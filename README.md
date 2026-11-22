# 3D ASCII Florist — Procedural Bouquet Generator

A self-contained, single-file HTML5 Canvas 3D ASCII art studio that procedurally generates and renders interactive, continuously rotating floral bouquets in real time — with zero external libraries, zero network requests, and full offline support.

## Highlights
- **Custom 3D ASCII Rendering Engine**: Indexed 3D triangle mesh rasterizer mapped directly onto a high-DPI monospace character grid, paired with slope-aware directional ASCII stems (`|`, `/`, `\`, `-`), screen-space petal contour separation (`Edges`), semantic per-material character ramps, and a lightweight 1/4-resolution phosphor bloom pass (`Glow`).
- **12 Procedural 3D Botanical Species**: Roses, rosebuds, tulips, cymbidium orchids, calla lilies, daisies, sunflowers, ruffled peonies, stargazer lilies with protruding stamens, pincushion proteas, wildflower spikes, plus berries, kangaroo paw branches, eucalyptus sprigs, ferns, and satin ribbon bows.
- **Collision-Free Florist Composer**: Seeded deterministic 3D golden-spiral layout with multi-step repulsion relaxation so blooms remain airy, balanced, and readable from every 360° angle across 4 silhouettes (*Dome*, *Airy*, *Round*, *Asymmetric*).
- **Curated Presets & Palettes**: 6 one-click presets (*Autumn Luxe*, *Wildflowers*, *Velvet Roses*, *Spring Pastel*, *Golden Sun*, *Midnight Garden*) and 7 harmonic color palettes, plus full customization of species mix, bloom count, greenery, ribbon color, optional translucent contour veil, and custom glowing dedication captions.
- **Built-in Export & Sharing**: Download crisp PNG snapshots, copy live plain-text ASCII art to clipboard, or copy reproducible URL hash recipes (`#b=...`).

## Quick Start
Open `bouquet.html` directly in any modern desktop or mobile browser — no build step or server required.

## Controls
- **Drag / Scroll**: Orbit, tilt, and zoom
- `Space` — Pause / Play rotation
- `Tab` — Toggle studio sidebar
- `N` — Generate new variation
- `D` — Cycle ASCII grid density (`Detailed` / `Ultra` / `Classic`)
- `E` — Toggle petal edge contours
- `G` — Toggle phosphor glow
- `R` — Reset camera view
- `H` — Hide / show all UI overlays
