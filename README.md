# ☀️ The Solar System

An interactive, visually rich Solar System simulator built with pure HTML, CSS, and Canvas API. Explore all 8 planets orbiting the Sun with accurate relative orbital speeds, detailed information tooltips, and a beautiful space environment — all in a single file with zero dependencies.

**[🚀 Live Demo](https://solarsystemjs.github.io)**

![The Solar System](https://img.shields.io/badge/status-active-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![Dependencies](https://img.shields.io/badge/dependencies-none-success)

---

## ✨ Features

### 🪐 Planets & Celestial Bodies
- All **8 planets** with accurate relative orbital speeds based on real orbital periods
- **The Sun** with animated corona, surface details, and radial glow effects
- **Earth's Moon** orbiting Earth
- **Saturn's rings** rendered with elliptical perspective (3 ring layers)
- **Jupiter's atmospheric bands** and animated Great Red Spot
- **Asteroid belt** between Mars and Jupiter with 150 individual particles

### 🎨 Visual Effects
- 3D-like planet shading with radial gradients and light source simulation
- Twinkling star field (400 stars with individual twinkle speeds)
- Nebula-like background gradients
- Planet glow halos and orbital trails
- Hover highlight rings around planets
- Smooth animations at 60fps

### 💬 Information Tooltips
Hover over any planet or the Sun to see detailed information:
- Planet type and diameter
- Distance from the Sun
- Orbital period and day length
- Surface temperature
- Number of moons
- Fun astronomical facts

### 🎮 Controls
| Control | Action |
|---------|--------|
| **Speed Slider** | Adjust simulation speed (0× to 5×) |
| **⏸ Pause / ▶ Play** | Pause or resume the simulation |
| **↺ Reset** | Reset time, speed, zoom, and pan to defaults |
| **◯ Orbits** | Toggle orbital path lines |
| **Aa Labels** | Toggle planet name labels |
| **+ / −** | Zoom in and out |
| **Mouse Wheel** | Zoom in/out |
| **Shift + Drag** | Pan the view |
| **Middle Mouse Drag** | Pan the view |

### 💾 Persistent State
All simulation state is automatically saved to `localStorage` and restored on page reload:
- Current simulation time (planets resume their exact positions)
- Speed setting
- Pause state
- Zoom level
- Pan offset
- Orbit and label toggle states

Auto-saves every 2 seconds and on page visibility change or unload.

### 📱 Responsive Design
- Adapts to any screen size and aspect ratio
- Full support for **portrait** and **landscape** orientations
- Touch-friendly controls and tooltips
- Scales planet sizes and orbits proportionally to viewport
- Control bar wraps gracefully on small screens

---

## 🚀 Getting Started

### Quick Start

No build tools, no dependencies, no installation. Just open the file:

```bash
git clone https://github.com/solarsystemjs/solarsystemjs.github.io.git
cd solarsystemjs.github.io
```

Then open `index.html` in any modern browser.

### Deploy

Since this is a single HTML file, deployment is as simple as serving one file. It works out of the box with:

- **GitHub Pages** — push to the repository and enable Pages
- **Any static hosting** — upload `index.html`
- **Local file** — double-click `index.html` to open directly

---

## 🏗️ Project Structure

```
solarsystemjs.github.io/
├── index.html    # Entire application (HTML + CSS + JS)
└── README.md     # This file
```

Everything is contained in a single `index.html` file:
- **CSS** — embedded in `<style>` tags
- **JavaScript** — embedded in `<script>` tags
- **Favicon** — inline SVG data URI (no external files)
- **No external dependencies** — no frameworks, no libraries, no CDN links

---

## 🔭 Planet Data

Orbital speeds are proportional to real orbital periods:

| Planet | Orbital Period | Relative Speed |
|--------|---------------|----------------|
| Mercury | 88 days | Fastest |
| Venus | 225 days | |
| Earth | 365 days | Reference |
| Mars | 687 days | |
| Jupiter | 4,333 days | |
| Saturn | 10,759 days | |
| Uranus | 30,687 days | |
| Neptune | 60,190 days | Slowest |

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Ideas for Contributions
- Dwarf planets (Pluto, Ceres, Eris)
- Planet click-to-focus/follow camera
- Realistic elliptical orbits
- Sound effects or ambient space music
- Additional moons for Jupiter and Saturn
- Comet with tail effect
- Time display showing Earth date
- Keyboard shortcuts

---

## 📄 License

MIT
