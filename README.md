# 🧊 Icy Climb Demo

A pure HTML5/CSS/JavaScript arcade climbing game. No frameworks, no assets, no build step — one file.

**Play it:** https://oelhalawany.github.io/icy-tower-demo/

> **Disclaimer:** This is a non-commercial demo project made for learning purposes only. It is not affiliated with or endorsed by any existing game or its rights holders. All code and graphics here were written from scratch for this project.

## Features

- 🧊 Endless procedurally generated floors — platforms shrink as you climb
- 💨 Wall-bounce momentum: build speed by bouncing between walls
- 🎨 Everything drawn with Canvas (no image files)
- 🏆 Score based on the highest floor reached

## Controls

| Key | Action |
| --- | ------ |
| ← / → | Move |
| Space | Jump |

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
# then open http://localhost:8000
```

## Deploy to GitHub Pages

1. Push this repo to GitHub (branch `main`).
2. Repo → **Settings** → **Pages**.
3. Under **Source**, pick **Deploy from a branch** → branch `main`, folder `/ (root)` → **Save**.
4. Wait ~1 minute, then open `https://<username>.github.io/icy-tower-demo/`.
