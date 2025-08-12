# Nordfriesland Logistik – Abfahrtskontrolle (PWA)

Installierbare Web-App für die LKW-Abfahrtskontrolle mit Checkliste, Pflicht-Fotos bei Mängeln, Logo, digitaler Unterschrift, PDF-Erzeugung und Mailversand via Google Apps Script.

## Schnellstart (GitHub Pages)
1. Repository anlegen (öffentlich), z. B. `nordfriesland-logistik-abfahrtskontrolle`
2. `index.html` und `README.md` hochladen
3. Settings → Pages → Source: *Deploy from a branch* → Branch: `main`, Folder: `/ (root)` → Save
4. URL: `https://<DEIN-NUTZERNAME>.github.io/nordfriesland-logistik-abfahrtskontrolle/`
5. Android: Seite in Chrome öffnen → Menü (⋮) → **Zum Startbildschirm hinzufügen** (PWA)

## Apps Script (Mailversand)
- `EMAIL_ENDPOINT` in `index.html` ist gesetzt – falls du die Apps-Script-URL änderst, passe sie hier an.
- In Apps Script „Als Web-App bereitstellen“ → Zugriff: **Jeder, auch anonym**.
