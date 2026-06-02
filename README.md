# Vedant Patil - Personal Student Portfolio

A modern, highly responsive, and visually striking dark-themed personal portfolio website built by **Vedant Patil**, a Class 10 student, STEM competitor, and aspiring IIT/AI Architect from Parbhani, India.

The site showcases academic achievements, science competitions, deep-tech skills, and future aspirations with a futuristic, sci-fi-inspired aesthetic.

---

## 🚀 Features

* **Futuristic Glassmorphic Design:** A deep purple/dark theme augmented with grid overlays, vibrant glowing radial gradients, and elegant glassmorphism (`backdrop-filter`).
* **Dynamic Intersection Observer Features:**
* **Scroll-Driven Animations:** Elements elegantly slide and fade into view (`.reveal`) as the user scrolls down.
* **Smart Navigation:** The header links dynamically update their active state highlighted line based on the visible viewport section.
* **Contextual Sticky Indicators:** A "Scroll Down" indicator appears exclusively on the hero section and transforms smoothly into a "Back to Top" action pill once the user scrolls past the fold.


* **Fully Responsive Layouts:** Optimized for all screen thresholds (Desktops, Tablets, and Mobile phones) using modern CSS Grid, Flexbox, and fluid typography via `clamp()`.
* **Accessibility & Performance Focused:**
* Semantic HTML5 tags (`<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`) with appropriate `aria` labels.
* Respects system accessibility preferences by completely disabling animations if `prefers-reduced-motion` is active.
* Pre-configured progressive enhancement via a lightweight `.js` class injection script to handle disabled JavaScript fallbacks safely.



---

## 📂 Repository Structure

```text
├── assets/
│   ├── favicon.svg          # Custom VP brand mark favicon
│   ├── trophy.svg           # Pixelated trophy icon for achievements
│   └── vedant-hero.svg      # Abstract STEM/AI custom vector hero illustration
├── index.html               # Semantic structural markup & dynamic component scripts
├── styles.css               # Architecture styles, custom properties, & media queries
└── README.md                # Project documentation

```

---

## 🛠️ Technical Stack

* **Markup:** HTML5 (Semantic, SEO friendly)
* **Styling:** Vanilla CSS3 (Custom Variables, Advanced Gradients, Grid/Flexbox)
* **Interactivity:** Vanilla JavaScript (ES6+, Intersection Observer API)
* **Typography:** Google Fonts (*Inter* for readable body text, *Poppins* for bold geometric headings)

---

## 🧩 Key CSS Custom Properties (Variables)

The site utilizes centralized custom properties in `:root` for effortless theme management:

| Variable | Value | Description |
| --- | --- | --- |
| `--card` | `rgba(14, 7, 24, 0.65)` | Translucent dark background for component cards |
| `--text` | `#fdfaff` | Primary crisp off-white text color |
| `--muted` | `#bda6df` | Subtle lavender-gray text color for body paragraphs |
| `--line` | `rgba(185, 132, 255, 0.14)` | Elegant translucent border neon accents |
| `--purple` to `--violet` | Linear Gradient | Main brand actions and brand-mark accents |

---

## ⚡ Deployment & Local Development

Because this project is written completely in static vanilla languages, it doesn't require compiling, bundling, or a local server setup to view or deploy.

### Local Preview

1. Clone or download this repository to your machine.
2. Double-click the `index.html` file to open it instantly in any modern web browser.

---

## 📝 License

This project is open-source. Feel free to use, modify, or adapt the design and architecture for your personal portfolios.
