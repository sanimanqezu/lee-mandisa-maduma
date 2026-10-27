# MANDISA

[![CI](https://github.com/sanimanqezu/lee-mandisa-maduma/actions/workflows/ci.yml/badge.svg)](https://github.com/sanimanqezu/lee-mandisa-maduma/actions/workflows/ci.yml)

A single-page tribute website — a photo and video gallery built as a self-contained static page with hand-written HTML, CSS, and a touch of JavaScript (scroll-reveal animations, lightbox-style gallery).

## What's here

| File | Purpose |
|---|---|
| `index.html` | The entire site — markup, styles, and scripts inline |
| `*.mp4` | Gallery video clips referenced by the page |
| `Sent/` | Source media |

No build step, no framework, no dependencies — just open the page.

## Viewing it locally

Any static file server works. For example:

```bash
npx serve . -p 3000
# then open http://localhost:3000
```

Or simply open `index.html` directly in a browser.

## Sharing a live preview

To share a temporary public link from your machine:

```bash
npx serve . -p 3000      # terminal 1
ngrok http 3000          # terminal 2 -> gives a public https URL
```

## Deploying

Being a static site, it hosts anywhere — GitHub Pages, Netlify, Vercel, or any static host. For GitHub Pages: enable Pages on the repository and serve from the default branch root.
