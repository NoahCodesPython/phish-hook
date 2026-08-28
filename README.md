# Phish Hook

Phish Hook is a browser extension that detects phishing deception patterns before a user takes a risky action.

## Website

The public site is a landing page that explains the extension, showcases URL + QR phishing scenarios, and links to the interactive dashboard demo.

## Build and package extension

```bash
npm install
npm run release:extension
```

This produces:

- `dist/` — unpacked extension bundle to load in Chrome.
- `public/phish-hook-extension.zip` — downloadable ZIP package exposed by the landing page.

## Logo

The project logo is stored as `public/phish-hook-logo.jpeg` and is used on the landing page.
