# Color Palette Generator

A coolors.co-inspired color palette tool built as a single HTML file. No frameworks, no server — just open `index.html` in your browser.

## Features

- **Full-screen color strips** — Each color fills a vertical strip across the viewport
- **5 harmony modes** — Complementary, Analogous, Triadic, Split-Complementary, Monochromatic
- **Free pick mode** — Edit each strip independently
- **Color picker** — Hue ring + saturation/lightness square for precise color selection
- **Drag to reorder** — Rearrange strips by dragging
- **Lock colors** — Protect individual colors from shuffling
- **Add/remove colors** — 2 to 10 strips, add with the + buttons between strips
- **Spacebar shuffle** — Randomize unlocked colors instantly
- **WCAG contrast checker** — Shows AA/AAA/Fail badges between adjacent colors
- **Save/load palettes** — Save palettes by name to localStorage
- **Dark/light theme** — Toggle with the sun/moon button, persists across sessions
- **Paint mode** — Full-screen canvas with 4 FX modes (Glow, Ribbon, Metaball, Particles)
- **Click to copy** — Click any hex code to copy it to clipboard

## Usage

1. Open `index.html` in a browser
2. Press **Spacebar** to generate random palettes
3. **Hover** a strip to see controls (lock, edit, remove, drag)
4. Click **Edit** to open the color picker
5. Click **Contrast** in the toolbar to see accessibility ratings
6. Click **Saved** to save/load palettes

## Tech

- Vanilla HTML/CSS/JavaScript
- No dependencies
- Everything in one file
