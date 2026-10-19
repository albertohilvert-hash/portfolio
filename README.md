# Portfolio Alberto Hilvert

Persönliche Webseite (eine Seite, Deutsch). Läuft als Cloudflare Worker mit statischen Dateien.

- Live: https://portfolio.hamolskyhilvert.org/
- Inhalt: `public/index.html` (Seite) und `public/portrait.jpg` (Porträt)
- Konfiguration: `wrangler.jsonc`

## Hochladen

```
npx wrangler deploy
```

Unter Windows PowerShell bei Skript-Fehlern `npx.cmd wrangler deploy` verwenden.
