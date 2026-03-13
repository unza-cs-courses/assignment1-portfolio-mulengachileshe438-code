[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8NpkA7e4)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23118387&assignment_repo_type=AssignmentRepo)
# Assignment 1: Responsive Portfolio Website

**Course:** CSC4035 Web Programming and Technologies
**Weight:** 5% of final grade
**Due:** Week 6, Friday 11:59 PM

---

## Overview

Create a professional, responsive portfolio website showcasing your skills, projects, and contact information. This assignment assesses your HTML5 and CSS3 skills, including semantic markup, modern layout techniques (Flexbox/Grid), and responsive design principles.

**Important:** No CSS frameworks (Bootstrap, Tailwind, etc.) are allowed. All CSS must be hand-written.

---

## Requirements

### Functional Requirements

Your portfolio must include **4 or more sections**:

| Section | Required Content |
|---------|------------------|
| **Home/Hero** | Your name, tagline, and call-to-action button |
| **About** | Professional bio (150+ words), profile image, skills list |
| **Projects** | Minimum 3 project cards with title, description, image, and links |
| **Contact** | Contact form with validation attributes (name, email, message) |

### Technical Requirements

| Requirement | Description |
|-------------|-------------|
| **HTML5** | Valid semantic HTML (header, nav, main, section, article, footer) |
| **CSS3** | External stylesheet only (no inline styles) |
| **CSS Variables** | Use custom properties for colors and spacing |
| **Flexbox** | Use for at least one layout component |
| **CSS Grid** | Use for at least one layout component |
| **Responsive** | Mobile-first with minimum 3 breakpoints |
| **Accessibility** | Alt text, form labels, color contrast, heading hierarchy |

### Breakpoints Required

```css
/* Mobile-first base styles */

/* Tablet (768px and up) */
@media (min-width: 768px) { }

/* Desktop (1024px and up) */
@media (min-width: 1024px) { }

/* Large Desktop (1200px and up) - optional */
@media (min-width: 1200px) { }
```

---

## Project Structure

```
csc4035-assignment1-portfolio/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # Main stylesheet
├── images/             # Your images (profile, projects, etc.)
├── screenshots/        # Screenshots at different breakpoints
│   ├── mobile.png
│   ├── tablet.png
│   └── desktop.png
└── README.md           # This file (update with your info)
```

---

## Getting Started

1. **Clone this repository** to your local machine
2. **Open `index.html`** in your code editor
3. **Complete the TODO comments** in each file
4. **Test responsiveness** using browser developer tools
5. **Take screenshots** at mobile, tablet, and desktop sizes
6. **Commit and push** your changes regularly

---

## Grading Rubric (100 points)

| Criterion | Points | Description |
|-----------|--------|-------------|
| **HTML Structure & Semantics** | 20 | Valid HTML5, semantic elements, proper document structure |
| **CSS Styling & Design** | 20 | Professional design, cohesive color scheme, typography |
| **Flexbox & Grid Usage** | 20 | Both techniques used appropriately and effectively |
| **Responsive Design** | 20 | Mobile-first, 3+ breakpoints, no horizontal scrolling |
| **Content & Completeness** | 10 | All sections complete with quality content |
| **Code Quality** | 10 | Clean, organized, well-commented code |

### Automated Tests (40% of grade)

The following are checked automatically on each push:
- HTML validation (no errors)
- Required HTML elements present
- CSS file linked correctly
- Required sections exist
- Responsive meta tag present

---

## Submission Checklist

Before submitting, verify:

- [ ] All 4 sections are complete (Home, About, Projects, Contact)
- [ ] HTML validates with no errors
- [ ] CSS uses custom properties (variables)
- [ ] Flexbox is used for at least one component
- [ ] CSS Grid is used for at least one component
- [ ] Site is responsive at all breakpoints
- [ ] All images have alt text
- [ ] Form inputs have labels
- [ ] Screenshots added to `/screenshots` folder
- [ ] README updated with your information

---

## Your Information

**Name:** Chilesh Mulenga
**Student ID:** 2022039904
**Design Theme:** Modern, clean professional design with blue primary colors and responsive layout featuring Flexbox, CSS Grid, dark mode toggle, and mobile hamburger menu navigation

### Features Implemented
- [x] CSS Custom Properties (light and dark mode color schemes)
- [x] Flexbox (navigation and form layouts)
- [x] CSS Grid (project cards with responsive columns)
- [x] Media Queries (mobile-first with 4 breakpoints)
- [x] Dark/Light Mode Toggle (with localStorage persistence)
- [x] Responsive Hamburger Menu (with smooth animations)
- [x] Smooth Scrolling & Transitions
- [x] Semantic HTML5 Elements
- [x] Form Validation & Accessibility

### CSS Techniques Used
- [x] CSS Custom Properties (--color-*, --spacing-*, --font-*)
- [x] Flexbox (navigation, footer, form layouts)
- [x] CSS Grid (project cards: 1 col mobile → 2 col tablet → 3 col desktop)
- [x] Media Queries (mobile < 768px, tablet ≥ 768px, desktop ≥ 1024px, large ≥ 1200px)
- [x] Dark Mode with CSS Variables
- [x] Smooth Transitions & Animations
- [x] Hamburger Menu Toggle (CSS + JavaScript)
- [x] Box Shadows & Color Gradients
- [x] Pseudo-elements (::after for underline effects)

### Sections Completed
1. **Hero Section** - Full name, professional tagline, call-to-action button
2. **About Section** - Professional bio (150+ words), profile image, 8 skills displayed as badges
3. **Projects Section** - 3 project cards with titles, descriptions, and action links (images removed for clean layout)
4. **Contact Section** - Contact form with name, email, subject, message fields and validation
5. **Navigation** - Sticky header with logo, responsive menu, and dark mode toggle
6. **Footer** - Copyright notice and social media links

### Bonus Features (+5% Extra)
- **Dark/Light Mode Toggle** (+3%) - Full dark mode implementation with localStorage persistence
- **Responsive Hamburger Menu** (+2%) - Mobile-friendly navigation with smooth animations

### Challenges & Solutions
Built a fully responsive portfolio website using modern CSS techniques without frameworks. Implemented a mobile-first approach with 4 responsive breakpoints. Used CSS Grid for project cards with responsive column layouts (1→2→3 columns) and Flexbox for navigation and form layouts. Added dark mode functionality using CSS custom properties that can be toggled via JavaScript and persisted in localStorage. Created an animated hamburger menu for mobile navigation that appears only on screens below 768px. Ensured all sections are accessible with proper heading hierarchy, form labels, and ARIA attributes. Removed project card images to maintain a clean, text-focused design.

### Credits
- System font stack using -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto
- Custom color scheme designed for professional appearance with light and dark modes
- No external frameworks or libraries used (vanilla JavaScript for interactions)

---

## Academic Integrity

- All code must be your own work
- No CSS frameworks or libraries allowed
- Images must be royalty-free or your own (credit sources)
- Plagiarism detection tools will be used

**Violations result in zero marks and academic misconduct reporting.**

---

## Extension Opportunities (Bonus: up to +10%)

- Dark/light mode toggle with CSS (+3%)
- CSS animations/transitions (+3%)
- CSS-only hamburger menu (+2%)
- Print stylesheet (+2%)
