# Shadownik — Project Hub

**5h4d0wn1k's Shadow Web ecosystem homepage**: a static, SEO-ready landing hub
that links the project portfolio, cybersecurity services, and company
capabilities — with privacy policy and terms pages, deployable to any static
host.

[![Stars](https://img.shields.io/github/stars/5h4d0wn1k/shadownikweb)](https://github.com/5h4d0wn1k/shadownikweb)
[![Last commit](https://img.shields.io/github/last-commit/5h4d0wn1k/shadownikweb)](https://github.com/5h4d0wn1k/shadownikweb)
[![Issues](https://img.shields.io/github/issues/5h4d0wn1k/shadownikweb)](https://github.com/5h4d0wn1k/shadownikweb)

## Why Shadownik

A single landing site should tell visitors who you are, what you build, and how
to reach you — fast, on any host, with no build step. Shadownik is a
self-contained static site: one `index.html` with hero, about, features,
gallery, events, metrics, FAQ, and contact sections, plus `privacypolicy.html`
and `termsandconditions.html` for legal completeness. The `CNAME` file points
the site at its live domain, and GitHub Pages-like hosts can serve it directly.

## Features

- **Single-file, zero-build site** — plain HTML/CSS/JS, no bundler required
- **Marketing sections** — hero, about, services, metrics, gallery, events, FAQ, contact form
- **Privacy policy & terms** — `privacypolicy.html` and `termsandconditions.html`
- **SEO metadata** — descriptive `<title>` and `<meta description>` in `index.html`
- **Brand assets** — bundled logo and brand files under `Shadownik Brand Website_files/`
- **Custom domain ready** — `CNAME` for `www.shadownik.online`
- **Security policy** — `SECURITY.md` for responsible disclosure

## Quickstart

Open `index.html` in a browser, or serve as static files:

```bash
python3 -m http.server 8000      # local preview → http://localhost:8000
```

## Project structure

- `index.html` — full landing page
- `privacypolicy.html`, `termsandconditions.html` — legal pages
- `CNAME`, `SECURITY.md` — domain + security reporting

## Contributing

File an issue or PR for content corrections, accessibility, or new sections.

## License

The site content and assets are provided as-is; no LICENSE file is bundled —
contact the owner before reusing assets.