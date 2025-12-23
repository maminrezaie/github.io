# Portfolio (Static)

This is a fast, static portfolio website for **Mohammad Amin Rezaie**.

## Files
- `index.html` – main page
- `assets/css/style.css` – styling
- `assets/js/main.js` – smooth scroll + active nav highlight
- `assets/img/` – photos
- `assets/docs/` – resume PDF

## Quick preview (local)
Open `index.html` in your browser (double click), or run a simple local server:

### Python
```bash
cd portfolio_site
python -m http.server 8000
```
Then open http://localhost:8000

## Deploy (recommended)
### GitHub Pages
1. Create a repo (e.g. `portfolio`)
2. Upload everything in this folder
3. In GitHub → **Settings → Pages**
4. Set **Branch**: `main` and folder `/root` and Save

### Netlify
1. Drag-and-drop the folder in Netlify dashboard, or connect the repo.
2. Build command: *none*
3. Publish directory: `/` (root)

## Make the contact form work
This template includes a static-friendly form card. To make it functional:
- **Formspree**: replace `<form action="#">` with your Formspree endpoint action URL.
- **Netlify Forms**: add `netlify` attribute and a `name` attribute, then deploy on Netlify.

## Edit content
Open `index.html` and update text, add links (GitHub, LinkedIn, etc.), and add a “Projects” section if you’d like.
