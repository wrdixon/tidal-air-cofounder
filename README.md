# tidal-air-cofounder

Co-founder recruitment page for Tidal Air. Hosted via GitHub Pages.

## Structure

```
index.html          Main page
images/
  logo.svg                    Tidal Air logo
  rendering-classroom.jpg     Product rendering (vision section)
  prototype-cambridge.jpg     Real hardware photo (prototypes section)
  tidal-prototype-unit.jpg    Unit photo for comparison card
  coway-airmega-prox.png      Competitor photo for comparison card
```

## Editing

All text content is in `index.html`. Each section is clearly labeled with HTML comments.

Common edits:
- **Copy changes**: find the section comment (e.g. `<!-- WHY NOW -->`) and edit the text inside
- **Swap Bill's photo**: find the `<!-- PHOTO -->` comment in the role section, replace the placeholder div with `<img src="images/bill-dixon.jpg" ...>`
- **Update investor list**: find `<!-- INVESTOR BLOCK -->` in the traction section
- **Update proof points**: find `<!-- THREE PROOF POINTS -->` in the traction section
- **Update Grafana link**: search for `tbdair.grafana.net` and replace the href

## Deploying

Push to `main` branch. GitHub Pages auto-deploys.
