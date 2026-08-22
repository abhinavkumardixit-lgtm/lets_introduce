# Abhinav Kumar Dixit — Portfolio

Personal portfolio site for **Abhinav Kumar Dixit** — AI/ML & Cloud Engineer, showcasing projects, skills, and experience across AI, cloud architecture (GCP), full-stack development, and geospatial data analysis.

## 🔗 Links

- **Live site:** _add your deployed URL here_
- **GitHub:** [abhinavkumardixit-lgtm](https://github.com/abhinavkumardixit-lgtm)
- **LinkedIn:** [abhinav-kumar-dixit](https://www.linkedin.com/in/abhinav-kumar-dixit-39a4a03a3)

## 🛠 Tech Stack

| Layer | Tools |
|---|---|
| Structure | HTML5, Bootstrap 5 |
| Styling | CSS3, custom design tokens |
| Interactivity | JavaScript, jQuery |
| Animation | GSAP (ScrollTrigger, ScrollSmoother, SplitText), AOS |
| Sliders | Swiper.js |
| Popups | Magnific Popup |
| Counters | PureCounter |

## ✨ Features

Core template features:
- Custom cursor, animated preloader
- Off-canvas mobile navigation
- GSAP-powered scroll animations and smooth scrolling
- Portfolio grid with hover interactions
- Marquee brand/logo strip

Additional features layered on top (see `assets/css/extra-features.css` and `assets/js/extra-features.js`):
- ✅ Light/dark mode toggle
- ✅ Cookie consent banner
- ✅ Site search (⌘K / Ctrl+K) across projects and sections
- ✅ Scroll progress bar (GSAP ScrollSmoother-aware)
- ✅ Copy-link buttons on each project card
- ✅ Print stylesheet
- ✅ Skip-to-content link for accessibility
- ✅ UTM tracking on outbound GitHub / LinkedIn / project links
- ✅ Contact form with inline validation, error states, and a success state
- ✅ Confirmation modal before sending a message
- ✅ "Last updated" date in the footer
- ✅ Floating "Say hello" contact button
- ✅ Expandable FAQ section

> These additions live in two standalone files (`extra-features.css` / `extra-features.js`) so they layer cleanly on top of the base template without touching `main.css` or `main.js`.

## 📁 Folder Structure

```text
.
├── index.html
├── README.md
├── vercel.json
├── _gitignore
├── _nojekyll
└── assets/
    ├── css/
    │   ├── main.css
    │   └── extra-features.css   ← new
    ├── js/
    │   ├── main.js
    │   └── extra-features.js    ← new
    ├── images/
    └── fonts/
```

## ▶ Run Locally

```bash
git clone <your-repo-url>
cd <your-repo>
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## 🌐 Deployment

Deploys cleanly to **Vercel** (config already included in `vercel.json`) or GitHub Pages (`_nojekyll` included to skip Jekyll processing).

## 🎨 Customization

- Personal info, projects, and contact details live directly in `index.html`.
- Theme accent color for the new features can be adjusted via the `--ef-accent` CSS variable in `assets/css/extra-features.css`.
- FAQ content and search index entries are defined at the top of `assets/js/extra-features.js`.

## 📄 License

Personal portfolio — content and copy belong to Abhinav Kumar Dixit. Template structure customized for personal use.

---

<div align="center">

**Abhinav Kumar Dixit** · AI/ML & Cloud Engineer

</div>
