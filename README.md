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

## Notes

- All copy is paraphrased from the real orchard-rite.com content (specs,
  history, FAQs) — nothing is copied verbatim.
- The three grower testimonials on `news.html` link out to the real
  orchard-rite.com pages rather than inventing quotes for real people.
- Diagrams (inversion layer, tower, ORCell) are hand-drawn inline SVG, so
  there are no image assets to source or license.
