# California Sea Lion Habitat

An interactive 3D model of a California sea lion habitat (modeled after the Central Park Zoo / Bronx Zoo style enclosure), built as a single self-contained HTML file using [Three.js](https://threejs.org/).

**Made by Mehak Wadhwa.**

## View it

- **Live:** **[https://mehak-w.github.io/Sea_Lion/](https://mehak-w.github.io/Sea_Lion/)**
- **Local:** download `index.html` and double-click it. Opens in any modern browser; no install or build step required.

## Controls

| Action | How |
|---|---|
| Rotate the view | Click + drag |
| Zoom in/out | Mouse scroll |
| Auto-rotate (presentation mode) | Press **R** |
| Read scene coordinates | Hover the mouse — `(x, z)` shown bottom-right |

## Features

- **Stadium-shaped enclosure** with iron railing, double hedge ring on top of the wall, and a long info sign on the front section
- **Pool** with animated wave-shader water + raised iron lip at the edge
- **Topographic stacked-slab rocks** in the central formation, the back mountain, the cave, and the front extension — built from layered ExtrudeGeometry slabs with peanut/ellipse outlines
- **Cave** with stacked slab walls in a partial ring, dome roof, and a single front entrance
- **Back rock land** with a wavy front edge, dense yellow grass tufts, bare trees, and a separate mini-island enclosure on the back-left
- **Outside environment**: paved walkway, distant city skyline (two rings of buildings), trees, gradient sky with cloud sprites
- **Procedural textures** — every surface uses canvas-generated noise textures (no external image files)
- **Soft shadows** (PCFSoftShadowMap) and ACES tone mapping

## Tech

- Three.js r0.160.0 loaded via importmap from unpkg (CDN only)
- ES modules — no bundler, no build step
- Pure WebGL via Three.js, no plugins
- Single ~50 KB self-contained HTML file

## Credit

Built and modeled by **Mehak Wadhwa**.
