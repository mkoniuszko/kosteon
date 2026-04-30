# Kosteon — Fizjoterapia Warszawa

Static website for [kosteon.pl](https://kosteon.pl), a physiotherapy practice in Warsaw.

## Structure

```
index.html        # Polish version
index-en.html     # English version
styles.css        # All styles
assets/           # Images and other static files
```

## Development

No build step — open `index.html` directly in a browser or serve with any static file server:

```bash
npx serve .
```

## Deployment

The site is hosted on GitHub Pages. Pushing to `master` deploys automatically. The custom domain is configured via `CNAME`.
