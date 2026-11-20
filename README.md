# Sara Lufrano · Portfolio

A static portfolio for a technical product leader and independent builder. Original watercolor artwork, ivory paper, blue/lavender/pink/gold accents, editorial typography, and restrained movement connect the homepage and three case studies.

## Preview

From the repository directory:

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Open http://127.0.0.1:4173. No dependencies or build step are required.

## Edit

- `index.html`: introduction, selected work, dynamic-pricing decision, approach, experience, independent sizing app, and contact.
- `case-studies/`: Control Station platform replacement, CityPASS/GetYourGuide integrations and payments, and build/buy/retire decisions.
- `style.css`: shared responsive layouts, print styles, and reduced-motion support.
- `script.js`: accessible mobile navigation and current footer year.
- `assets/watercolor-splash.webp`: locally bundled watercolor artwork with transparency; no external image or font requests.

The sizing illustration is editorial artwork, not an application screenshot. Case-study figures are preserved from the existing portfolio.

## Deployment

This repository is designed for the existing GitHub Pages URL, https://saralufrano.github.io/portfolio/. Relative paths support the `/portfolio/` prefix and direct visits to case-study pages.

Review and merge the redesign branch into the branch currently selected in GitHub **Settings → Pages**. If Pages uses `main` and the repository root, merging into `main` publishes the redesign. If a workflow or another source branch is configured, use that existing setup. No hosting migration is necessary.

## Verification

The redesign was checked in-browser at narrow mobile, tablet, and desktop widths. Home and case-study navigation, mobile-menu open/close, image loading, console output, and horizontal overflow were checked. All 65 local links, assets, and section fragments were checked; the JavaScript passed its syntax check. Motion is disabled by `prefers-reduced-motion: reduce`; content and navigation remain available without JavaScript.
