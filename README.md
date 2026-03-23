# WebDev Journal Blog

WebDev Journal Blog is a multi-page personal learning journal built with **HTML, CSS, and JavaScript** as part of the **Scrimba Full‑Stack Web Development Career Path**.
The project documents my journey into frontend development with a strong emphasis on **semantic HTML**, **accessibility (WCAG 2.2)**, and **clean, responsive CSS architecture**.

---

## 🎨 Preview

-------IN PROGRESS----------------

---

## 🛠 Tech Stack

- HTML5 (semantic markup)
- CSS3
  - CSS Grid
  - Responsive typography using `clamp()`
  - Media queries
- Vanilla JavaScript
- Google Fonts (Source Sans 3)

---

## ✨ Features

- Multi‑page layout (Home, Article, About)
- Semantic HTML structure (`header`, `nav`, `main`, `article`, `section`, `footer`)
- Keyboard‑accessible navigation
- Skip link for bypassing repeated navigation (WCAG 2.4.1)
- Semantic date markup using `<time datetime>`
- Responsive layouts with CSS Grid
- Clean, sectioned CSS architecture
- Mobile‑first, progressively enhanced design

---

## 📁 Project Structure

```
.
├── index.html
├── full-article.html
├── about.html
├── css/
│   ├── style.css
│   ├── article.css
│   └── about.css
├── script/
│   └── script.js
├── images/
│   ├── favicon/
│   └── *.jpg / *.png
└── README.md
```

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/webdev-journal-blog.git
```

2. Open `index.html` in your browser.

No build tools, frameworks, or dependencies are required.

---

## ♿ Accessibility

Accessibility is a core focus of this project and is implemented intentionally throughout the codebase.

### Implemented Accessibility Features

- Semantic HTML landmarks for screen readers
- Skip link to bypass repeated navigation (WCAG 2.4.1)
- Keyboard‑accessible navigation and controls
- Valid ARIA usage only where appropriate
- Semantic `<time>` elements with machine‑readable `datetime` attributes
- Clear heading hierarchy

### Skip Link Example

```html
<a href="#main-content" class="skip-link">Skip to main content</a>
```

```css
.skip-link {
  position: absolute;
  top: -40px;
  left: 0;
  background: #000;
  color: #fff;
  padding: 0.5rem 1rem;
  z-index: 1000;
}

.skip-link:focus {
  top: 0;
}
```

---

## 🎯 Learning Goals

This project was built to practice and demonstrate:

- Semantic HTML and accessible markup
- WCAG 2.2 accessibility fundamentals
- CSS Grid for responsive layouts
- Mobile‑first design principles
- Clean and maintainable CSS organization
- Progressive enhancement with JavaScript

---

## ⚠️ Current Limitations

- Content is static
- No dynamic data loading
- JavaScript functionality is minimal

---

## 🚀 Future Improvements

- Enhanced JavaScript interactions
- Improved focus styles and contrast auditing
- Content expansion
- Dark mode support
- Add **View More** functionality for blog posts:
- Display only 6 posts initially
- Load 6 additional posts each time the button is clicked
- Implement a **hamburger navigation menu** for smaller screens:
- Replace the horizontal menu on mobile
- Toggle navigation visibility on click

---

## 👤 Author

Created by **Federico Celia**  
Frontend / Full‑Stack Developer in progress

🔗 LinkedIn: https://www.linkedin.com/in/federico-celia-13b3851a8/

---

## 📄 License

This project is licensed under the  
**Creative Commons Attribution–NonCommercial 4.0 International (CC BY‑NC 4.0)** license.

You are free to:

✔ Use the code  
✔ Modify it  
✔ Share it

…but **only for personal and non‑commercial purposes**.

Commercial use is **not permitted**.

For full legal details, see the official license:  
https://creativecommons.org/licenses/by-nc/4.0/
