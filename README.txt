Trainingsplaner PWA 1-70

1. Alle Dateien zusammen auf einen HTTPS-Webserver hochladen (z.B. GitHub Pages, Netlify).
2. HTTPS-Adresse im Browser öffnen und über das Browsermenü „App installieren“ / „Zum Startbildschirm hinzufügen“ wählen.
3. Nach dem ersten erfolgreichen Laden kann die App offline verwendet werden.
4. Daten bleiben vorerst im localStorage des jeweiligen Browsers und der jeweiligen Webadresse.
5. WICHTIG: Daten aus einer zuvor lokal geöffneten HTML-Datei werden NICHT automatisch übernommen. Vorher JSON-Sicherung exportieren, in der PWA wieder importieren.
6. Für Sicherung und Gerätewechsel regelmässig JSON exportieren. Keine Datenbank, Benutzerkonten oder Cloud-Synchronisierung in dieser Version.

Der Planungsalgorithmus ist unverändert aus Version 1-69 übernommen.

Hinweis: Der lokale Speicherschluessel redog_v4 bleibt aus Kompatibilitaetsgruenden erhalten.
