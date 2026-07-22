# Pierre Bretschneider Webdesign – Website-Prototyp

Vorschau-Version der neuen Website. Die komplette Seite steckt in **einer einzigen Datei**
(`index.html`) – Schriften, Styles, Skripte und alle Bilder sind eingebettet. Es werden
keine weiteren Dateien, kein Build und kein Server benötigt.

## Auf GitHub veröffentlichen (GitHub Pages)

1. Neues Repository auf github.com anlegen (z. B. `website-prototyp`).
2. Den Inhalt dieses Ordners hochladen (`index.html`, `.nojekyll`, `README.md`) –
   entweder per „Add file → Upload files“ im Browser oder per git push.
3. Im Repository: **Settings → Pages → Build and deployment**
   - Source: „Deploy from a branch“
   - Branch: `main`, Ordner: `/ (root)` → **Save**
4. Nach 1–2 Minuten ist die Seite erreichbar unter:
   `https://<dein-github-name>.github.io/<repo-name>/`

Die Unterseiten (Leistungen, Referenzen, Kontakt) laufen über `#/…`-Links und
funktionieren auf GitHub Pages ohne weitere Konfiguration.

## Hinweise

- **GitHub Pages ist öffentlich** – auch wenn das Repository privat ist, ist die
  veröffentlichte Seite für jeden mit dem Link erreichbar.
- Die enthaltenen Kundenstimmen (Google-Rezensionen) sind über den Webdesignvertrag
  freigegeben.
- Das Kontaktformular versendet in diesem Prototyp nichts; es dient nur der Ansicht.

## Aktualisieren

Neue Version bauen (im Hauptprojekt: `node build.mjs` im Ordner `prototyp/`, Ergebnis
`prototyp.html`), die Datei als `index.html` hierher kopieren und erneut hochladen.
