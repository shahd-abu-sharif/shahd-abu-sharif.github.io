<div align="center">

# Shahd Abu Sharif — Portfolio

**Backend Engineer · Team Lead · Software Architect**

A personal portfolio showcasing my work in backend engineering, system design, and database architecture.

[![Live Site](https://img.shields.io/badge/Live_Site-View_Now-00d4ff?style=for-the-badge&logo=vercel&logoColor=white)](https://shahd-abu-sharif.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-7f5af0?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/eng-shahd-abu-sharif)
[![Email](https://img.shields.io/badge/Email-Contact-ff6ac1?style=for-the-badge&logo=gmail&logoColor=white)](mailto:eng.shahd.abusharif@gmail.com)

</div>

---

## ✨ About

A single-page portfolio built with pure **HTML, CSS, and vanilla JavaScript** — no frameworks, no build step. Designed with a **dark editorial theme** featuring cyan/violet accents, smooth animations, and a focus on readability.

> "From vision to execution."

---

## 🎯 Features

- **Animated hero** — typewriter effect, gradient name, entrance animations
- **Tech stack marquee** — infinite scroll of technologies I work with
- **Code identity card** — `shahd.ts` snippet introducing who I am
- **Skills with animated bars** — fill-up animation on scroll with shimmer
- **Featured projects grid** — 6 projects with 3D tilt on hover
- **Experience timeline** — animated line draw + staggered card reveals
- **Education & certifications** — academic background and credentials
- **Working contact form** — powered by Formspree, sends straight to my inbox
- **Custom cursor** — dot + ring that follows the mouse (desktop only)
- **Scroll progress bar** — visual indicator of reading position
- **Fully responsive** — mobile-first, tested on all screen sizes
- **Accessible** — respects `prefers-reduced-motion`

---

## 🛠️ Tech Stack

<div align="center">

| Category | Tools |
|----------|-------|
| **Languages** | HTML5 · CSS3 · Vanilla JavaScript |
| **Fonts** | [Fira Code](https://fonts.google.com/specimen/Fira+Code) · [Instrument Serif](https://fonts.google.com/specimen/Instrument+Serif) |
| **Form** | [Formspree](https://formspree.io) |
| **Deployment** | GitHub Pages |
| **Icons** | Emoji + inline SVG |

</div>

> No frameworks. No dependencies. No build tools. Just clean, hand-written code.

---

## 📁 Project Structure

```
portfolio/
├── index.html                              # Main page — everything lives here
├── files/
│   ├── me.png                              # Profile photo (transparent PNG)
│   └── eng-Shahd-M-Abu-Sharif-CV.pdf      # Downloadable CV
├── favicon.ico                             # Optional site icon
└── README.md
```

---

## 🚀 Run Locally

No setup required — it's just static files.

**Option 1 — Just open it**
```bash
# Double-click index.html
```

**Option 2 — Local server (recommended)**
```bash
# Python 3
python -m http.server 8000

# or Node.js
npx serve

# Then visit http://localhost:8000
```

---

## 🌐 Deployment

This site is deployed via **GitHub Pages**.

To deploy your own version:

1. Fork this repo
2. Go to **Settings → Pages**
3. **Source:** `Deploy from a branch`
4. **Branch:** `main` · folder `/ (root)`
5. Save — your site is live at `https://<username>.github.io/<repo>/`

---

## 📬 Contact Form Setup

The contact form uses **[Formspree](https://formspree.io)** — no backend needed.

To make it work for your own fork:

1. Create a free account on [formspree.io](https://formspree.io)
2. Create a new form → copy your **Form ID**
3. In `index.html`, find:
   ```html
   action="https://formspree.io/f/YOUR_FORM_ID"
   ```
4. Replace `YOUR_FORM_ID` with your actual ID

Free tier includes **50 submissions/month** — plenty for a portfolio.

---

## 🎨 Design System

**Color Palette**

| Variable | Value | Usage |
|----------|-------|-------|
| `--bg` | `#0a0c11` | Background |
| `--text` | `#e6e9ef` | Primary text |
| `--cyan` | `#00d4ff` | Accent 1 |
| `--violet` | `#7f5af0` | Accent 2 |
| `--green` | `#2cb67d` | Success / "Available" |
| `--pink` | `#ff6ac1` | Accent 3 |

**Typography**
- **Headings:** Instrument Serif (italic accents)
- **Body:** Fira Code (monospace aesthetic)

---

## ✅ Browser Support

| Chrome | Firefox | Safari | Edge |
|:------:|:-------:|:------:|:----:|
| ✅ 90+ | ✅ 88+  | ✅ 14+ | ✅ 90+ |

Requires support for `IntersectionObserver`, `backdrop-filter`, and CSS custom properties — all modern browsers qualify.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

**Note:** Personal content (photo, CV, and written text) is **not** covered by the MIT license — please replace with your own.

---

## 🙏 Credits

- Design & development — **Shahd Abu Sharif**
- Fonts — [Google Fonts](https://fonts.google.com)
- Form handling — [Formspree](https://formspree.io)
- Deployment — [GitHub Pages](https://pages.github.com)

---

<div align="center">

**© 2026 Shahd Abu Sharif**

Built with ☕ and clean architecture.

⭐ If you like this project, consider giving it a star!

</div>