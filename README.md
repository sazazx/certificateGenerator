# PNG → PDF Annotator

A zero-dependency, single-file web app to annotate images and export them as PDFs.

**Live site:** `https://YOUR_USERNAME.github.io/YOUR_REPO/`

## Features
- Upload PNG / JPG / WEBP
- Click anywhere on the image to place text
- Drag pins to reposition text
- Customise font, size, color, weight
- Export as a full-resolution PDF

## How to deploy

```bash
git init
git add .
git commit -m "init"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

Then on GitHub: **Settings → Pages → Branch: `main` → `/ (root)` → Save**

## Tech
- HTML5 Canvas API (built-in)
- [jsPDF](https://github.com/parallax/jsPDF) via CDN
- Google Fonts via CDN
- No build step · No npm · No framework
