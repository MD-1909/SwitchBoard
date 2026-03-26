# ⚡ SwitchBoard — Indian Modular Switchboard Layout Planner

A single-page web app for planning Indian modular switchboard layouts room by room. Design your electrical switchboard panels visually with drag-and-drop, then print/export the complete layout with diagrams and component tables.

![No frameworks. Just vibes.](https://img.shields.io/badge/frameworks-zero-brightgreen) ![Single file](https://img.shields.io/badge/file-just%20one-blue) ![AI built](https://img.shields.io/badge/built%20by-GitHub%20Copilot-blueviolet)

---

## ✨ Features

- **Room Management** — Create, rename, delete, and reorder rooms
- **Panel Sizing** — 6 / 12 / 18 module panels (Indian standard plates)
- **Drag & Drop** — Drag components from the palette onto the switchboard grid
- **Pair-Based Layout** — Each row of 6 modules is split into 3 pairs of 2, just like real Indian modular plates
- **1-Module & 2-Module Components** — Sockets fill a full pair (2 modules); switches occupy a single slot
- **Custom Labels** — Right-click any placed component to add/edit a label (e.g., "Fan 1", "AC outlet")
- **Visual SVG Components** — Every component has a unique SVG icon that looks like the real thing
- **Print / Export** — Generates a full printable report with:
  - Visual plate diagrams (SVG) for every panel in every room
  - Summary tables with slot, component, and label details
  - Blank plates consolidated into a single row to save space
  - Page breaks between rooms
- **Persistent Storage** — All data saved to `localStorage` automatically
- **Dark Mode UI** — Easy on the eyes during those late-night electrical planning sessions

## 🔌 Supported Components

| Component | Modules | Icon |
|-----------|---------|------|
| 6A Socket | 2M | 🔌 |
| 16A Socket | 2M | 🔌 |
| 5-Pin Socket | 2M | ⏣ |
| 1-Way Switch | 1M | ◻ |
| 2-Way Switch | 1M | ◻ |
| Fan Regulator | 1M | 🌀 |
| Indicator Light | 1M | 💡 |
| Bell Switch | 1M | 🔔 |
| USB Charger | 1M | 🔋 |
| Blank Plate | 1M | ▬ |
| TV / DTH | 1M | 📺 |
| Ethernet / Data | 1M | 🌐 |

## 🚀 Usage

1. Open `index.html` in any modern browser. That's it. No build step, no `npm install`, no server.
2. Create rooms using the sidebar
3. Add panels (6 / 12 / 18 modules) to each room
4. Drag components from the palette onto the switchboard grid
5. Right-click placed components to add labels or remove them
6. Hit **⎙ Print / Export** to generate a printable report of all rooms

## 🛠️ Tech Stack

- **React 18** — loaded via CDN (no build tooling needed)
- **Babel Standalone** — in-browser JSX transpilation
- **Vanilla CSS** — dark mode, CSS variables, zero dependencies
- **localStorage** — persistence with automatic save
- **Native HTML5 Drag & Drop API**
- **Inline SVG** — hand-crafted component visuals

All in a single `index.html` file. No `node_modules` were harmed in the making of this project.

## 📸 Screenshots

Open the file in your browser and try it out — the UI speaks for itself.

## 🤖 Credits

**This entire project was built by [GitHub Copilot](https://github.com/features/copilot) (Claude Opus 4.6) — from the first line to the last.**

Every single line of HTML, CSS, JavaScript, React component, SVG icon, drag-and-drop handler, print layout, and this README was written by AI through an iterative conversation. The human contributor provided the vision, requirements, and feedback — the AI did all the coding.

Built with ❤️ by a machine that doesn't even have hands to flip a light switch.

## 📄 License

MIT — do whatever you want with it.
