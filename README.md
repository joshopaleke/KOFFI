# KOFFI ☕

> *Love for Koffi, Fear of Small Places.*

A premium coffee brand landing page built as part of the **30 Days Challenge By Amarachi Iwueze** challenge. Pixel-perfect recreation of a Figma design with scroll-driven animations and rich micro-interactions.

---

## ✨ Features

- **Scroll-Driven Stacked Card Deck** — 3 cards animate in one by one as you scroll, stacking and tilting like a physical deck of cards using a fixed-panel + spring physics engine
- **NimbuDemo Custom Font** — loaded via `@font-face` to match the Figma design exactly
- **Animated Hero Section** — pink highlight bar slides in behind "SMALL", illustration floats, CTAs fade up in sequence
- **Spring Physics** — smooth `lerp`-based easing on all scroll animations (no GSAP dependency)
- **One-Way Ratchet** — cards accumulate as you scroll down; they never exit once entered
- **Cursor Glow** — subtle pink radial gradient that follows the mouse
- **Fully Responsive** — flat card list on mobile (≤ 860px), full animation on desktop
- **Accessible** — ARIA labels, focus-visible outlines, `prefers-reduced-motion` support

---

## 🖥️ Preview

| Hero | Card Stack |
|------|------------|
| Animated headline with pink bar, illustration, badge | Cards slide up and tilt into a layered deck |

---

## 🗂️ Project Structure

```
KOFFI/
├── index.html          # Single-file app — all HTML, CSS, JS
├── Group 1.png         # Hero illustration
├── hands-heart.svg.svg # Card 1 icon
├── hands-clac.svg.svg  # Card 2 icon
├── hands-hello.svg.svg # Card 3 icon
├── Frame.svg           # Supporting asset
├── coffee-01.svg       # Supporting asset
├── fonts/
│   ├── NimbuDemo-Regular.otf
│   ├── NimbuDemo-Medium.otf
│   ├── NimbuDemo-SemiBold.otf
│   └── NimbuDemo-Bold.otf
└── .gitignore
```

---

## 🚀 Running Locally

No build step needed. Just open `index.html` in your browser:

```bash
# Clone the repo
git clone https://github.com/joshopaleke/KOFFI.git
cd KOFFI

# Open in browser (macOS)
open index.html

# Or serve it locally
npx serve .
```

---

## 🎨 Design

- **Color Palette:**
  - Forest Green `#09543D`
  - Deep Brown `#461E10`
  - Blush Pink `#FFA9E9`
  - Cream `#FFFDF7`
- **Fonts:** NimbuDemo (custom), Poppins, Inter, Joti One

---

## 🛠️ Tech Stack

| Layer | Choice |
|-------|--------|
| Markup | Semantic HTML5 |
| Styling | Vanilla CSS (custom properties, `@font-face`, `position:fixed`) |
| Animation | Vanilla JS (`requestAnimationFrame` + `lerp` spring physics) |
| No frameworks | Zero dependencies |

---

## 📅 Context

This project is a self-challenge going from zero to job-ready design engineer by building real Figma-to-code projects every day.

---

*Made with ☕ and a healthy fear of small places.*
