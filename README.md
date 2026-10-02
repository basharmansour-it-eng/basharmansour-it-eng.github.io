# Bashar Mansour — Portfolio

Personal portfolio of **Bashar Mansour**, a Flutter developer and Informatics Engineering graduate (Software
Engineering track) from Damascus University, Syria.

🔗 **Live site:** [basharmansour-it-eng.github.io](https://basharmansour-it-eng.github.io)

---

## 📖 About

A single-page, fully responsive portfolio that presents my background, skills, and mobile and desktop projects.
It is hand-written with plain HTML, CSS, and JavaScript, with no frameworks, no build step, and no external
libraries, so it loads fast and can be hosted anywhere.

---

## ✨ Features

- **Bilingual:** English and Arabic, with a full right-to-left layout in Arabic
- **Dark and light themes** that follow the same colour palette
- **Remembers your choices:** the selected language and theme are saved between visits
- **Project showcase:** each project is displayed inside a CSS-drawn phone or laptop frame that tilts toward the
  cursor and enters the page with a 3D animation
- **Project gallery:** clicking a project opens a full-screen viewer with a swipeable and draggable carousel,
  arrow buttons, dot indicators, and keyboard support (`Esc` to close, `←` `→` to navigate)
- **Working contact form:** messages are delivered straight to my inbox through [Web3Forms](https://web3forms.com),
  with a spam trap and clear success and error messages
- **One-click copy** for email and phone, with a confirmation toast
- **Motion with purpose:** typewriter hero title, animated constellation background, scroll-reveal text,
  animated skill bars, 3D-tilt cards, magnetic buttons, custom cursor, and a scroll-progress bar
- **Responsive:** tuned for desktop, tablet, and phone, with a slide-in mobile menu
- **Accessible:** keyboard navigation, focus styles, labelled controls, and support for
  `prefers-reduced-motion`

---

## 🧰 Tech stack

| Area | Technology |
| --- | --- |
| Markup and styling | HTML5, CSS3 (custom properties, Grid, Flexbox, 3D transforms) |
| Behaviour | Vanilla JavaScript (ES6+) |
| Graphics | Canvas API and inline SVG icons |
| Contact form | [Web3Forms](https://web3forms.com) |
| Hosting | GitHub Pages |

---

## 📁 Project structure

```
.
├── index.html            # The entire site: markup, styles, and scripts
├── images/
│   ├── profile.jpg       # Profile photo
│   ├── stockmate/        # hero.png + gallery/1.png … 8.png
│   ├── chance/
│   ├── citizen/
│   └── loadbalancer/
└── README.md
```

---

## 💻 Run locally

No installation is required. Download or clone the repository and open `index.html` in any modern browser:

```bash
git clone https://github.com/basharmansour-it-eng/basharmansour-it-eng.github.io.git
cd basharmansour-it-eng.github.io
```

Then double-click `index.html`, or serve the folder with any static server, for example
`python -m http.server 8000`.

---

## 🛠️ Customise

All editable content sits near the top of the `<script>` section in `index.html`:

| What to change | Where |
| --- | --- |
| Email, phone, and Web3Forms access key | `EMAIL`, `PHONE`, `WEB3FORMS_KEY` |
| Projects (names, type, tech tags, image folders) | `PROJECTS` |
| Skills shown in the Skills section | `SKILLS` and `TECH` |
| Navigation links | `NAV` |
| All English and Arabic text | `I18N` (`en` and `ar` blocks) |
| Contact cards | `CONTACTS` |

**Project images:** put a cover image at `images/<project>/hero.png` and screenshots at
`images/<project>/gallery/1.png`, `2.png`, `3.png`, and so on. Missing images are skipped automatically, and a
placeholder is shown until they are added.

---

## 🚀 Deployment

The site is deployed with **GitHub Pages** from the `main` branch. Pushing a change to `main` publishes it
automatically within a minute or two.

---

## 📬 Contact

- ✉️ [basharman2003@gmail.com](mailto:basharman2003@gmail.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/bashar-mansour)
- 🐙 [GitHub](https://github.com/basharmansour-it-eng)
- 📍 Damascus, Syria
