# FurFeast

Static export of the FurFeast Smart Pet Feeder site.

## Contents

- `index.html` — homepage
- `404.html` — not-found page
- `author/` — author archive pages
- `wp-content/` — themes, plugins, uploads
- `wp-includes/` — WordPress core assets (needed for static rendering)

Generated via Simply Static. Serve as-is with any static host.

## Local preview

```powershell
# PowerShell — serve current folder on http://localhost:8000
python -m http.server 8000
```

## Deploy

Push to `main` to update the connected GitHub repo.
