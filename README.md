# 🌌 Aether OS

A browser-based desktop environment — built in a single `index.html` file with pure HTML, CSS, and Vanilla JS. No frameworks, no dependencies, no build step. Just open it.

---

## ✨ Features

### Desktop
- **Live animated wallpaper** — procedural canvas: 520 twinkling stars, drifting nebula wisps, aurora sine-wave bands, random shooting stars
- **Mouse parallax** — move your cursor to shift star layers at different depths
- **Desktop icons** — double-click to launch apps
- **Right-click context menu** — quick-launch apps from anywhere on the desktop

### Window Manager
- **Draggable windows** — grab any title bar to move
- **Minimize / Close** — macOS-style traffic-light buttons
- **Active state** — clicking a window brings it to the front (z-index management)
- **Position persistence** — `localStorage` remembers where you left each window after refresh

### Taskbar
- **Start Menu** — animated slide-in app launcher
- **Taskbar buttons** — click to toggle minimize/restore
- **Live clock** — time + date, updates every second

---

## 📦 Apps

| App | Icon | Description |
|---|---|---|
| **Terminal** | 🖥️ | Interactive shell with `neofetch`, `ls`, `echo`, `help`, ↑↓ history |
| **System Info** | ⚡ | Live system stats — time, kernel, RAM, CPU cores, session uptime |
| **Notepad** | 📝 | Auto-saving notes with `localStorage` — 3 independent note slots |
| **Calendar** | 📅 | Month view with today highlighted, navigate months |
| **Calculator** | 🔢 | Full arithmetic calculator with keyboard support |
| **Chess** | ♟️ | Fully playable 2-player chess with legal move enforcement |

---

## 🎨 Customisation

Open `index.html` and edit the CSS variables at the top:

```css
:root {
  --accent-color: #00f2ff;   /* change to any neon: #ff00aa, #39ff14, #bf86ff */
}
```

### Wallpaper Ideas
The background is a procedural canvas — to tweak the colours, find the nebula wisp array in the `LiveWallpaper` IIFE and change the `c1` RGBA values.

---

## 🖥️ Terminal Commands

| Command | Output |
|---|---|
| `help` | List available commands |
| `neofetch` | System summary card |
| `ls` | Mock file listing |
| `whoami` | Current user |
| `uname -a` | OS system string |
| `version` | OS version |
| `time` | Current time |
| `echo <text>` | Print text |
| `clear` | Clear output |

Arrow keys ↑ ↓ navigate command history.

---

## 🚀 Usage

1. Download or clone the repo
2. Open `index.html` in any modern browser (Chrome, Edge, Firefox)
3. No server required — it's 100% client-side

```
Aether os/
└── index.html   ← the entire OS
└── README.md    ← this file
```

---

## 🛠️ Tech Stack

| Layer | Tech |
|---|---|
| Structure | HTML5 |
| Styling | Vanilla CSS (Flexbox / Grid / backdrop-filter) |
| Logic | Vanilla JS (ES2020) |
| Storage | `localStorage` |
| Animation | Canvas 2D API + `requestAnimationFrame` |
| Fonts | Google Fonts (Inter, JetBrains Mono) |

---

*Built with Antigravity AI · Aether OS v1.0.0*
