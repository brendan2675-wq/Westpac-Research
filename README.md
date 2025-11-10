# Westpac Research Practice Lead Cover Page

This repo contains the single-page cover experience created for the Westpac Research Practice Lead application. It mirrors the GEL-inspired layout you prototyped in Cursor and is ready to deploy via GitHub Pages (or any static host).

## Structure

```
.
├── index.html                # Entry point for GitHub Pages
├── cover-page.html           # Working copy (kept for reference)
└── assets
    └── images
        ├── brendan-profile.png          # Portrait shown in the hero
        └── warehouse-background.jpg     # Background image for hero
```

> The `assets/images` directory includes placeholder filenames. Add your actual image files before publishing.

## Getting Started

1. Drop your hero portrait and background image into `assets/images/`, matching the filenames above.
2. Open `index.html` in a browser to confirm everything renders as expected.
3. Update any copy or links directly in `index.html` (and mirror in `cover-page.html` if you keep both files).

## Deploying To GitHub Pages

1. Create a new public repository (e.g., `westpac-research-lead-cover`).
2. Copy these files into the repo and commit:
   ```bash
   git init
   git add .
   git commit -m \"Add Westpac cover page\"
   ```
3. Push to GitHub:
   ```bash
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
4. In GitHub, go to **Settings → Pages**, select **Deploy from branch**, choose `main` and `/ (root)` as the folder, then save. Pages will provide a URL once the site builds.

## Customising Further

- To change imagery, swap files in `assets/images/` with the same filenames.
- If you want to externalise the CSS, move the `<style>` block into `assets/styles.css` and link it from `index.html`.
- Replace the mail link and portfolio URL with live ones if they change.

## License

This page is a personal application artifact; no open-source license is applied. You are free to use and adapt it for your own application materials.

