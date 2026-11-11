# Medikamenten-App V6 (offline)

GitHub Pages: Den **Inhalt** dieses Ordners in die Wurzel des Repositories hochladen. `index.html`, `app.js`, `styles.css`, `sw.js`, `manifest.webmanifest` und `icons/` müssen nebeneinander liegen.

## Neu
- Packungsgröße, Restbestand, Grenzwert, Tablettenverbrauch je Einnahme; Verbrauch wird bei dokumentierter Einnahme abgezogen und bei Rücknahme wieder gutgeschrieben.
- Dosis in mg und Stärke je Tablette zur Berechnung von Bruchteilen (nicht jede Tablette darf geteilt werden).
- Termine mit ICS-Export für den iPhone-Kalender (keine automatische bidirektionale Synchronisation).
- Fachärzte mit Kontaktdaten und Zuordnung zu Terminen.

**Wichtig:** Vorratswarnungen erscheinen beim Öffnen der App, nicht zuverlässig als Hintergrund-Push. Daten lokal im Browser speichern und regelmäßig JSON-Backup exportieren. Vor dem Upgrade Backup erstellen. Vorratszähler für Altbestände beginnen erst mit der neuen Version und werden nicht rückwirkend aus alten Logs errechnet.
