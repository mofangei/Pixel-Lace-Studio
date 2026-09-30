# 🩷 Pixel Lace Studio
![HTML5 Canvas](https://img.shields.io/badge/HTML5-canvas-e34f26)
![Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen)
![Live Demo](https://img.shields.io/badge/live-demo-ff69b4)

A free, browser-based studio for designing ornate **pixel lace** — the delicate, symmetric dot-and-grid patterns you see all over Pinterest. Place a few pixels and let symmetry bloom them into doilies, florals, and filet-crochet-style charts. No sign-up, no install, nothing leaves your device.

**▶ Live: https://mofangei.github.io/pixel-lace/**

---

## ✨ What it does

The whole idea: real lace is symmetric, so instead of placing every dot by hand, you paint once and it mirrors across 2, 4, or 8 axes automatically. A handful of dots near the center becomes an intricate doily.

### Drawing
- **12 symmetry modes** — Free, Mirror ↔, Mirror ↕, Diagonal ⟍, Diagonal ⟋, X-fold (both diagonals), Quarter (4-way), Radial (8-way), Turn ×2 (180° rotational), Pinwheel (4-fold rotational), plus **Tile 4** and **Tile 9** for seamless repeating patterns.
- **Tools** — brush, eraser, eyedropper, fill bucket, and **color swap** (recolor every pixel of one color at once).
- **Freeform Move** — grab any connected shape and drag it anywhere; rotate and flip it while carrying.
- **Brush sizes** — 1× through 6× for fine detail or chunky lace.
- **Adjustable grid** — 16×16 up to 128×128.

### Color
- Curated lace palette plus a **custom color picker** and a separate **backdrop** color.
- **Palette themes** — one-click swaps: Coquette, Gold, Pastel, Ocean.
- **Pixel shape** — render cells as squares, round **beads**, or cross-**stitch** X's for a beadwork / chart look.

### Starting points
- **12 starter motifs** — Bloom, Doily, Scallop, Lattice, Crystal, Heart, Daisy, Tulip, Rose, Blossom, Sunflower, Lily.
- **🎲 Surprise me** — generates a fresh random symmetric pattern to remix.

### Image tracing
- Drop or upload any image as a **reference guide** (adjustable opacity, fit, scale, and position). The guide never appears in exports.
- **Trace to grid** — convert the image into editable pixels, in original colors or matched to your palette, with optional background removal. Great for turning a logo or word into pixel lace.

### Save, share & export
- **Save / load** designs in your browser, with auto-restore of your latest canvas.
- **Backup / import** all designs as a `.json` file to move between devices.
- **Shareable links** — the design is encoded into a URL so anyone can open and remix it.
- **Export** as **PNG** or **SVG** (with an optional transparent background).
- **Seamless preview** — see your design tiled 3×3 as a wallpaper/border test.
- **Timelapse recorder** — record your build and export it as a video, with speed control and an optional transparent background.

### Comfort
- **Dark / light theme** (remembers your choice).
- Full keyboard shortcuts.

---

## ⌨️ Shortcuts

| Key | Action |
|-----|--------|
| `B` | Brush |
| `E` | Erase |
| `I` | Eyedropper |
| `G` | Fill bucket |
| `S` | Color swap |
| `V` | Freeform move |
| `R` / `F` | Rotate / flip the grabbed shape |
| `Esc` | Drop the grabbed shape |
| `⌘/Ctrl + Z` | Undo |
| `⌘/Ctrl + Shift + Z` | Redo |

---

## 🚀 Run it yourself

It's a **single self-contained HTML file** — no build step, no dependencies, no server.

- **Online:** hosted free on GitHub Pages (see the link above).
- **Offline:** download `index.html` and open it in any browser. It keeps working with no internet.

---

## 🛠️ Tech

Vanilla HTML, CSS, and JavaScript in one file. All rendering is done on an HTML canvas, and all your data (saved designs, preferences) lives in your browser's local storage. Nothing is uploaded anywhere.

---


Feel free to fork it, remix it, and make it your own.
