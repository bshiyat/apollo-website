# Apollo Training Facility — Website

Custom single-page landing site for **Apollo Training Facility**, a premium gym on Mecca Street, Amman, Jordan.

## Structure

```
apollo-website/
├── index.html              ← Main file (CSS + JS inline)
├── assets/
│   ├── apollo-statue.png   ← Apollo Belvedere bronze statue (auto-downloaded)
│   └── apollo-statue-bust.png  ← Apollo marble bust (backup option)
└── README.md
```

## Tech Stack

- **Single `index.html`** — all HTML, CSS, JS inline (~2000 lines)
- **GSAP 3** via CDN — gsap core, ScrollTrigger, ScrollToPlugin
- **Google Fonts** — Cormorant Garamond (display) + Outfit (body)
- No build tools, no frameworks

## Features

- Page loader with split-text animation
- GSAP scroll-triggered image reveal animations (wipe overlays)
- Parallax effects on images and full-bleed image breaks
- Animated counter stats
- Testimonial carousel with prev/next arrows and progress bar
- Scrolling marquee text banner
- Timeline with scroll-progress line
- Scroll progress bar at top of page
- Noise texture overlay for film grain aesthetic
- Responsive design (mobile hamburger nav, stacked layouts)

## Images

- Gym photos load from Wix CDN during development
- For production, download all images to `assets/` and update src paths
- Apollo statue PNG included in `assets/`

## Color Scheme

| Token | Value | Use |
|-------|-------|-----|
| `--bg` | `#000000` | Page background |
| `--white` | `#FFFFFF` | Primary text, accents |
| `--text` | `#999999` | Body text |
| `--text-dim` | `#555555` | Labels, subtle text |
| `--border` | `#1A1A1A` | Borders, dividers |
| `--statue-glow` | `rgba(201,168,76,0.15)` | Hero statue glow (only gold) |

## Development

Just open `index.html` in a browser. No build step required.

## Contact

- **Phone:** +962 7 9979 2078
- **Location:** Mecca Street, Amman, Jordan
- **Hours:** Sat–Thu 6AM–11:30PM, Fri 11AM–7PM
