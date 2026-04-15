# Studio Zo — Northern Virginia's First Infrared Heated Mat Pilates Studio

Live at: **https://ashe127.github.io/StudioZO/**

## What's New in This Build

- **Press banner** at top: "As seen on Fox 5 DC & ABC 7 Good Morning Washington" → links to Fox 5 video
- **Headline:** "Northern Virginia's First Infrared Heated Mat Pilates Studio with Childcare"
- **Primary CTA site-wide:** "Join Founding Membership" → BSport founding link
- **Founding pricing visible everywhere:** $179 (code: LORTONVA2026) + $219 (code: LORTONKIDSVA2026)
- **Intro popup:** Shows both founding offers with codes on first page load
- **Class names updated:** Zo Sculpt, Zo Flow, Zo Method, Zo Restore
- **"Zo Kids"** replaces "Childcare" everywhere
- **About page subsections** with hamburger menu jump links: Our Story, The Method, Founder, What Sets Us Apart
- **Founder section** uses `assets/Founder pic .JPG`
- **Eventbrite embed** on Events page (org 120805755958)
- **"What to Expect" section** rewritten with full new copy
- **Marquee text** darkened for readability

## Pages
1. Home — founding membership focus, branded mid-page tiers, BSport widget at bottom
2. Memberships & Pricing — founding tiers up top, drop-ins last
3. Schedule & Booking — BSport calendar + 4 Zo class types + What to Expect
4. About — multi-section with anchor jumps for hamburger menu
5. Events — Eventbrite embed + past partners gallery
6. Zo Kids — underplayed, dedicated page

## Tech Stack
- React 18 (CDN)
- Babel Standalone (no build step)
- BSport widgets via iframe isolation (resolves React conflict)
- Eventbrite iframe embed
- Playfair Display + Urbanist fonts

## Asset Notes
**Important:** Make sure `assets/Founder pic .JPG` (note the space) exists in your repo for the founder section to display.

## BSport Setup (already configured)
- Company ID: 5566
- Calendar widget ID: 805329
- Subscription widget ID: 12349
- Founding Membership URL: https://backoffice.bsport.io/m/Studio%20Zo/5566/subscription/?tabSelected=5&index=5

## To Deploy
1. Replace `app.jsx` and `index.html` in your GitHub repo
2. Commit + push
3. Hard refresh browser (Ctrl+Shift+R / Cmd+Shift+R)
