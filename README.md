# Anas Osman — improved English / Arabic website

This version fixes the live website’s design conflict: each language page now contains its own CSS and JavaScript. It does not load `assets/css/style.css` or depend on a GitHub Pages theme.

## Upload these files to the root of your existing repository

- `index.html` — complete English website.
- `index-ar.html` — complete Arabic website with right-to-left formatting.
- `anas.jpg` — your portrait.
- `Anas_Osman_CV.pdf` — your latest CV, unchanged.
- `.nojekyll` — serve the static site directly.

Copy the FILES INSIDE this folder into the top level of your `osmananas.github.io` repository. Replace the existing `index.html` and `index-ar.html`. Do not place this whole folder inside another folder in the repository. The old `assets/css/style.css` is no longer used by these pages. Keep your current GitHub Pages setup and commit the updated files.

Both HTML files include the entire website, with focused sections for Home, Research, Publications, Education & Experience, Skills, Conferences & Training, About and Contact. Navigation switches between these sections; normal browser Back and Forward and direct section links work. All eight publications, six conference entries, selected training, languages, awards and your professional profile are included. The language switch preserves the current section.

## Local preview

Extract the ZIP and open `index.html` or `index-ar.html`. Keep the photo and PDF in the same folder as the HTML. There is no build step, npm dependency or backend. The optional Cairo and Amiri fonts use Google Fonts; system fonts provide an offline fallback.

## Editing

Text, colours, layout and scripts are all inside the HTML files. Look for the `anas-website-design` style block to adjust the shared colours. Update both language versions when changing a detail. Replace `anas.jpg` or `Anas_Osman_CV.pdf` using the same filename when updating those files. Published titles and author lists keep their official English spelling in both language versions.

The publication search, filters and sorting, theme toggle, mobile navigation and email-copy buttons work locally. Without JavaScript, every section remains visible and ordinary links and CV downloads still work. The site has no analytics or external contact-form service.

The anticipated PhD completion remains July 2027. Academic service lists the named reviewer role; the supplied CV PDF is unchanged. Decorative contour graphics are design elements, not scientific data plots.
