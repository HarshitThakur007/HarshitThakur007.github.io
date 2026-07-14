# Harshit Thakur — Portfolio

Personal portfolio site. Plain HTML/CSS/JS, no build step, ready for GitHub Pages.

## Files
- `index.html` — page content
- `style.css` — dark, developer-style theme
- `script.js` — nav toggle, typewriter effect, scroll reveal
- `Harshit-Thakur-Resume.pdf` — downloadable résumé (linked from the hero section)

## Deploy to GitHub Pages

**Option A — user site (recommended, gives you `harshitthakur007.github.io`)**

1. Create a new GitHub repo named exactly: `HarshitThakur007.github.io`
2. From this folder, run:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/HarshitThakur007/HarshitThakur007.github.io.git
   git push -u origin main
   ```
3. Go to the repo → Settings → Pages → Source → set to `Deploy from branch`, branch `main`, folder `/ (root)`.
4. Your site goes live at **https://harshitthakur007.github.io** within a minute or two.

**Option B — project site (any repo name, e.g. `portfolio`)**

Same steps, but the URL will be `https://harshitthakur007.github.io/portfolio/`.

## Updating content later
- Edit the **FinTrack** project card in `index.html` (search for `id="projects"`) once it has a live link or repo — just add an `<a>` around the title or a "view project" button.
- Swap `Harshit-Thakur-Resume.pdf` any time you update your résumé — keep the filename the same so the download link keeps working.
- Colors/theme live at the top of `style.css` under `:root`.

## Local preview
Any static server works, e.g.:
```bash
python3 -m http.server 8000
```
Then open http://localhost:8000
