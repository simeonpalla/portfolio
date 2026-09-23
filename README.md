# Simeon Palla | Portfolio

Personal portfolio of Simeon Palla, a data-driven generalist working across governance, energy, education, road safety and software.

**Live:** [simeonpalla.github.io/portfolio](https://simeonpalla.github.io/portfolio/)

## Sections

The range of work, experience, featured project (ADB AI for Safer Roads 2026, Top 10), things I've built, research and writing, skills, education and credentials, contact.

## Tech

A single static `index.html`. No build step and no framework.

- 3D hero: a wave-animated data globe with arcs and orbiting rings, built with [Three.js](https://threejs.org) (loaded from a CDN)
- Aurora and film-grain backdrop, glassmorphism cards with 3D tilt and cursor spotlight
- A hand-drawn animated SVG artwork for each project
- A scroll-driven journey timeline that lights up as you read
- Responsive down to phone width; respects `prefers-reduced-motion`; falls back gracefully without WebGL

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

## Deploy

Served by GitHub Pages from the `main` branch root.
