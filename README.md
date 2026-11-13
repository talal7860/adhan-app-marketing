# Adhan Times marketing site

Static landing page for the Adhan Times app (iPhone, iPad, Apple Watch), served at
https://adhantimes.conelabs.org/.

- `index.html`: the whole page (inline CSS and JS, Google Fonts).
- `img/`: screenshots, icons and the Open Graph image.
- `netlify.toml`: Netlify publishes the repo root, no build step. Every push to `main` deploys.

DNS: `adhantimes.conelabs.org` is a CNAME in Route 53 to the Netlify site.

The app itself lives in https://github.com/talal7860/prayer-app.
