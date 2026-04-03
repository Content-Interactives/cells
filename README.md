# Cells

Single-page WebGL lesson built with Three.js (loaded from CDN) inlined in `index.html`. [Standards.md](Standards.md) describes NGSS alignment.

**Live:** https://content-interactives.github.io/cells

## Development

No install or bundler. Options:

- Open `index.html` in a browser (file:// may restrict some APIs—prefer a server).  
- From this directory:

```bash
npx serve .
```

## Layout

- `index.html` — entire scene, scripts, and styles (single-file app)

## Stack

Three.js r128 (cdnjs), HTML5, inline CSS/JS.

## Deployment

Push `index.html` (and any future assets) to the static host root for the `cells` GitHub Pages site.
