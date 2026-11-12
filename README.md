# RJ Carpets website

Static site (no build step). Files: `index.html`, `images/`, `video/`.

## Deploy on GitHub Pages
1. Create a GitHub account, then click **New repository**. Name it e.g. `rj-carpets`, set it to Public, and create it.
2. Click **uploading an existing file**, drag in everything inside this folder (index.html, images, video, .nojekyll), and click **Commit changes**.
3. Go to **Settings > Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, choose branch `main` and folder `/ (root)`, then Save.
4. After 1 to 2 minutes the site is live at `https://YOUR-USERNAME.github.io/rj-carpets/`.

Tip: name the repository `YOUR-USERNAME.github.io` to get the shorter address `https://YOUR-USERNAME.github.io/`.

## Custom domain (optional)
Settings > Pages > Custom domain, then point your domain's DNS to GitHub Pages.

## Editing
Open `index.html` in any text editor. Swap photos by replacing files in `images/` (keep the same names) and videos in `video/`.
