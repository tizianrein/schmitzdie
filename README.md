# SchmitzDie Hausmeisterservice – Webseite

Statische Webseite (HTML/CSS, ohne Abhängigkeiten).

## Struktur

```
index.html            Startseite (mit Referenz-Slideshow)
ueber-uns.html        Über uns
leistungen.html       Leistungen
referenzen.html       Referenzen (Bildergalerie)
kontakt.html          Kontakt (mit Google Maps)
impressum.html        Impressum (bitte vervollständigen!)
images/referenzen/    Referenzfotos (referenz-1.jpg … referenz-6.jpg)
.nojekyll             Deaktiviert Jekyll auf GitHub Pages
```

## Eigene Fotos einbauen

Einfach die Platzhalter in `images/referenzen/` durch eigene Fotos ersetzen –
Dateinamen beibehalten (`referenz-1.jpg` usw.), Querformat ca. 1200×900 px oder größer.
Die Bildunterschriften stehen in `index.html` und `referenzen.html` (Suche nach `cap`).

## Auf GitHub Pages veröffentlichen

1. Auf github.com ein neues Repository anlegen (z. B. `schmitzdie-website`).
2. Alle Dateien aus diesem Ordner ins Repository hochladen
   (auf GitHub: "Add file" → "Upload files" – auch den Ordner `images` mit hochladen).
3. Im Repository: **Settings → Pages**.
4. Unter "Build and deployment" als Source **Deploy from a branch** wählen,
   Branch `main` und Ordner `/ (root)`, dann **Save**.
5. Nach 1–2 Minuten ist die Seite unter
   `https://BENUTZERNAME.github.io/schmitzdie-website/` erreichbar.

Eigene Domain (z. B. schmitzdie.de): unter **Settings → Pages → Custom domain**
eintragen und beim Domain-Anbieter einen CNAME auf `BENUTZERNAME.github.io` setzen.

## Vor dem Livegang

- Impressum vervollständigen (Inhabername usw.)
- Datenschutzerklärung ergänzen (wegen Google Maps Pflicht)
