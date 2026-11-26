# Know Your Products: parent site

A small static site for `www.knowyourproducts.in`. Plain HTML and CSS, no scripts, no build step, no images.
Fonts (Manrope, Inter) are self-hosted under the SIL Open Font License; the licences are in `fonts/`.

## Before publishing

The page only states what is known for certain: that Know Your Products makes Protryx, and what Protryx does.
Two places in `index.html` are marked `OWNER TO SUPPLY`:

1. **About the company**: who runs it, where it is based, when it started. Keep it factual.
2. **Contact**: an email address or other contact route.

Do not add customers, partners, statistics or services unless they are real and can be checked.

## Publishing

The current `www.knowyourproducts.in` site is served by GitHub Pages from a separate repository.
To publish this design there, replace that repository's site files with the contents of this folder
(keep its existing `CNAME` file, which tells GitHub Pages to answer for `www.knowyourproducts.in`).
The Protryx app itself stays at `protryx.knowyourproducts.in` on Render and is not affected.
