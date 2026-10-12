# Coffee Landing Template

A clean, responsive coffee shop landing page template built with **Tailwind CSS (CLI workflow)**.

## Live Demo
https://coffee-template-rho.vercel.app/

## Screenshots

<img src="./screenshots/coffee-cover.png" width="100%" />
<img src="./screenshots/coffee-2.png" width="100%" />
<p>
  <img src="./screenshots/coffee-mobile-1.png" width="49%" />
  <img src="./screenshots/coffee-mobile-2.png" width="49%" />
</p>


## Features
- Responsive layout
- Reusable landing sections (Hero / Features / Menu / CTA)
- Tailwind-based styling
- Production minify scripts that generate a ready-to-deploy `dist/` folder

## Tech Stack
- HTML
- Tailwind CSS (CLI)
- JavaScript

## Project Structure (high-level)
- `src/input.css` → Tailwind input file
- `public/` → development files (HTML/CSS/JS)
- `public/styles/app.css` → generated Tailwind output (dev)
- `dist/` → minified production build (generated)

## Run Locally (Development)

1) Install dependencies:

    npm install

2) Start Tailwind watcher (generates CSS into `public/styles/app.css`):

    npm run dev

3) Open in browser:

- `public/index.html`

## Production Build (Minified)

Generate a minified build in the `dist/` folder:

    npm run minify:all

Output files:
- `dist/index.html`
- `dist/styles/app.min.css`
- `dist/js/app.min.js`

## License
MIT
