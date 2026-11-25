# Dr Abdul Joseph Fofanah (Dr Aajay)

Academic website and home of the Centre for Research, Innovation and Development (CRID-SL).

Live at **https://afofanah.pages.dev**

## What's here

| Path | Contents |
|---|---|
| `index.html` | The whole site: pages, styles, animations and publication data |
| `img/` | Photos, poster and book cover |
| `data/openalex.json` | Fallback citation figures (the page also fetches live figures from OpenAlex) |
| `404.html`, `robots.txt`, `sitemap.xml` | Housekeeping for GitHub Pages and search engines |

## Updating the site

- **Small text changes:** open `index.html` on GitHub, click the pencil icon, edit, and commit. The live site updates within a minute or two.
- **Photos:** upload new images into `img/` and reference them from `index.html`.
- **Publications:** each entry is a line in the `PUBS` list inside `index.html`; author lists are in `AUTHORS`.
- **Citations:** the OpenAlex card refreshes itself on every visit. The Google Scholar card is updated by hand.

## Publishing

GitHub Pages serves this repository from the `main` branch root (Settings → Pages → Deploy from a branch → `main` / root).
