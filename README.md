# Elixir Cleaning Services — homepage redesign

A static, mobile-first homepage concept for [Elixir Cleaning Services](https://elixircleaningservices.ca/). Open `index.html` directly or serve the repository root with any static web server. All site code and the Manrope font are local; original photography and the original logo are linked to the source website and therefore require a network connection. Links to the business's internal pages intentionally lead to the existing website. The demo uses `noindex, nofollow`.

## Files

- `index.html` — homepage
- `css/style.css` — responsive styles
- `js/script.js` — accessible mobile menu
- `assets/fonts/` — Manrope font files and license
- `.nojekyll` — GitHub Pages compatibility

## GitHub Pages

Publish the repository root from the desired branch in **Settings → Pages**, or use a Pages workflow. All local paths are relative, including for project subdirectory URLs.

## Source and limitations

Homepage copy and image URLs were taken from the existing homepage. The contact form links to the original contact page rather than claiming a static form can submit. Source images remain remotely hosted because the development environment could not download them from the source domain. The source's navigation and a license image could not be independently verified from the accessible page extraction; verify these against the original before production use. Colors are an editorial interpretation, not verified source color codes.
