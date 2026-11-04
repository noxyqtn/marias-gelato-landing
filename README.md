# Maria's Gelato – Landing Page

Landing Page für **Maria's Gelato – Greek Sweet**, eine Eisdiele in Romanshorn (Schweiz).

## Design & Stil

* **Stil:** Apple / MacOS Liquid Glass (Glassmorphism) mit `backdrop-filter: blur`, halbtransparente Container, dünne weiße Ränder, abgerundete Ecken (`rounded-3xl`)
* **Styling:** Tailwind CSS (via CDN)
* **Typografie:** Inter (Google Fonts)
* **Sprache:** Deutsch (Standarddeutsch, Schweiz)
* **Responsive:** Mobil und Desktop optimiert

## Inhalte

* Titel & Untertitel
* Adresse: Hafenstrasse 58, 8590 Romanshorn
* Telefon: 076 607 87 83 (klickbar via `tel:`-Link)
* Öffnungszeiten
* Hinweis: Selbstbedienung
* Spezial-Card: Geburtstagstorten auf Anfrage
* Menü-Raster: Kaffee, Bubble Waffle, Eis, Griechische Süssigkeiten
* Footer: Handgemacht & eigene Produktion, Preise inkl. 8.1% MwSt.

## Dateien

* `index.html` – die Landing Page (einzelne HTML-Datei, keine Build-Schritte nötig)
* `README.md` – diese Datei

## Deployment (Netlify)

1. Repository bei GitHub erstellen (oder dieses Repository verwenden)
2. Bei [Netlify](https://netlify.com) anmelden und „Add new site“ → „Import an existing project“ wählen
3. Dieses GitHub-Repository verbinden
4. Build-Einstellungen lassen (kein Build nötig, statische HTML-Datei)
5. Site deployen – die Seite ist danach unter der Netlify-URL erreichbar

Alternativ per Drag & Drop: Den Ordner mit `index.html` direkt auf [app.netlify.com/drop](https://app.netlify.com/drop) ziehen.

## Lokales Testen

Die Datei `index.html` kann einfach im Browser geöffnet werden, da Tailwind über CDN geladen wird:

```bash
# Beispiel mit Python (optional, nur für lokalen Server)
python -m http.server 8000
```

Dann unter `http://localhost:8000` öffnen.

## Lizenz

Keine – frei nutzbar für Maria's Gelato.
