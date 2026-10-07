# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

Mini site (in Brazilian Portuguese) about the history and discography of the band Oficina G3. It is plain static HTML/CSS — no build step, package manager, linter, or tests. To preview, open `index.html` in a browser or serve the folder (e.g. `python3 -m http.server`).

## Structure

- `index.html` — landing page: band intro plus a grid of album links (`.albuns-container > a.album`).
- `pages/<album>.html` — one page per album, each linking back to `../index.html`. All 10 albums are linked from the index and have complete pages.
- `style/style.css` — the single shared stylesheet for every page (Raleway via Google Fonts). Mobile responsiveness lives in the `@media` blocks at the end (breakpoints 900px and 600px). Styles are class-based per section: `.home`/`.albuns` (index), `.hero`/`.descricao`/`.tracklist`/`.streamings` (album pages).
- `script/script.js` — empty; only `index.html` includes it (`defer`).
- `images/` — album covers named `<slug>-image.jpg`, plus `logo.png` and `background.avif`.

## Conventions

- Album pages are copy-paste templates (see `pages/o-tempo.html`): header with logo → `section` with `.botao-voltar` and `#hero` (cover, title, "year • genres") → `#descricao` ("O Álbum") → `#tracklist` (`<ol>`) → `#streamings` ("Ouça Agora", Spotify and Apple Music `iframe` embeds in `.iframes`) → footer. New album pages should reuse this structure and CSS classes. Asset paths in `pages/` use the `../` prefix.
- Filenames/typos to be aware of when linking: the Indiferença cover is `images/indifecenca-image.jpg` (misspelled), the Histórias de Bicicletas page is `pages/h&b.html` (cover `historias-e-bicicletas-image.jpg`), and the index card text "Elektracustika" links to `elektracustica.html`.
- Content language is pt-BR; keep UI text and album copy in Portuguese.
