# Simeon Palla | Portfolio

Personal portfolio of Simeon Palla. Data, public policy, infrastructure and technology: turning complex problems into evidence, tools and decisions.

**Live:** [simeonpalla.github.io/portfolio](https://simeonpalla.github.io/portfolio/)

## What's on the page

- **Approach:** an interactive problem-to-decision flow across four domains (road safety, education, governance, AI products)
- **Selected work:** Speed Safety Score (ADB AI for Safer Roads 2026, Top 10) as a full case study with a live explorer and an illustrative road-network map; GovLens AP and Expense Tracker as visual stories; FilmECHO, mst-abs and Car Price Prediction under "More work"
- **Experience:** seven roles as chapters, each with a plain-language headline, what was done and the tools used
- **Research and toolbox:** policy briefs, research interests and a skills toolbox
- **About and contact**

## Tech

A single static `index.html` plus self-hosted fonts. No build step and no framework.

- 3D hero: a wave-animated data globe with arcs and orbiting rings, built with [Three.js](https://threejs.org) (loaded from a CDN)
- Hand-built SVG graphics: an animated road-network map, project artwork, an icon sprite, phone mock-up
- Aurora and film-grain backdrop, glass cards with 3D tilt and a cursor spotlight, staggered reveals, scroll progress line and a scroll-driven experience spine
- Type: Instrument Sans, Instrument Serif and JetBrains Mono, self-hosted in `fonts/` as fixed-weight WOFF2 (SIL Open Font License), so weights render the same in every browser including Safari
- Sized for laptop screens (1280 to 1920 wide) with roomy, scrollable sections; stacks cleanly on tablets and phones; tested in Chromium and WebKit (Safari's engine)
- Respects `prefers-reduced-motion`; falls back gracefully without WebGL

## Colours

Four tokens at the top of `index.html` (`--c1` to `--c4`) plus `--bg`, `--ink` and `--muted` drive the whole site, including the 3D scene and the SVG artwork.

## Run locally

Serve the folder (fonts need to load over HTTP, not from a `file://` path):

```bash
python -m http.server 8000
```

## Deploy

Served by GitHub Pages from the `main` branch root.
