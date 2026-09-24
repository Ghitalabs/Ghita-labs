# Ghita Labs

This is the little corner of the internet for Ghita Labs.

It’s intentionally simple: a static, bilingual site with no framework, no build step and no backend to babysit. The site introduces the lab, keeps a public record of the experiments I’m exploring, and gives people a straightforward way to reach me.

Right now, Startly is paused and LedgerFold is in research. That may change as the work changes. I’d rather keep the site honest than make an early experiment look more finished than it is.

## What’s in here

- `index.html` holds the actual site.
- `styles.css` handles the layout, responsive design and visual system.
- `script.js` powers the English/French switch and the small interactions.
- `404.html` is the custom error page.
- `robots.txt` gives search crawlers the basic rules.
- `ghita-labs-logo.png` is the transparent Ghita Labs logo.
- `team-ghita-analyst.jpeg`, `team-gigi-builder.jpeg` and `team-ghitou-skeptic.jpeg` are the illustrated “Meet the Lab” portraits.

## Publishing

There’s nothing to compile. Upload the files as they are to GitHub Pages and the site is ready to serve.

Before pushing a new version live, I check it once on a phone and once on a desktop. That catches most of the things that matter here: broken links, awkward spacing, unreadable text and images that are heavier than they need to be.

## A few deliberate non-features

There are no accounts, cookies, analytics, API keys, database or mailing-list forms in this version. The contact button opens a real email inbox. Keeping the site this small is partly a design choice and partly a maintenance choice.

If Ghita Labs eventually needs more infrastructure, it can earn it first.

## Search and sharing

The site includes the boring but useful pieces that are easy to forget: a canonical URL, search metadata, a sitemap, robots rules, structured data for Ghita Labs and Ghita El Belghiti, and social preview metadata.

`og-image.png` is the large preview used when the site is shared. `favicon.png` and `apple-touch-icon.png` handle browser tabs and saved shortcuts.

The canonical URL currently points to `https://ghitalabs.github.io/`. If Ghita Labs moves to a custom domain later, the canonical, Open Graph URLs, sitemap and robots file should all be updated together rather than leaving the old GitHub Pages address behind.

After publishing, the only manual SEO setup worth doing at this stage is adding the site to Google Search Console and submitting `sitemap.xml`. I’m deliberately not turning this repository into a content machine before there is a product and a search problem worth writing for.
