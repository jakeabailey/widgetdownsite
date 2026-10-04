# Widgetdown website

A static site: `index.html` (marketing), `legal.html` (privacy policy and terms of
use), `styles.css` and `images/`. No build step, no JavaScript, no cookies.

## Before publishing
- Replace `support@example.com` (index.html footer, legal.html contact and footer)
  with a real support address.
- Check the developer name in legal.html ("Who we are").
- Have the privacy policy and terms reviewed; they're written from how the app works,
  not by a lawyer.
- When the app is live, swap "Coming soon to the App Store" for Apple's official
  "Download on the App Store" badge (from Apple's marketing resources) linking to the
  listing, and keep its alt text.

## Hosting
Any static host works, e.g. GitHub Pages (publish this folder), Netlify or Cloudflare
Pages (drag and drop the folder). Use the published `legal.html` address as the
**Privacy Policy URL** in App Store Connect (`…/legal.html#privacy`).

## Accessibility (WCAG 2.2 AA)
Landmarks and a skip link; one h1 and no skipped heading levels; descriptive alt text
on every screenshot (decorative images use `alt=""`); colour tokens checked for
contrast in light and dark mode (text ≥ 5.7:1, focus outlines ≥ 6.1:1); visible
focus outlines; links and controls at least 44px tall; no motion, and smooth scrolling
only without reduced-motion; reflows to 320px; works with Windows high-contrast mode.

## Screenshots
`images/` are renders of the real widget code plus a Simulator screenshot of the app.
