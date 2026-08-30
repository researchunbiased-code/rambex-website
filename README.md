# Rambex Website — Concept Redesign

A static, GitHub/Cloudflare-ready Rambex website redesigned to follow the supplied Rambex concept much more closely.

## Structure

- `index.html` — complete responsive single-page site
- `style.css` — responsive styling and layout
- `assets/rambex-logo.png` — Rambex logo
- `assets/rambex-concept.png` — original concept reference
- `assets/rambex-hero.jpg` — clean hero image extracted from the supplied concept artwork

## Deploy

### GitHub Pages
Upload the contents of this folder to the repository root and enable GitHub Pages from the `main` branch.

### Cloudflare Pages
Connect the GitHub repository to Cloudflare Pages:
- Framework preset: **None**
- Build command: leave blank
- Build output directory: `/`

No build step or Node.js dependency is required.

## Notes

The layout intentionally uses the concept image as a design reference rather than displaying the entire screenshot as a page background. The main visual language — dark header, compact mountain hero, three circular system stages, dark benefit strip, orange/blue/green accents, thin technical lines and modular cards — is carried through the entire site.

The contact button currently points to `info@rambex.com`; replace it with the preferred Rambex contact address if needed.
