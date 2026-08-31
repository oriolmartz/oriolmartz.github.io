# Oriol Martínez Ribas — AI Engineering Portfolio

Static portfolio prepared for GitHub Pages.

## Publish as a personal GitHub Pages site

Create a public repository named exactly:

```text
oriolmartz.github.io
```

Then open PowerShell in this folder and run:

```powershell
git init
git add .
git commit -m "Publish AI engineering portfolio"
git branch -M main
git remote add origin https://github.com/oriolmartz/oriolmartz.github.io.git
git push -u origin main
```

In GitHub, open **Settings → Pages** and select:

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/(root)**

The site will be available at `https://oriolmartz.github.io/`.

## Structure

```text
index.html
assets/
  about/
  projects/
  video/
  social-preview.png
.nojekyll
robots.txt
sitemap.xml
404.html
```

## Demo videos

Included and connected:

- `flight-delay-risk-demo.mp4`
- `quant-regime-tracer-demo.mp4`
- `evidenceroute-demo.mp4`
- `narrative-shift-demo.mp4`
- `warehouse-optimizer-demo.mp4`

All five walkthroughs are included under `assets/video/` and connected from `index.html`.

## Local preview

From this folder:

```powershell
python -m http.server 8000
```

Open `http://localhost:8000`.
