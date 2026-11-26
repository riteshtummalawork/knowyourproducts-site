# Protryx: public site

A small static site for `protryx.com` (`www.protryx.com` redirects to it). Plain HTML and CSS, no scripts, no build step, no images.
Fonts (Manrope, Inter) are self-hosted under the SIL Open Font License; the licences are in `fonts/`.

## Before publishing

The page only states what is known for certain: what Protryx does and what it does not do.
The logo is the Protryx X mark (navy tile, white and red strokes), the same mark the app uses.
Two places in `index.html` are marked `OWNER TO SUPPLY`:

1. **About Protryx**: who runs it, where it is based, when it started. Keep it factual.
2. **Contact**: an email address or other contact route.

Do not add customers, partners, statistics or services unless they are real and can be checked.

## Publishing

The `protryx.com` site is served by GitHub Pages from a separate repository.
To publish this design there, replace that repository's site files with the contents of this folder
(keep its existing `CNAME` file, which tells GitHub Pages to answer for `protryx.com`).
The Protryx app itself is at `exam.protryx.com` on Render and is not affected.
