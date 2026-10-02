# Claude — Personal Portfolio Website

A single-page personal portfolio website for **Girish Lade** — a multi-disciplinary developer, UI/UX designer, and AI tools creator. Built as one self-contained HTML file: no build step, no dependencies, no backend.

## Features

- **Multi-page SPA experience** — Home, About, Services, Projects, and Contact sections with smooth JS page navigation
- **Hero landing section** — gradient hero with typewriter-animated headline, CTA buttons, and glassmorphic feature card
- **Services showcase** — six service cards (Web Development, AI Tools Development, UI/UX Design, Mobile App Development, Data Science, Brand Strategy)
- **Projects gallery** — cards for six projects (Voice-to-Text Quick Notes, Girish AI Chatbot, Caesar Cipher tools, Parallax Website, Retro Chatbot) with links to their GitHub repos
- **Contact form** — builds a pre-filled `mailto:` link so messages open in the visitor's own email client (no server required)
- **About section** — journey, skills/technologies, vision, and social links (Instagram, LinkedIn, GitHub, CodePen, email)
- **Responsive design** — mobile hamburger menu, adaptive grid layouts, smooth scroll effects and scroll-triggered card animations

## Tech Stack

- Pure HTML5 + CSS3 (custom, no frameworks)
- Vanilla JavaScript (page routing, form handling, IntersectionObserver animations, typing effect)
- System/inter font stack — zero external requests

## Quick Start

No build step needed — just open the file:

```bash
git clone https://github.com/girishlade111/Claude.git
cd Claude
# open index.html in any browser, or serve it:
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Project Structure

```
Claude/
├── index.html   # Entire site: markup, styles, and scripts in one file
└── README.md    # This file
```

## Deploy

Any static host works — GitHub Pages, Cloudflare Pages, Netlify, Vercel:

1. Push the repo to GitHub
2. Enable GitHub Pages on the default branch (root) — done automatically for this repo

## License

© 2025 Girish Lade. All rights reserved.

---

Built by Girish Lade — [ladestack.in](https://ladestack.in)
