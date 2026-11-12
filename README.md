# Nährwerte

Nährwert-App auf Basis der Schweizer Nährwertdatenbank (BLV).

## Veröffentlichen mit GitHub Pages
1. Alle Dateien dieses Ordners in ein neues Repository legen.
2. Settings → Pages → Source: *Deploy from a branch*, Branch `main`, Ordner `/ (root)`.
3. Nach ca. 1 Minute läuft die App unter `https://<benutzername>.github.io/<repo>/`.

## Auf dem iPhone
In Safari öffnen → Teilen → *Zum Home-Bildschirm*.

## Aktualisieren
`index.html` ersetzen und in `sw.js` die Version erhöhen (`naehrwerte-v2` …).

## Eigene Daten
Eigene Lebensmittel, Favoriten und Notizen speichert die App im Browser-Speicher (localStorage) des Geräts – nicht in index.html und nicht auf GitHub.
Sicherung: unten in der App «Sichern (Export)» → JSON-Datei; «Wiederherstellen (Import)» liest sie wieder ein.
