ABNEHM-COACH PRO v1.3 – PWA-PAKET

ENTHALTEN:
- index.html: bestehende App v1.3
- manifest.webmanifest: Installationsdaten und App-Symbol-Verweise
- sw.js: Service Worker für App-Shell und Offline-Start
- icons/: App-Symbole

VERÖFFENTLICHUNG:
Dieses Paket als ZIP direkt über Cloudflare Pages (Direct Upload) veröffentlichen.
Die Dateien müssen im Website-Hauptverzeichnis liegen; index.html ist der Einstieg.

WICHTIG VOR DEM WECHSEL VON file:// AUF HTTPS:
1. Öffne die bisherige lokale HTML-App.
2. Gehe zu Einstellungen > Datensicherung > Gesamte Daten exportieren.
3. Bewahre die JSON-Sicherungsdatei sicher auf.
4. Öffne nach Veröffentlichung die neue HTTPS-App und importiere die Sicherung über
   Einstellungen > Vollständige Sicherung wiederherstellen.
5. Dropbox in der HTTPS-App erneut verbinden. Browserdaten und OAuth-Verbindung
   sind je nach Ursprung getrennt und werden nicht automatisch von file:// übernommen.

Die App speichert weiterhin lokal im Browser (IndexedDB). Die Dropbox-Anbindung
bleibt eine separate Synchronisations-/Sicherungsfunktion. Die PWA-Veröffentlichung
überträgt keine persönlichen Trackingdaten in das Hosting.
