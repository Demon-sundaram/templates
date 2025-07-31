# BrewMaster Café Website

A modern, responsive café web template built with HTML, CSS, and vanilla JavaScript. Designed for a smooth user experience, showcasing an engaging hero section, menu display, about & contact sections, interactive navigation, and order simulation.

---

## Features

- **Responsive Design:** Looks great on all devices (mobile, tablet, desktop).
- **Animated Hero Section:** Eye-catching background with text and a call-to-action.
- **Sticky Navigation Bar:** Smooth color transition on scroll, with adaptive desktop/mobile menus.
- **Interactive Menu:** Menu cards with hover animation and simulated "Add to order" buttons.
- **About Section:** Details about the café, animated stats, and a featured image badge.
- **Contact Form:** Styled contact form with validation and simulated submission.
- **Social Media Links:** Interactive icons for major platforms (Facebook, Twitter, LinkedIn).
- **Simple Animations:** Fade-in effects for menu cards, stats, and contact info as you scroll.
- **Accessible & User-Friendly.**

---

## File Structure

/
├── index.html # Main HTML file with all sections
├── styles.css # Main CSS file using custom properties and media queries
└── script.js # JavaScript for all interactivity (menu toggle, animations, form, etc.)


---

## Quick Start

1. **Clone or Download the Repository.**
2. **Open `index.html` in your browser.**
3. No dependencies are required! All CSS and JavaScript are included via local files.

---

## Usage Highlights

### Navigation

- **Desktop:** Horizontal menu; links scroll smoothly to page sections.
- **Mobile:** Hamburger menu toggles a vertical slide-out menu.

### Animations

- Sections fade in on scroll (using IntersectionObserver via JS).
- Buttons and cards gently animate on hover.

### Order Simulation

- Clicking any "Order" button in the menu section triggers an alert (demo of e-commerce interaction).

### Contact Form

- Simple form validation (fields not empty).
- On submission, a thank you alert is displayed and the form resets.

---

## How It Works

### HTML (`index.html`)

Organizes the site's content into semantically structured sections: Navbar, Hero, About, Menu, Contact, and Footer.

### CSS (`styles.css`)

Implements a clean, modern style using system fonts, custom colors, flexible layouts (Grid, Flexbox), media queries for responsive design, and smooth section animations.

### JavaScript (`script.js`)

Handles navigation effects (scroll color, menu toggling), smooth anchor scrolling, form validation, demo ordering, interactive social icons, and fade-in animation of elements as they enter the viewport.

---

## Customization

- **Images:** Replace demo image URLs in `.hero-bg` and `.about-image` for your own photos.
- **Menu:** Edit menu items in the HTML to suit your real product list.
- **Colors & Fonts:** Adjust in the CSS file as needed.

---

## Accessibility & Cross-Browser Notes

- Uses semantic HTML for structure.
- Smooth scrolling polyfilled for older browsers.
- All essential features work without JavaScript (except interactive extras).

---

## Credits

- Background photography: Pexels (replace with your own as desired).
- Designed & developed for demonstration purposes.

---

**Enjoy your modern café template!**

*BrewMaster Café – Crafted with passion, served with love.*
