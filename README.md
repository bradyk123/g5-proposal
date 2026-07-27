# Client proposal

A single-page proposal site. Static HTML, no build step, no dependencies.

- `index.html` — the entire site (styles and scripts inlined)
- `robots.txt` — blocks search engine crawling

## Notes

The page is excluded from search indexing via `robots.txt` and a `noindex`
meta tag. It is still reachable by anyone with the URL — treat the link as
shareable-but-unlisted, not private.

## Editing

Open `index.html` and edit directly. Changes pushed to `main` deploy
automatically via GitHub Pages.
