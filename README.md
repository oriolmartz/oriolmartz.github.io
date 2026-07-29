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
- `warehouse-optimizer-demo.mp4`

The Narrative Shift walkthrough is not included in the supplied source ZIP. Its card opens an intentional preview placeholder without requesting a missing file. To activate it later:

1. Add `assets/video/narrative-shift-demo.mp4`.
2. In `index.html`, find the Narrative Shift video button.
3. Set `data-video="narrative-shift-demo.mp4"` and remove `data-video-pending="true"`.

## Local preview

From this folder:

```powershell
python -m http.server 8000
```

Open `http://localhost:8000`.
