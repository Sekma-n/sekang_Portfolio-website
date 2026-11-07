# `README.md`

Here's a professional, corporate-grade README tailored to your portfolio repository. Copy it into a file named **`README.md`** at the root of your GitHub repository (`sekma-n/sekang_Portfolio-website`).

```markdown
# Sekang Segotso — Portfolio Website

> **Website Developer · South Africa**
> Responsive, accessible, and performant web experiences built with HTML, CSS, JavaScript and Java.

[![Live Demo](https://img.shields.io/badge/Live_Demo-sekma--n.github.io-6d7cff?style=for-the-badge&logo=githubpages&logoColor=white)](https://sekma-n.github.io/sekang_Portfolio-website/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#tech-stack)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#tech-stack)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#tech-stack)
[![License](https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge)](#license)

---

## 📋 Overview

A personal portfolio website designed to showcase my work, technical skills, professional experience, and verified certifications. The site is built from scratch with **semantic HTML5, modern CSS3, and vanilla JavaScript** — no build tools, no frameworks, no dependencies. It is fully responsive, cross-browser tested, and optimised for performance and accessibility.

**Live site:** [https://sekma-n.github.io/sekang_Portfolio-website/](https://sekma-n.github.io/sekang_Portfolio-website/)

---

## ✨ Features

| Feature | Description |
| :--- | :--- |
| **Dark / Light Theme** | Persisted theme toggle using `localStorage`; applied before first paint to avoid flash. |
| **Responsive Layout** | Fluid grids, mobile-first breakpoints, and a collapsible navigation menu tested from 320 px upward. |
| **Typewriter Hero** | Rotating role titles (Website Developer, Java Developer, Front-End Coder, UI Designer) with a blinking caret. |
| **Scroll Reveal** | Sections animate into view using `IntersectionObserver`; respects `prefers-reduced-motion`. |
| **Sticky Navigation** | Navigation bar with backdrop blur and a subtle border that appears on scroll. |
| **Structured Data** | Semantic sections for About, Skills, Projects, Experience, and Certifications. |
| **Accessibility** | Keyboard-navigable menu, `aria-current` on active links, descriptive `alt` text, and focus states. |
| **Performance** | Optimised assets, system font fallback, and zero runtime dependencies. |

---

## 🧱 Tech Stack

- **HTML5** — semantic structure and accessible markup
- **CSS3** — custom properties (variables), Grid, Flexbox, responsive media queries
- **JavaScript (ES5+)** — theme persistence, mobile menu, scroll reveal, typewriter effect
- **Google Fonts** — Inter typeface
- **GitHub Pages** — static hosting and deployment

> **No frameworks, no bundlers, no npm.** The entire site is hand-written HTML, CSS, and JavaScript.

---

## 📑 Page Sections

| # | Section | Description |
| :--- | :--- | :--- |
| 01 | **About** | Professional summary, quick facts, and CV download. |
| 02 | **Skills** | Languages, frameworks & tools, and development practices. |
| 03 | **Projects** | Three selected builds — Portfolio, Online Booking System, and Responsive Landing Page. |
| 04 | **Experience** | Timeline of freelance and internship roles. |
| 05 | **Certifications** | Verified Coursera credential — *Create Your First Python Program From UST* (Grade: 100%). |
| — | **Contact CTA** | Direct links to email, phone, GitHub, and LinkedIn. |

---

## 📁 Project Structure

```text
sekang_Portfolio-website/
├── index.html              # Home / landing page
├── About.html              # About page
├── skills.html             # Skills page
├── Projects.html           # Projects page
├── experience.html         # Experience page
├── contact.html            # Contact page
├── logo.png                # Site favicon and navbar logo
├── sekang.webp             # About-page avatar
├── sekang2.webp            # Hero visual
├── Sekang_Segotso_Web_Developer_CV.pdf
└── README.md               # This file
```

> **Note:** All pages share an identical design system (theme variables, navigation, footer, and interaction scripts) for a consistent experience across the site.

---

## 🚀 Getting Started

No installation or build step is required.

```bash
# 1. Clone the repository
git clone https://github.com/sekma-n/sekang_Portfolio-website.git

# 2. Navigate into the project
cd sekang_Portfolio-website

# 3. Open index.html in your browser
#    or serve it locally:
python3 -m http.server 8000
```

Then visit **`http://localhost:8000`** in your browser.

---

## 🎨 Customisation

The design system is driven by CSS custom properties defined in `:root` and `[data-theme="light"]`. To rebrand the site, update these tokens:

```css
:root {
  --bg: #0b0f19;
  --surface: #121a2b;
  --text: #e7ebf3;
  --accent: #6d7cff;
  --accent-2: #22d3ee;
  --radius: 16px;
  --max: 1080px;
}
```

- **Colours** — edit `--accent`, `--accent-2`, and surface tokens.
- **Typography** — swap the Google Fonts `<link>` and update `font-family`.
- **Content** — each section is clearly commented in the HTML (`<!-- ================= ABOUT ================= -->`).
- **Assets** — replace `logo.png`, `sekang.webp`, `sekang2.webp`, and the CV PDF in the root directory.

---

## ✅ Certifications

| Credential | Issuer | Date | Grade | Status |
| :--- | :--- | :--- | :--- | :--- |
| Create Your First Python Program From UST | UST · Coursera | Nov 2, 2026 | 100% | ✅ Verified |

---

## 🌐 Browser Support

| Browser | Version |
| :--- | :--- |
| Chrome / Edge | Latest 2 versions |
| Firefox | Latest 2 versions |
| Safari | Latest 2 versions |
| Mobile browsers | iOS Safari, Chrome Android |

---

## 📬 Contact

- **Email:** [sekang.segotso@moov.life](mailto:sekang.segotso@moov.life)
- **Phone:** [+27 61 4548 884](tel:+27614548884)
- **GitHub:** [github.com/sekma-n](https://github.com/sekma-n)
- **LinkedIn:** [linkedin.com/in/sekangsegotso](https://linkedin.com/in/sekangsegotso)
- **Location:** South Africa (UTC+2)

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

You are free to use the structure and design system as inspiration, but please replace the personal content (name, CV, images, and contact details) with your own.

---

<p align="center">
  <sub>Built with plain HTML, CSS &amp; JavaScript · © 2026 Sekang Segotso</sub>
</p>
```

## Why this README works

1. **Instant clarity** — the first screen states who you are, what the project is, and links to the live demo.
2. **Corporate tone** — tables, a consistent section hierarchy, and professional badges give it the feel of a maintained product repository rather than a class assignment.
3. **Scannable** — recruiters and collaborators can find Features, Tech Stack, and Getting Started in seconds.
4. **Accurate to the codebase** — the structure, sections (01–05), certifications, and contact details are pulled directly from your live site and the `Home.html` / `About.html` you shared.
5. **Actionable** — clone commands, customisation tokens, and a browser-support table help anyone who wants to run, fork, or review the project.

## Quick setup steps

1. On GitHub, navigate to your repository: `https://github.com/sekma-n/sekang_Portfolio-website`
2. Click **Add file → Create new file**
3. Name it **`README.md`**
4. Paste the Markdown above
5. Scroll down and click **Commit new file**

The README will automatically render on the repository homepage.
