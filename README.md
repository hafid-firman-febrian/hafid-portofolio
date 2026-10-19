# Hafid — Portfolio

Static site, no build step.

- `index.html` — home
- `case-studies.html` — case studies (served at `/case-studies`)
- `assets/` — portrait, project covers and screenshots

## Deploy to Vercel

**Drag & drop:** vercel.com → Add New → Project → drop this folder.

**CLI:**
```
npm i -g vercel
cd hafid-portfolio
vercel --prod
```

Framework preset: **Other**. Build command: none. Output directory: `.` (root).
