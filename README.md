
# 🌐 Group Showcase Website

A multi-page static website built using only HTML and CSS. This project presents individual group members, their roles, and work samples in a clean and responsive design.

---

## 📌 Overview

This is a static website created by our team to showcase each our group. It contains multiple linked pages with personalized content (photos, bios, links), all styled consistently using CSS. There is **no Frameworks** — all interaction is limited to HTML and CSS and basic js capabilities (e.g. hover effects, layout, navigation, animations).

---

## 🧱 Tech Stack

- **HTML5**
- **CSS3**
- Responsive layout (media queries, flexbox/grid)
- No frameworks, no JS

---

## 📁 Project Structure

```bash
project-root/
│   404.html                           # "Not Found" page
│   index.html                         # Home page with group mambers and overal info
│   README.md                          # This documentation file
│
├───css
│       home-page-styles.css           # Home page styles
│       student-page-styles.css        # Student bio page styles
│       styles.css                     # Global styles for every page
│
├───img                                # Folder with website images
│   └───students                       # Folder with student's bio pictures
│
└───students                           # Folder with student's bio pages
        anton.html                     # Anton's bio page
```

---

## 📄 Pages

| Page         | Purpose                        |
| ------------ | ------------------------------ |
| `index.html` | Homepage — team overview       |
| `404.html`   | "Not Found" page               |
| `anton.html` | Anton profile and portfolio    |

Each profile page includes:

* Avatar
* Short biography
* Carrousel of photos

---

## 🎨 Design Notes

* All pages have a same styles and layout
* Styling features:
  * Flexbox for layout
  * CSS hover effects on links/images/buttons

---

## 🧪 How to Run

No setup required — just open `index.html` in any browser:

```bash
# Optional: Open with VS Code Live Server
npx live-server
```

Or double-click `index.html` locally.

---

## 🧹 Style Guidelines

* Class names use `kebab-case` (e.g. `team-card`, `profile-header`)
* Keep consistent indentation (2 or 4 spaces)
* Responsive rules placed at the bottom of the stylesheet

---

## 👥 Team Members

| Name  | Role         | Page         |
| ----- | ------------ | ------------ |
| Anton | HTML layout  | `anton.html` |
| Kolya | HTML layout  | `None`       |
| Illya | Styling / QA | `None`       |
| Vika  | Styling / QA | `None`       |

---

## 📝 Notes

This project was created to simulate a professional team portfolio site. It is built with clean, readable, and maintainable code and is ready for hosting (e.g., GitHub Pages, Netlify).
