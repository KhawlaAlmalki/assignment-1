# Technical Documentation

## 1. Project Overview
This project is a **personal portfolio website** built as part of Assignment 1.  
The goal was to create a simple, responsive web application showcasing personal details, projects, and contact options while practicing **HTML, CSS, and JavaScript** fundamentals and integrating AI-assisted development tools.

---

## 2. Repository Structure
assignment-1/
├── README.md # Project description & setup instructions
├── index.html # Main entry point (HTML structure)
├── css/
│ └── styles.css # Styling (layout, colors, responsiveness)
├── js/
│ └── script.js # JavaScript for interactivity
├── assets/
│ └── images/ # Profile picture and project placeholders
├── docs/
│ ├── ai-usage-report.md # Report on AI usage (tools, benefits, outcomes)
│ └── technical-documentation.md # Technical details (this file)
└── .gitignore # Ignore unnecessary files

---

## 3. Technologies Used
- **HTML5** → Semantic structure of the site.
- **CSS3** → Styling, responsive layouts (Flexbox/Grid).
- **JavaScript (ES6)** → Client-side interactivity (theme toggle, scroll reveal, form handling).
- **AI Tools** → ChatGPT for code explanation, debugging, and documentation support.

---

## 4. Features Implemented
### ✅ Core Sections
1. **About Me** – Introduction, tagline, and profile image.
2. **Projects** – At least two projects with titles, descriptions, and placeholder images.
3. **Contact** – A form with Name, Email, and Message fields (front-end only).

### ✅ Extra Sections
- **Experience & Education**
- **Skills & Expertise**
- **Awards & Recognition**

### ✅ Interactivity
- **Dark/Light Theme Toggle** – Persists using `localStorage`.
- **Scroll Reveal Animation** – Elements fade in when entering the viewport.
- **Contact Form Feedback** – Displays confirmation/error messages (no backend required).

### ✅ Responsive Design
- Layout tested on **desktop, tablet, and mobile** using CSS Flexbox/Grid.
- Images are responsive (`object-fit: cover`, percentage-based sizing).

---

## 5. Implementation Details
- **Dark Mode**:
    - Toggle button updates the `<html>` element with a `.dark` class.
    - State is stored in `localStorage` so the user’s preference persists.

- **Scroll Reveal**:
    - Implemented with `IntersectionObserver`.
    - Adds an `in` class to `.reveal` elements when they become visible.

- **Contact Form**:
    - Uses native HTML5 validation.
    - JavaScript provides simple feedback text under the form (`#msg`).

---

## 6. Code Quality & Standards
- Clean and consistent indentation.
- Comments added for clarity in HTML, CSS, and JavaScript.
- No unused code or broken links.
- Semantic HTML tags used for accessibility.

---

## 7. Testing & Compatibility
- **Browsers tested**: Chrome, Edge.
- **Responsive testing**: DevTools for mobile, tablet, and desktop.
- **Performance**: Lightweight design with minimal external dependencies.

---

## 8. Future Improvements
- Add backend support for contact form (e.g., Node.js or Firebase).
- Replace placeholder project images with real screenshots.
- Enhance animations with smoother transitions.
- Add deployment pipeline (Netlify or GitHub Pages).

---

## 9. Conclusion
This project demonstrates the foundation of a professional portfolio website by combining **front-end development skills, responsive design, interactivity, and responsible AI integration**. It provides a base that can be expanded in future assignments into a fully developed professional portfolio.

