# Moritz und Oskars Abenteuer

Ein-Knopf-Spiel für Kinder. Oskar (rot, O) oder Moritz (blau, M) spielen als
Ritter, Astronaut, Schulkind in Bützow oder junger Jedi – je drei Level, getrennte Profile
und Rekorde pro Junge.

- **Kurz tippen:** springen / hüpfen (Astronaut: nach oben schweben)
- **Lang drücken:** Schild (Ritter), Schutzschild (Astronaut), Schultüte saugt (Schulkind), Laserschwert-Schild (Jedi)

## Als App installieren

Die Seite öffnen: https://adler78hh.github.io/moritz-und-oskar-ein./ – dann:

- **iPad/iPhone (Safari):** Teilen-Symbol → „Zum Home-Bildschirm“
- **Android (Chrome):** Menü ⋮ → „App installieren“ bzw. „Zum Startbildschirm hinzufügen“

Nach dem ersten Öffnen läuft das Spiel auch ohne Internet.
Spielstände werden im Gerät gespeichert.

## Aufbau

Alles steckt in `index.html` (Canvas, kein Build-Schritt). `sw.js` sorgt
für den Offline-Betrieb, `manifest.webmanifest` und die Icons für die Installation.
