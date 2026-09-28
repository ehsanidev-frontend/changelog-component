# 🧩 Changelog Component

A responsive, single-component website built as part of the 
[roadmap.sh](https://roadmap.sh/projects/changelog-component) project series.

This project is a **standalone component** focused on mastering **CSS layout 
and positioning** techniques using pure HTML and CSS.

---

## 📋 Project Overview

This project creates a **visually appealing and responsive changelog component** 
that can be easily integrated into any website.

The goal is to practice:
- **CSS Positioning** with `position: absolute` and `position: relative`
- **Flexbox** for vertical alignment and item layouts
- **Pseudo-elements** (`::before`) for creating the vertical timeline line
- **Media queries** for mobile-first responsive behavior
- **Box model** and modern CSS techniques
- **Typography** and color schemes

The component displays a timeline of project updates with dates, 
dots, and titles, plus a call-to-action button.

---

## 🎯 Goals & Requirements

Based on the original [project requirements](https://roadmap.sh/projects/changelog-component):

- [x] Fully styled, responsive changelog component
- [x] Simple HTML structure with semantic tags
- [x] Visual timeline with vertical line and dots
- [x] Date and title alignment for each entry
- [x] Call-to-action button
- [x] Use of Flexbox and absolute positioning
- [x] Responsive design for mobile screens
- [x] Well-structured and customizable component
- [ ] Host on GitHub Pages or Cloudflare Pages (bonus)
- [ ] Add hover animations to timeline items (bonus)

---

## 📁 Project Structure

```
Changelog-Component/
│
├── index.html              # Main HTML file
├── style.css               # Main stylesheet
└── README.md               # Project documentation
```

---

## 🎨 Design System

### Typography
- **Headings:** Georgia / Times New Roman (serif)
- **Body:** Inherited serif font
- **Fluid sizing** for the main title (`2.5rem`)

### Color Scheme
| Token | Value | Usage |
|-------|-------|-------|
| Background | `#f9f9f9` | Page background |
| Card | `#ffffff` | Changelog card background |
| Border | `#1a1717` | Card border, timeline line, dots |
| Text (main) | `#333333` | Body text and titles |
| Text (muted) | `#888888` | Dates and subtitles |
| Button BG | `#333333` | Primary button background |
| Button Hover | `#555555` | Button hover state |

### Responsive Breakpoint
- **Mobile:** `max-width: 600px` — timeline shifts left, dates stack above titles

---

## 📄 Component Description

| Section | Description | Status |
|---------|-------------|--------|
| **Header** | Title "Changelog" + subtitle | ✅ Done |
| **Timeline** | Vertical line with 7 dated entries | ✅ Done |
| **Dots** | Absolute-positioned circles on the line | ✅ Done |
| **Button** | "Visit Complete Changelog" CTA | ✅ Done |
| **Responsive** | Mobile-friendly layout | ✅ Done |

---

**Techniques used:** Flexbox for card and timeline layouts, `position: absolute` 
for dots and vertical line, `::before` pseudo-element for the timeline line, 
CSS custom properties for consistent colors.

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/ehsanidev-frontend/Changelog-Component.git
```

2. Navigate to the project folder:

```bash
cd Changelog-Component
```

3. Open `index.html` in your browser:

```bash
# On macOS
open index.html

# On Windows
start index.html

# Or use a local server (recommended)
npx serve .
```

No build step or dependencies required. ✅

---

## 🛠️ Built With

- **HTML5** — Semantic markup
- **CSS3** — Flexbox, absolute positioning, pseudo-elements, media queries
- **CSS Variables** — For consistent theming
- **Modern CSS Reset** — `box-sizing: border-box` and margin/padding reset

---

## ⚠️ Known Issues & TODO

The following improvements are planned for future iterations:

### 🔴 High Priority

- [ ] **Add SEO meta tags** (`description`, Open Graph) to `index.html`
- [ ] **Test on all major browsers** (Chrome, Firefox, Safari, Edge)
- [ ] **Validate HTML** with [W3C Validator](https://validator.w3.org)
- [ ] **Validate CSS** with [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

### 🟠 Medium Priority

- [ ] **Add `aria-label`** to the timeline for screen readers
- [ ] **Add `type="button"`** to the CTA button for semantic correctness
- [ ] **Use `<time>` element** for dates instead of `<span>`
- [ ] **Improve mobile breakpoint** — test on smaller screens (320px)
- [ ] **Add smooth hover transitions** to timeline items
- [ ] **Replace `<div>` timeline with `<ol>`** semantic list

### 🟡 Low Priority

- [ ] **Add dark mode** support via `prefers-color-scheme`
- [ ] **Add subtle animations** on page load
- [ ] **Extract design tokens** into CSS custom properties
- [ ] **Host on GitHub Pages** or Cloudflare Pages (bonus)

### 🧪 Validation

- [ ] **Validate HTML** and fix reported errors
- [ ] **Validate CSS** and fix reported warnings
- [ ] **Check accessibility** with Lighthouse

---

## 📚 Reference

- **Project Source:** [roadmap.sh — Changelog Component](https://roadmap.sh/projects/changelog-component)
- **Author:** [@ehsanidev-frontend](https://github.com/ehsanidev-frontend)
- **Inspiration:** [roadmap.sh Changelog Page](https://roadmap.sh/changelog)

---

## 🗺️ Roadmap Progress

This project is part of my learning journey on [roadmap.sh](https://roadmap.sh):

- [x] **Basic HTML Website** — HTML structure
- [x] **Personal Portfolio** — CSS styling
- [x] **Changelog Component** ← *you are here* (Positioning & layout)
- [ ] Responsive Design (advanced)
- [ ] CSS Grid & Animations
- [ ] JavaScript Basics

---

## 📝 License

This project is open-source and available for learning purposes.

---

## 🙌 Acknowledgments

- [roadmap.sh](https://roadmap.sh) for providing the project guidelines
- The open-source community for inspiration and feedback
- Everyone who reviewed the initial CSS layout issues

---

⭐ If you found this project helpful, feel free to give it a star!