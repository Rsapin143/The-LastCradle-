# The Last Cradle — Website

Static website deployment package.

## Structure
- `index.html` — website entry point
- `assets/css/styles.css` — website styling
- `assets/images/` — team portraits and other embedded images
- `assets/js/site.js` — JavaScript, if needed

## Preview locally
Open `index.html` in a browser, or run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Deploy
Upload the contents of this folder to a static hosting provider such as Netlify, Cloudflare Pages, GitHub Pages, or your own web server. Set the publish/root directory to the folder containing `index.html`. No build step is required.
