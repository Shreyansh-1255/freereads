# FreeReads 📚

Search public-domain and free ebooks across multiple legal libraries at once — one search box, five sources, zero hosting.

**[Live demo →](https://shreyansh-1255.github.io/freereads/)**

## What it does

FreeReads is a meta-search tool. It doesn't host or store any books — it queries free, public APIs from legitimate libraries and shows you the results as clickable cards. Click a card and you're sent straight to the original source to read or download.

## Sources searched

| Source | What it offers |
|---|---|
| [Project Gutenberg](https://www.gutenberg.org) | 70,000+ public-domain ebooks |
| [Open Library](https://openlibrary.org) | Free ebooks & lending library (Internet Archive-backed) |
| [Internet Archive](https://archive.org) | Digitized texts, public-domain books |
| [LibriVox](https://librivox.org) | Free public-domain audiobooks |
| [Wikisource](https://en.wikisource.org) | Transcribed public-domain texts |
| [Standard Ebooks](https://standardebooks.org) | Beautifully formatted classics (search link only — no public API) |

## Features

- Progressive results — each source shows its results as soon as it responds, no waiting for all five
- Toggle sources on/off before searching
- Single static HTML file — no build step, no backend, no database
- Nothing is scraped, mirrored, or re-hosted — every result links out to its original source

## Tech

Plain HTML, CSS, and JavaScript. No frameworks, no dependencies. Fonts: [Fraunces](https://fonts.google.com/specimen/Fraunces) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono).

## Running locally

Just open `index.html` in a browser — no server or build step needed.

## Deploying

This repo is set up for [GitHub Pages](https://pages.github.com/). Push to `main`, enable Pages in **Settings → Pages**, and it's live.

## Why no PDF Drive / Z-Library / similar

FreeReads only indexes sources that legally distribute public-domain or openly licensed content. Sites that distribute copyrighted material without permission are intentionally left out.

## License

MIT — see [LICENSE](LICENSE).
