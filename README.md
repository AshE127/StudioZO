# Studio Zo — Website

**Sweat. Sculpt. Align.**

A boutique heated mat Pilates studio website built with React (JSX + Babel standalone).

## Pages
1. **Home** — Landing page with hero, class types, testimonials, childcare teaser
2. **Memberships & Pricing** — Tiers, drop-ins, class packs, BSport purchase widget
3. **Schedule & Booking** — BSport calendar widget, new client info
4. **About Studio Zo** — Story, differentiators, instructor team
5. **Events & Community** — Upcoming/past events, mailing list
6. **Childcare** — Dedicated page for kids' room (key differentiator)

## Tech Stack
- React 18 (via CDN)
- Babel Standalone (JSX transpilation — no build step)
- Playfair Display + Urbanist (Google Fonts)
- BSport widget placeholders (ready for embed codes)

## Deployment (GitHub Pages)
1. Push this repo to GitHub
2. Go to Settings → Pages → Source: Deploy from branch → `main` / `root`
3. Site will be live at `https://yourusername.github.io/repo-name/`

## BSport Integration
Replace the placeholder widgets in `app.jsx` by searching for `BsportWidget` and replacing with your actual BSport embed code from Settings → Widget in your BSport dashboard.

## Brand Colors
| Color | Hex | Usage |
|-------|-----|-------|
| Soft Ivory | #F5F2EE | Primary background |
| Rich Black | #111111 | Text |
| Soft Nude Beige | #C97C5D | Accent color |
| Dark Forest Green | #0C1910 | Secondary |
| Pure White | #FFFFFF | Cards, sections |

## Logo Assets
All logo variations are in `/assets/`:
- `logo-horizontal-black.png` — Nav logo (dark text, transparent bg)
- `logo-horizontal-white.png` — For dark backgrounds
- `logo-monogram-black.png` — SZ circle mark (dark)
- `logo-monogram-white.png` — SZ circle mark (light)
- `logo-full-black.png` — Full logo with tagline (dark)
- `logo-full-white.png` — Full logo with tagline (light)
- `logo-stacked-black.png` — Stacked layout (dark)
- `logo-stacked-white.png` — Stacked layout (light)
