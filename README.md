# Farrell & Co — Homepage Redesign Concept

A homepage redesign concept for [Farrell & Co Chartered Accountants](https://www.farrellco.co.uk/), Hemel Hempstead, prepared by AQ Digital.

This is a design concept, not the official Farrell & Co website. All firm details are taken from their current public website.

## Structure

```
index.html        Single landing page
styles.css        All styles
script.js         Mobile menu, header shadow, scroll reveals
assets/           Logo mark (favicon) and ICAEW badge
.nojekyll         Tells GitHub Pages to serve files as-is
```

No build step, dependencies or framework. Fonts load from Google Fonts.

## Run locally

Open `index.html` in a browser.

## Deploy to GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**, then choose `main` and `/ (root)`.
4. Save. The site will be published at `https://<username>.github.io/<repository>/` within a minute or two.

All paths are relative, so the page works from a repository subpath without changes. The page includes `noindex, nofollow` so search engines don't index the concept.
