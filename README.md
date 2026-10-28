# Phúc Long Website — BOD draft

Static site. Open `index.html` (it forwards to `Phuc Long Website.dc.html`).

## Publish on GitHub Pages
1. Create a new repository on GitHub.
2. Upload **everything inside this folder** to the repository root (keep folder structure, including `_ds/` and the `.nojekyll` file).
3. Settings → Pages → Source: **Deploy from a branch** → Branch: `main` / `(root)` → Save.
4. After 1–2 minutes the site is live at `https://<your-username>.github.io/<repo-name>/`.

Notes
- `.nojekyll` must be kept — without it GitHub hides the `_ds/` folder (brand fonts and styles).
- Viewers need an internet connection (the page runtime loads React from a CDN).
- Do not open the files by double-clicking on your computer; they need to be served from a web address (GitHub Pages, or any web server).
