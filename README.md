# Scrye Systems — Website

A static single-page site for [Scrye Systems](https://scryesystems.com), a systems development firm focused on positive-expectancy trading systems.

## Stack

- Plain HTML, CSS, and a sprinkle of inline SVG
- No build step, no framework, no dependencies
- Google Fonts (Fraunces, Instrument Sans, JetBrains Mono) loaded via CDN

## Local development

Clone the repo and open `index.html` in a browser:

```bash
git clone https://github.com/YOUR-USERNAME/scrye-site.git
cd scrye-site
open index.html   # macOS
# or just double-click it in Finder / Explorer
```

No install step. Edit, save, refresh.

## Deployment (GitHub Pages)

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under "Build and deployment," set the source to `main` branch, `/ (root)`.
4. Save. GitHub will give you a URL like `https://YOUR-USERNAME.github.io/scrye-site/` within a minute or two.

To use a custom domain (like `scryesystems.com`), add a `CNAME` file with the domain in it and point your DNS at GitHub Pages.

## Structure

```
.
├── index.html      # everything — markup + styles + inline SVG
├── README.md       # you are here
└── .gitignore
```

## To do

- [ ] Wire up real YouTube links in the Videos section
- [ ] Add a `/systems` detail page per offering
- [ ] Swap the ticker data for a real feed or make it clearly illustrative
- [ ] Replace placeholder social links in the footer
- [ ] Add favicon and OG image

## License

© 2026 Scrye Systems. All rights reserved.
