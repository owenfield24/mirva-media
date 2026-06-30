# Mirva Media — website

A single-page static site (HTML/CSS/JS, no build step) plus a Terms page.

## Files
- `index.html` — the site
- `terms.html` — Terms of Service (draft; have an attorney review)
- `MIRVA-Logo.png`, `MIRVA-Logo-transparent.png` — logo assets

## Run locally
Open `index.html` in a browser, or serve the folder:
```
python3 -m http.server 8787
```

## Deploy (Vercel)
This repo is a static site — Vercel needs no build settings.
1. Push to GitHub.
2. In Vercel: **Add New → Project → Import** this repo.
3. Framework preset: **Other** · Build command: *(none)* · Output dir: `./`
4. Deploy. Every push to `main` auto-deploys.

## Quote form
The form posts to Formspree (`/f/xwvdnppg`). Submissions arrive by email
once the form is activated (confirm the first submission via Formspree's email).
