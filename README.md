# Mandrudi Tools

Interaktive Werkzeuge fuer Supply Chain, SAP & KI - Mandrudi KOAM SRL.
Ziel-Hosting: https://tools.mandrudi.com (GitHub Pages).

## Struktur
- `index.html` - Uebersicht (Root)
- `<tool>/index.html` - je Tool (16 Stueck)
- `CNAME` - Custom Domain
- `.nojekyll` - kein Jekyll-Processing

## Deployment (GitHub Pages)
1. Repo auf GitHub anlegen und diesen Ordner pushen.
2. Settings -> Pages -> Source: Branch `main`, Ordner `/ (root)`.
3. Custom domain `tools.mandrudi.com` (CNAME-Datei liegt bei).
4. IONOS DNS: CNAME-Eintrag `tools` -> `<dein-github-user>.github.io`.
5. HTTPS aktiviert GitHub automatisch. Hauptseite + E-Mail bleiben unberuehrt.
