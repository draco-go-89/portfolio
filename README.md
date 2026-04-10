# Dhrubo Basumatary Portfolio

Personal portfolio website for Dhrubo Basumatary showcasing projects, skills, and contact form.

## Project Overview

- Static website built with HTML, CSS, and JavaScript.
- Responsive layout with mobile menu, scroll effect, smooth anchor navigation.
- Animated skill progress bars using Intersection Observer.
- Contact form validation and user feedback (demo mode; no backend).
- Project showcase cards linking to live demos and GitHub repos.

## Folder Structure
- `index.html`: main page markup
- `styles.css` or embedded CSS in `index.html`: styles
- `js/script.js`: interactive behavior (menu, scroll navbar, smooth scroll, form, skill animation)
- `TODO.md`: improvement ideas / backlog

## Features

- Fixed glass navbar with scroll state class (`.navbar.scrolled`)
- Mobile hamburger toggle and outside-close behavior
- Smooth scrolling for anchors (`#home`, `#about`, `#projects`, `#skills`, `#contact`)
- Animated skill bars when section is visible
- Form submit validation: name, email, message required
- Projects section with cards and external links
- Skills section with progress bars animated from `data-progress`
- Footer with social links (Instagram, Facebook, GitHub, LinkedIn, YouTube)

## Running Locally

1. Clone repository
2. Open `index.html` in browser, or run local server:
   - VS Code Live Server extension
   - `npx http-server` or `python -m http.server`
3. Test responsiveness and interactions.


## To Do

- Add backend/API for form submission
- Replace hardcoded skill percentages with data-driven JSON
- Add project screenshots + deployment status badges
- Add dark mode toggle
- Optimize accessibility (aria, labels, focus states)

## Notes

- `Skills` section ID: `#skills` (line 644)
- JavaScript skill observer in `js/script.js` uses:
  - `document.querySelector('#skills')`
  - `IntersectionObserver`
  - `entry.target.querySelectorAll('.skill-progress')`


## Link    

https://draco-go-89.github.io/portfolio/

## Author

- Dhrubo Basumatary
- GitHub: https://github.com/draco-go-89
- Instagram: https://www.instagram.com/___lubolabao.1___/
