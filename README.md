# neoyagami.github.io

A simple English landing page for MouseJump, YASDEC, PanelPC, and Backloop, with a dark background and soft green and blue accents and a generic note about AI-assisted development. OpenGC570D appears below the desktop tools in a separate experimental kernel driver section.

## Preview

From the repository directory, run:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>. No build step, JavaScript, external fonts, or package installation is required.

## Edit

- `index.html`: project descriptions, download links, and the development note.
- `backloop.html`: Backloop overview, operating commands, and links to its upstream guides.
- `stylesheets/styles.css`: layout, responsive styles, and color variables.
- `images/favicon.svg`: browser icon.
- `fonts/`: the local Open Sans files retained from the original site.

Project information is based on the linked project READMEs. Download links point to each repository's latest release, so they do not need updating for each version.

## GitHub Pages

The site is designed for <https://neoyagami.github.io/>. Push these files to the repository's `master` branch, then set **Settings → Pages → Build and deployment → Deploy from a branch** to **master / (root)** if it is not already configured. `.nojekyll` tells Pages to serve the static files directly.

The older theme's unused assets are retained but are no longer loaded by the page.
