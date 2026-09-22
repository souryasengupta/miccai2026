# MICCAI 2026 paper explorer

Interactive index of all 1,166 MICCAI 2026 accepted papers, filterable by organ,
modality, dimension, AI method, task and presentation type.

`index.html` is fully self-contained — no build step, no CDN, no network calls.
Open it locally or serve it as a static site.

## Publish on GitHub Pages
1. Create a repository (any name, e.g. `miccai2026`).
2. Upload `index.html`, `.nojekyll` and `robots.txt` to the default branch.
3. Settings -> Pages -> Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. Live in ~1 minute at `https://<user>.github.io/<repo>/`.

`.nojekyll` tells Pages to serve the file as-is. `robots.txt` and the page's
`noindex` tag keep it out of search results.

**Anyone with the URL can open it.** A GitHub Pages site is public even when the
source repository is private; private publishing needs GitHub Enterprise Cloud.

## Data provenance
Parsed from the MICCAI 2026 oral, spotlight and poster schedule PDF (revised
2026-09-08) and matched against public arXiv abstracts retrieved 2026-09-21.
412 of 1,166 papers had a retrievable abstract; the rest are classified from
titles alone and badged accordingly in the table.
