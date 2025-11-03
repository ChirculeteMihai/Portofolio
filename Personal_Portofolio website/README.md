# Personal Portfolio – GitHub Pages

A minimal, fast, and accessible personal site template ready for GitHub Pages.

## Features
- Pure HTML/CSS/JS (no build step)
- Responsive layout and accessible navigation
- 404 page for GitHub Pages
- Minimal `_config.yml` for Pages

## Structure
- `index.html` – main page with sections (Home, About, Projects, Contact)
- `404.html` – not found page handled by Pages
- `assets/css/styles.css` – theme variables and responsive styles
- `assets/js/main.js` – mobile nav + small enhancements
- `assets/img/` – images, favicon, and social preview
- `_config.yml` – configuration for GitHub Pages

## Quick start
1. Replace "Your Name" and profile links in `index.html` and `_config.yml`.
2. Add your images to `assets/img/` and update `og-image.png` and `favicon.png` if desired.
3. Commit and push to GitHub.

## Deploy on GitHub Pages
- User/Org site: Create a repo named `your-username.github.io`. Push these files to the `main` branch.
- Project site: Use any repo name. Push to `main`, then enable Pages in Settings → Pages. Set Branch = `main` and folder = `/root`.

If using a project site, set `baseurl` in `_config.yml` to `"/REPO_NAME"` and adjust any absolute links accordingly. This template uses relative asset links, so it should work as-is.

## Local preview
Open `index.html` in your browser. For a local server with correct 404 behavior, use any static server (optional).

## Customize
- Colors: edit CSS variables in `assets/css/styles.css`.
- Sections: modify markup in `index.html`; duplicate `.card` for more projects.

## License
MIT – do whatever you like, just replace my placeholders with yours.