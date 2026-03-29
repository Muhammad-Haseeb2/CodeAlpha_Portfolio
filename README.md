# 🌐 Personal Portfolio Site | CodeAlpha Frontend Internship | Task 3

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Task](https://img.shields.io/badge/Task-3%20of%204-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![CodeAlpha](https://img.shields.io/badge/Internship-CodeAlpha-purple)

A **complete personal portfolio website** built with pure HTML, CSS, and vanilla JavaScript. Features a warm editorial aesthetic with a custom cursor, smooth scroll-reveal animations, animated skill bars, a 6-project showcase, and a fully functional contact form — all in one responsive single-page file.

---

## 📸 Preview

```
┌──────────────────────────────────────────────────────────┐
│  M. Bilal    About · Projects · Skills · Contact  [Hire] │
├──────────────────────────────────────────────────────────┤
│                                                          │
│  Muhammad           ┌──────────────────┐                │
│  Bilal        ← →   │  Profile Photo   │                │
│  ─────────          │                  │                │
│  Python Developer   │  [Python·Front.] │                │
│  & Frontend Eng.    └──────────────────┘                │
│  [View Projects]  [Get in Touch]                        │
│                                                          │
├──────────────────────────────────────────────────────────┤
│   2+          12+          8          ∞                  │
│  Years       Projects    Tasks     Lines of Code         │
├──────────────────────────────────────────────────────────┤
│  ABOUT  ·  PROJECTS  ·  SKILLS  ·  CONTACT             │
└──────────────────────────────────────────────────────────┘
```

---

## ✨ Features

### Layout & Navigation
- 🔝 **Sticky navbar** with glass-morphism blur effect
- 🔗 **Smooth scroll** navigation to all sections
- 📱 **Fully responsive** — collapses gracefully on mobile and tablet

### Visual & Animation
- 🖱️ **Custom cursor** — a dot + ring that scales up on hover over links and buttons
- 🎞️ **Scroll-reveal animations** — every section fades and slides up using IntersectionObserver
- 📊 **Animated skill bars** — fill with eased animation when scrolled into view
- 🖼️ **Hero image frame** — offset border decoration with an italic tag label
- 🌅 **Alternating section backgrounds** — light/dark sections for visual rhythm

### Sections
| Section | Content |
|---|---|
| 🏠 Hero | Name, tagline, profile photo, CTA buttons |
| 📊 Stats | Years coding, projects built, tasks, lines of code |
| 👤 About | Bio, skills tag cloud, experience / education timeline |
| 💼 Projects | 6 project cards with thumbnail, tags, description, links |
| 📈 Skills | Python, JS, HTML/CSS, Flask, Git — animated progress bars |
| 📬 Contact | Info links (email, GitHub, LinkedIn) + message form with success state |
| 🔻 Footer | Copyright, tech credits, back-to-top link |

### Bonus
- ✅ **Contact form** with JavaScript validation and animated success state
- ♿ **Semantic HTML** — proper heading hierarchy and landmark elements
- 🌍 **Deployable** to GitHub Pages or Netlify as-is (single `.html` file)

---

## 🧠 Concepts Used

| Concept | Usage |
|---|---|
| CSS Grid & Flexbox | Page layout, nav, project grid, stats row, contact grid |
| CSS custom properties | Consistent colour and typography system |
| CSS `@keyframes` | Scroll-reveal, skill bar fill, cursor interactions |
| `position: sticky` + `backdrop-filter` | Navbar that stays visible and blurs content behind it |
| `IntersectionObserver` API | Triggering animations exactly when elements enter the viewport |
| CSS `::before` pseudo-element | Hero image decorative offset border frame |
| JavaScript DOM events | Cursor tracking, form submission, smooth interactions |
| CSS `transition` | Hover states on cards, links, buttons, skill tags |
| Responsive `clamp()` | Fluid font sizes for headings across all screen sizes |
| `object-fit: cover` | Consistent image cropping in project cards |

---

## 📁 Project Structure

```
CodeAlpha_Portfolio/
│
├── task3_portfolio.html    # Complete single-file portfolio (HTML + CSS + JS)
└── README.md               # Project documentation
```

---

## 🚀 How to Run

### Prerequisites
- Any modern web browser (Chrome, Firefox, Edge, Safari)
- No installations, no build tools, no dependencies

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/Muhammad-Haseeb2/CodeAlpha_Portfolio.git

# 2. Navigate into the folder
cd CodeAlpha_Portfolio

# 3. Open directly in your browser
# Double-click task3_portfolio.html
# OR open with Live Server in VS Code for hot reload
```

### Deploy to GitHub Pages (Bonus)

```bash
# 1. Push to GitHub
git add . && git commit -m "Add portfolio site" && git push

# 2. Go to Repository → Settings → Pages
# 3. Source: Deploy from branch → main → / (root)
# 4. Your site will be live at:
#    https://YOUR_USERNAME.github.io/CodeAlpha_Portfolio/task3_portfolio.html
```

---

## ✏️ Personalisation Guide

Before uploading, update these placeholders in `task3_portfolio.html`:

| Placeholder | Replace With |
|---|---|
| `Muhammad Haseeb` | Your full name |
| `Muhammad-Haseeb2` | Your GitHub username |
| `muhammad-haseeb-hsb` | Your LinkedIn profile URL slug |
| `itxhaseeb@gmail.com` | Your email address |
| `Islamabad, Capital, Pakistan` | Your city/country |
| Profile photo `src` | Your actual photo URL or local path |
| Project card links | Your real GitHub repo and live demo URLs |
| Stats numbers | Your actual stats |

---

## 🎨 Design Decisions

- **Aesthetic**: Warm editorial — inspired by literary magazines and upscale editorial design
- **Typography**: Playfair Display (headings, serif) + DM Sans (body) + DM Mono (labels)
- **Color palette**: Warm parchment background (#faf8f3) with burnt sienna accent (#c8502a) and ink dark (#111)
- **Dark sections**: About and Contact use near-black (#111) with warm cream accents for drama
- **Custom cursor**: Reinforces the refined, designed feel of the site

---

## 📱 Responsive Behaviour

| Screen | Changes |
|---|---|
| Desktop (>900px) | Full two-column layouts, hero photo visible, full nav |
| Tablet (600–900px) | Single-column sections, hero photo hidden |
| Mobile (<600px) | Stacked form fields, compact padding, minimal nav |

---

## 👤 Author

**Muhammad Haseeb** — CodeAlpha Frontend Development Intern

- 🌐 GitHub: [github.com/Muhammad-Haseeb2](https://github.com/Muhammad-Haseeb2)
- 💼 LinkedIn: [linkedin.com/in/muhammad-haseeb-hsb](https://linkedin.com/in/muhammad-haseeb-hsb)

---

## 🏢 About CodeAlpha

[CodeAlpha](https://www.codealpha.tech) is a leading software development company offering hands-on internship programs in Python, Web Development, AI, and more.

---

## 📄 License

This project is developed as part of the **CodeAlpha Frontend Development Internship**.
Free to use for educational purposes.
