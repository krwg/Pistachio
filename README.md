<div align="center">

# Pistachio Oil

**Premium cold-pressed pistachio oil — static product landing.**

[![Live demo](https://img.shields.io/badge/demo-GitHub%20Pages-d4a853?style=flat-square)](https://krwg.github.io/pistachio-oil/)
[![License](https://img.shields.io/badge/license-MIT-af52de?style=flat-square)](LICENSE)
[![Stack](https://img.shields.io/badge/stack-vanilla%20HTML-0071e3?style=flat-square)](docs/index.html)

</div>

---

A **single-page marketing site** for pistachio oil — Apple-inspired layout, scroll-driven sections, recipe cards, process carousel, and a mock checkout flow. Built as a **front-end portfolio piece** (no backend, no real payments).

**[→ Open site](https://krwg.github.io/pistachio-oil/)**

Page copy and UI are in **Russian** (product positioning for RU market). This README is in English for GitHub.

---

## Sections

| Block | Content |
|-------|---------|
| **Hero** | Product shot, price anchor, primary CTA |
| **Benefits** | Bento-style feature grid |
| **Specs** | Cold press, origin, bottle format |
| **Process** | Harvest → drying → press (image carousel) |
| **Recipes** | Salad, salmon, ice cream cards |
| **FAQ** | Accordion |
| **Buy** | Mock add-to-cart + mobile sticky bar |

---

## Tech

- One HTML file with inline CSS and JS (`docs/index.html`)
- PNG assets in `docs/assets/`
- Responsive: mobile nav, safe-area insets, reveal-on-scroll
- No build step, no framework

---

## Run locally

```bash
git clone https://github.com/krwg/pistachio-oil.git
cd pistachio-oil
npx --yes serve docs
# open http://localhost:3000
```

---

## Project layout

```
pistachio-oil/
├── docs/
│   ├── index.html
│   └── assets/       # product & recipe images
├── LICENSE
└── README.md
```

---

## Note

This is a **design / UX demo**, not a live store. Buttons simulate cart actions in the browser only.

---

<div align="center">

By [krwg](https://github.com/krwg) · static landing, no checkout backend

</div>
