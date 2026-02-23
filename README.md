# 爪尺 米 | SYSTEM_CORE

A high-performance, cinematic personal portfolio with a hacker-terminal aesthetic. Built with raw HTML, CSS, and JavaScript — no frameworks, no bloat.

## 🖥️ Live

**[mdmisumon.pro.bd](https://mdmisumon.pro.bd)**

## ⚡ Features

### Terminal Portfolio (`index.html`)
- **CRT scanline overlay** — retro terminal feel with a modern grid background
- **Neko Bot** — interactive cat companion with eye-tracking, sleep mode, happy & rage states
- **Scramble text animations** — CJK character scramble on scroll reveal
- **Custom cursor** — dot + ring system with magnetic hover effects
- **Glassmorphism cards** — frosted glass UI with glow-on-hover

### Interactive Silk Canvas (`silk.html`)
- **WebGL generative art** — real-time symmetry drawing powered by D3.js
- **Custom color system** — rainbow palette + gradient swatches with instant preview
- **6-fold rotation** — clickable segment controls for rotational symmetry
- **Mirror & Spiral** — toggle effects for kaleidoscope-style patterns
- **Auto-color mode** — automatic color cycling with solid/gradient modes

### Typing Defense (`typing.html`)
- Custom typing game module

### Projects Lab (`projects.html`)
- Project showcase with terminal-style navigation

## 🏗️ Project Structure

```
portfolio-terminal/
├── index.html          # Main portfolio landing page
├── projects.html       # Projects showcase
├── silk.html           # Interactive Silk generative art canvas
├── typing.html         # Typing defense game
├── CNAME               # Custom domain config
└── silk_files/         # Silk engine dependencies
    ├── site.js         # Core Silk engine
    ├── site.css        # Silk styles
    ├── d3.v3.min.js    # D3.js for generative graphics
    ├── jquery-1.8.1.min.js
    ├── knockout-2.2.0.min.js
    ├── underscore.min.js
    ├── keymaster.js    # Keyboard shortcut handler
    ├── noise.js        # Perlin noise generator
    ├── detect.js       # Device detection
    ├── jquery.fullscreen.js
    ├── normalize.css
    └── ss-social.css
```

## 🎨 Design System

| Token | Value | Usage |
|-------|-------|-------|
| `--green` | `#00FF41` | Primary accent, text, borders |
| `--red` | `#FF003C` | Rage state, alerts |
| `--dark` | `#000000` | Background |
| Font | JetBrains Mono | Monospace UI |
| Font | Noto Serif SC | CJK decorative |
| Font | Playfair Display | Headings |

## 🚀 Deployment

Hosted on **GitHub Pages** with custom domain.

```bash
# Clone
git clone https://github.com/mdmisumon/portfolio-terminal.git

# Open locally
# Just open index.html in a browser — no build step needed
```

## 📜 License

© 2026 MD Mi Sumon. All rights reserved.
