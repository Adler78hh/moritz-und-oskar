# Mo und Os Abenteuer

Ein-Knopf-Spiel für Kinder. Elf Figuren (Mo, Os, Id, Lu, Ki, Finn, The, Os W., Fin, Le, Fre)
spielen als Ritter, Geburtstagskind, Astronaut, Schulkind in Bützow oder junger Jedi – je drei Level,
eigene Profile und Rekorde pro Figur.

- **Kurz tippen:** springen / hüpfen (Astronaut: nach oben schweben)
- **Lang drücken:** Schild (Ritter), Schutzschild (Astronaut), Schultüte saugt (Schulkind), Laserschwert-Schild (Jedi), Geschenk hochwerfen (Geburtstagskind)

## Als App installieren

Die Seite öffnen: https://adler78hh.github.io/moritz-und-oskar/ – dann:

- **iPad/iPhone (Safari):** Teilen-Symbol → „Zum Home-Bildschirm“
- **Android (Chrome):** Menü ⋮ → „App installieren“

Nach dem ersten Öffnen läuft das Spiel auch ohne Internet. Spielstände werden im Gerät gespeichert.

## Aufbau

Alles steckt in `index.html` (Canvas, kein Build-Schritt). `sw.js` sorgt für den
Offline-Betrieb, `manifest.webmanifest` und die Icons für die Installation.
