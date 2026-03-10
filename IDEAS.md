# Ideas Scratch Pad

## "Pick Your Fighter" About Page
Instead of linking between A/B/C variants at the bottom of each page,
create a landing experience where the visitor chooses which version of Vinh they want to meet:

- **The Engineer** → about.html (Terminal)
- **The Designer** → about-b.html (Clean Card)
- **The Human** → about-c.html (Expressive)

Could live at `/about.html` as an interstitial before any content loads.
Fits the HCDE dual identity (human + computer) concept.
Could be a simple 3-column card picker, or something more playful.

---

## Projects Page
Build a `projects.html` page with a card grid layout, linked from the nav.
Each card should show: title, category tag, short description, and a link to detail page (future).
Source data from `content.json` (same centralization pattern as About).
Categories to represent: Software, Hardware/IoT, Mobile, Web, UX Research, Concepts/Ideas.

---

## High Contrast / Accessibility Toggle
Add a toggle (button or keyboard shortcut) to switch the site into a high-contrast mode.
Motivation: the current dark theme with muted colors (#a0a0b8, #6a6a8a) has low contrast ratios
that don't meet WCAG AA standards — ironic for an HCDE portfolio.
Implementation ideas:
- CSS custom properties (variables) for all colors, swap them on toggle
- Persist preference with localStorage
- Could also just audit + improve base contrast without a toggle

---

## Clickable Project Cards
Make each project card on `projects.html` link to a detail page or expandable view.
Options:
- Modal/overlay that expands the card in place (no new page needed yet)
- Individual detail pages (e.g. `projects/rainier.html`) for case study writeups
- External links where applicable (GitHub, live site, YouTube, etc.)
Start simple: add an optional `link` field to `projects.json` and render it when present.

---

## Other Ideas
(add more as they come up)
