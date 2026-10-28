# GameDev-Termine rund um Essen

Kuratierte Entwicklerkonferenzen, Indie-Showcases, Workshops, Game Jams und professionelle Netzwerktreffen im Umkreis von ungefähr 100 km um Essen.

## Struktur

- `index.html`: statische, responsive Terminübersicht
- `styles.css`: Gestaltung
- `events.json`: redaktionell gepflegte Veranstaltungsdaten

Abgelaufene Termine werden im Browser automatisch ausgeblendet. Neue oder geänderte Termine benötigen deshalb nur eine Aktualisierung von `events.json`.

## GitHub Pages aktivieren

1. Repository **Settings → Pages** öffnen.
2. Unter **Build and deployment** die Quelle **Deploy from a branch** auswählen.
3. Branch **main** und Ordner **/(root)** auswählen.
4. Speichern.

Danach ist die Seite unter <https://phreakmania.github.io/gamedev-events/> erreichbar.
