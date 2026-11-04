# NKZS Rechnungen
PWA fuer Angebote und Rechnungen von NKZS (Foto, Video, Social Media Management). Eine Datei, laeuft offline.

## Aufbau
- index.html (~128 KB, App inkl. Style und Script)
- sw.js (Cache), manifest.webmanifest, icon-*.png
- Bei Aenderungen Cache-Version in sw.js erhoehen, sonst sieht man alte Staende.

## Konventionen
- Sprache: Deutsch. Keine Build-Schritte, Aenderungen direkt in der Datei testen (Doppelklick oder lokaler Server).
- Nur gezielt lesen: grosse Dateien per Suche/Zeilenbereich oeffnen, nicht komplett laden.
- Deployment: Push auf main, GitHub Pages.
