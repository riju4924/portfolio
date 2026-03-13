# Mrinmoy Mukherjee — Personal Portfolio

A clean, aesthetic, and fully responsive personal portfolio website built with pure HTML, CSS, and JavaScript. Designed with a dark luxury editorial aesthetic featuring gold and violet accents.

🌐 **Live Site:** [your-portfolio.vercel.app](https://your-portfolio.vercel.app)

---

## Preview

> Dark-themed portfolio with animated scroll reveals, a hero section, skills grid, experience timeline, project showcase, and contact section.

---

## Features

- **Single-file architecture** — everything in one `index.html`, zero dependencies
- **Fully responsive** — works on mobile, tablet, and desktop
- **Scroll animations** — elements reveal smoothly as you scroll
- **Active nav highlighting** — navigation updates based on scroll position
- **No frameworks or build tools** — just open the file and it works

---

## Sections

| Section | Description |
|---|---|
| Hero | Full-screen intro with animated grid background |
| About | Personal bio with stat cards |
| Skills | Categorized technical skills grid |
| Experience | Education card + work experience timeline |
| Projects | Project showcase with metrics and tech stack |
| Activities | Achievements and extracurriculars |
| Contact | Links to email, GitHub, LinkedIn, LeetCode |

---

## Tech Stack

- **HTML5**
- **CSS3** — CSS variables, Grid, Flexbox, animations
- **Vanilla JavaScript** — IntersectionObserver for scroll reveals
- **Google Fonts** — Playfair Display, DM Mono, DM Sans

---

## Getting Started

No installation or build step required.

**Option 1 — Open locally:**
```bash
# Just open the file in your browser
open index.html
```

**Option 2 — Clone and run:**
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
open index.html
```

---

## Deployment

This site is deployed on **Vercel** via GitHub integration. Every push to `main` triggers an automatic redeploy.

To deploy your own fork:
1. Fork this repository
2. Go to [vercel.com](https://vercel.com) → New Project → Import your fork
3. Click Deploy — no configuration needed

---

## Customization

To update the portfolio with your own information, edit `index.html` directly:

- **Personal details** — name, location, phone, email in the hero and contact sections
- **Social links** — replace `href` values for GitHub, LinkedIn, and LeetCode
- **Projects** — duplicate the `.project-card` block and update the content
- **Colors** — all colors are CSS variables at the top of the `<style>` block:

```css
:root {
  --accent: #c8a96e;   /* gold */
  --accent2: #7c6eab;  /* violet */
  --bg: #0a0a0f;       /* background */
}
```

---

## Project Structure

```
portfolio/
└── index.html    # Entire site — HTML + CSS + JS in one file
└── README.md
```

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

*Built by Mrinmoy Mukherjee — CSE Student at The Neotia University, Kolkata*
