# Orchard-Rite — Modernized Concept Site

A static, multi-page redesign concept for orchard-rite.com. Plain HTML/CSS/JS —
no build step, so it deploys as-is to GitHub Pages.

## Structure

```
index.html            Home
tree-shakers.html      Tree shaker models + innovations
wind-machines.html     Wind machine science, specs, engines, accessories
orcell.html            ORCell remote monitoring
about.html             History & manufacturing
news.html              Industry updates & grower testimonials (link out)
faqs.html               Frost-protection FAQ accordion
contact.html            Distributor / contact links
assets/style.css        Shared stylesheet (design tokens at the top)
assets/script.js        Mobile nav toggle + FAQ accordion
```

## Deploying to GitHub Pages

1. Create a new repo (or use an existing one) and add these files at the root
   (or in a `/docs` folder — your call).
2. Commit and push.
3. In the repo: **Settings → Pages → Source**, pick the branch (and `/docs`
   folder if you used one).
4. GitHub will publish at `https://<username>.github.io/<repo>/`.

No dependencies to install — the only external calls are to Google Fonts
(`fonts.googleapis.com` / `fonts.gstatic.com`) for Space Grotesk and
Source Serif 4.

## Media

- `assets/img/wind-machine-orchard.jpg` and `assets/img/tree-shaker-orchard.jpg` are
  your supplied photos, used as the Wind Machines / Tree Shakers page-hero
  backgrounds and as the poster/background image on the homepage's dark
  "Wind Machines" panel.
- `assets/video/wind-machine.mp4` and `assets/video/tree-shaker.mp4` are your
  supplied homepage videos, used as the two autoplay/muted/looping hero
  clips on `index.html`.
- The facility diagram on `about.html` and the inversion-layer / ORCell
  diagrams are original inline SVG illustrations (no photo was supplied for
  those, so they're drawn rather than sourced) — no external image files
  to license or go missing.

## Notes

- All copy is paraphrased from the real orchard-rite.com content (specs,
  history, FAQs) — nothing is copied verbatim.
- The three grower testimonials on `news.html` link out to the real
  orchard-rite.com pages rather than inventing quotes for real people.
- Diagrams (inversion layer, tower, ORCell) are hand-drawn inline SVG, so
  there are no image assets to source or license.
