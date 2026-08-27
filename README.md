# Michael Portale — Portfolio

The source for Michael Portale's personal portfolio website. It is a responsive, single-page site that introduces current work, links to live projects and professional profiles, and includes an in-browser Snake game.

## What is included

- Responsive navigation with mobile menu support
- Dark/light theme preference persisted in local storage
- Scroll-driven navigation state and reveal animations
- Project and contact sections
- Canvas-based Snake game with difficulty selection and keyboard controls

## Stack

Plain HTML, CSS, and JavaScript. Google Fonts and Font Awesome are loaded from CDNs; no application build is required for the main site.

## Run locally

Serve the repository root with any static file server, for example:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Repository layout

```text
index.html       Site structure and content
css/style.css    Responsive styling and themes
js/script.js     Navigation, theme, and animation behavior
js/snake-game.js Canvas-based Snake implementation
```

The `portfolio/` directory is a separate legacy React project retained in this repository; the root static site is the deployed portfolio implementation.
