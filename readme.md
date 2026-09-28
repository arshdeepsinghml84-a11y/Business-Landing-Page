# NovaTech Solutions – Business Website

A modern, responsive, single-page marketing website for a fictional digital agency called **NovaTech Solutions**. It presents the company's services, portfolio, pricing, testimonials, FAQ and contact details in one smooth-scrolling page.

## Description

This project is a landing page / website template for a digital services company (web development, app development, digital marketing, SEO, cloud solutions and business consulting).

- **What it does:** Presents a business's services and lets visitors explore work, pricing and contact options.
- **Who it's useful for:** Small businesses, agencies and freelancers who want a clean landing-page design, and beginners learning HTML, CSS and JavaScript.
- **What problem it solves:** Gives a ready-made, professional single-page layout that can be customised with your own content.

## Features

- Sticky navigation bar that changes style on scroll
- Active menu link highlighting based on the section you are viewing
- Mobile-friendly hamburger menu
- Hero section with animated background shapes and an SVG illustration
- Client logos strip
- About section with mission and vision cards
- Services grid (6 services) with hover effects
- "Why Choose Us" section
- Animated number counters that start when scrolled into view
- Portfolio grid with hover overlays
- Testimonial slider with previous/next buttons, dots and auto-play
- Pricing plans (Starter, Professional, Enterprise)
- FAQ accordion
- Contact form with client-side validation (name, email, phone, message)
- Newsletter sign-up form with email validation
- Scroll-reveal animations and a back-to-top button
- Fully responsive layout (desktop, tablet, mobile)
- SEO meta tags and Open Graph tags
- Accessibility basics: ARIA labels, focus styles, and reduced-motion support

> **Note:** The contact and newsletter forms only validate input and show a success message in the browser. They do not send data anywhere yet.

## Technologies Used

- HTML5
- CSS3 (CSS variables, Flexbox, Grid, animations, media queries)
- Vanilla JavaScript (no frameworks) using `IntersectionObserver`
- [Google Fonts](https://fonts.google.com/) – Poppins
- Inline SVG icons and illustrations

## Project Structure

```text
project-folder/
├── index.html      # Page content, styles and scripts (all in one file)
├── README.md
└── .gitignore
```

## How to Run

No installation or build step is needed.

**Option 1 – Open directly**
1. Download or clone this project.
2. Double-click `index.html` to open it in your browser.

**Option 2 – VS Code Live Server (recommended)**
1. Open the project folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click `index.html` and choose **Open with Live Server**.

An internet connection is needed the first time so the Poppins font can load from Google Fonts.

## Usage

- Use the top navigation (or the **Get Started** button) to jump between sections.
- Browse the services, portfolio, pricing and FAQ.
- Use the arrows or dots to move through testimonials.
- Fill in the contact form to see the validation and success message.

To customise it, open `index.html` and edit the text, colours (in the `:root` CSS variables at the top) and contact details.

## Screenshots

_Screenshots not added yet._

## Live Demo

Live Demo: Not deployed yet

## Future Improvements

- Connect the contact and newsletter forms to a real service (for example Formspree, EmailJS or a backend)
- Add real project images to the portfolio section
- Move the CSS and JavaScript into separate `style.css` and `script.js` files
- Add a dark mode
- Add individual pages for services and portfolio projects
- Replace placeholder company details with real ones

## Author

Created by Arshdeep Singh