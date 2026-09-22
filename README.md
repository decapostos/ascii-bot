# ascii-bot

An ASCII-art head rendered with Three.js — a 3D head drawn as text
characters on a black canvas.

Single-file static site: `index.html` plus Three.js `0.152.2` loaded from
CDN (unpkg primary, jsdelivr fallback).

## Run

```sh
python3 -m http.server 8126
# open http://localhost:8126/index.html
```

Needs network access for the Three.js CDN scripts.

## Live

https://thefullctx.github.io/ascii-bot/

This repo is the source of truth, served via GitHub Pages.
