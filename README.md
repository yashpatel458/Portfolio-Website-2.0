# Portfolio Website 2.0

Personal portfolio of **Yash Patel** — Software Engineer & QA Automation Analyst based in Toronto, Canada.

A fast, single-page site built with plain HTML, CSS, and JavaScript — no frameworks, no build step. Just open it and it works.

## ✨ Features

- **Interactive 3D scenes** — a [Spline](https://spline.design) animation in the hero, and a robot that follows your cursor in the contact section
- **Dark / light theme** — toggle in the nav, remembered across visits, and respects your OS preference on first load
- **Fully responsive** — adapts from desktop to mobile; 3D scenes are skipped entirely on small screens so phones never pay the WebGL cost
- **Performance-minded** — lazy-loaded scenes, responsive images (WebP with JPEG fallbacks), preconnected fonts
- **Accessible** — semantic sections, ARIA labels, keyboard-friendly mobile menu, honors `prefers-reduced-motion`
- **SEO-ready** — Open Graph tags, JSON-LD structured data, meta descriptions

## 📑 Sections

1. **About** — who I am and what I work with
2. **Experience** — roles including Fidelity Investments
3. **Education** — academic background
4. **Projects** — 14 projects, from full-stack apps (RequestRouter, EduMavericks, Aeroquest, TripHackr, CVMate) to fun front-end builds (Simon Game, Drum Kit, Diceysion)
5. **Achievements & Certifications**
6. **Contact** — email and socials, with the cursor-tracking robot

## 🛠️ Tech

| | |
|---|---|
| Markup & styling | HTML5, modern CSS (custom properties, grid, flexbox) |
| Interactivity | Vanilla JavaScript (theme toggle, lazy scene injection, mobile menu) |
| 3D | [`@splinetool/viewer`](https://www.npmjs.com/package/@splinetool/viewer) web component |
| Typography | DM Serif Display, DM Sans, DM Mono (Google Fonts) |

## 🚀 Run locally

No dependencies to install — serve the folder with any static server:

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

(Opening `index.html` directly also works, but a local server is needed for the contact-section Spline scene to load.)

## 📁 Structure

```
├── index.html          # the entire site — markup, styles, and scripts
├── assets/
│   └── robot-scene.splinecode   # local Spline scene for the contact section
└── img/                # profile, portfolio screenshots (WebP + JPEG), favicons
```

## 📬 Contact

- **Email:** yashpatel.sde@gmail.com
- **LinkedIn:** [linkedin.com/in/yashpatel458](https://linkedin.com/in/yashpatel458)
- **GitHub:** [github.com/yashpatel458](https://github.com/yashpatel458)
- **Twitter:** [@yashpatel458](https://twitter.com/yashpatel458)

---

© Yash Patel. Design and content are personal — feel free to draw inspiration from the code, but please don't republish the site as your own.
