# Mona Pouresmaeil — Portfolio

A personal portfolio website showcasing Machine Learning, Data Science, and Software Engineering projects, education, skills, CV, and contact details. Built as a fast, responsive static site and deployed to GitHub Pages.

## Overview
- Responsive single-page site with smooth navigation and section reveals
- Highlights featured projects with links to source code
- Includes downloadable and embedded CV
- Mobile-friendly navigation with a hamburger menu
- Deployed at: https://monaii.github.io/My_Portfolio/

## How It’s Built
- Tech stack: HTML5, CSS3, JavaScript (no frameworks)
- Fonts & Icons: Google Fonts (`Inter`), Font Awesome
- Responsive design: CSS media queries for `768px` and `480px` breakpoints
- Interactivity: Smooth scrolling, mobile menu toggle, intersection observer animations

## Folder Structure
```
My_Portfolio/
├── cv/                     # CV files (PDF)
├── images/                 # Images and assets
├── index.html              # Main page markup
├── styles.css              # Global styles and responsive rules
└── script.js               # Navigation, scrolling, and section reveal logic
```

## How to Run Locally
Prerequisites: `python3` installed (for a simple local server)

1. Clone the repository
   ```bash
   git clone https://github.com/monaii/My_Portfolio.git
   cd My_Portfolio
   ```
2. Start a local server
   ```bash
   python3 -m http.server 8000
   ```
3. Open in your browser: `http://localhost:8000/`

Alternative: open `index.html` directly in a browser (a local server is recommended).

## Deployment (GitHub Pages)
- Push changes to the `main` branch
- GitHub Pages serves the site at: `https://monaii.github.io/My_Portfolio/`
- To (re)enable Pages: Repository → Settings → Pages → Source: `main` / `/root`

## Updating Content
- Projects: Edit links and descriptions in `index.html` under the Projects section
- CV: Place new PDF in `cv/` and update the CV links/iframe in `index.html`
- Social links: Update hero and contact sections in `index.html`
- Styles/behavior: Edit `styles.css` and `script.js`

## Features
- Mobile-friendly layout and touch-friendly buttons
- Animated section reveals on scroll
- Smooth anchor navigation with offset for fixed navbar
- External links open in new tabs

## Contact
- Email: `mona.pouresmaeil@studenti.polito.it`
- LinkedIn: `https://linkedin.com/in/mona-pouresmaeil-8b04a82b4/`
- GitHub: `https://github.com/monaii`
- Kaggle: `https://kaggle.com/monapouresmaeil`