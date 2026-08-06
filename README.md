# RocketRush Portfolio Site

Single-page site built from the case-study PDF. Open `index.html` directly in a browser to preview — no build step needed.

## Design
Light, clean SaaS look inspired by the teamrocketrush-ui reference (white background, purple accent, black pill nav CTA, rounded cards, numbered belief list with tag chips).

## Wired links
- Nav "Pricing" button and both "Process + Pricing" CTAs → https://teamrocketrush-ui.github.io/linkedin-personal-brand-partnership/ (opens in a new tab)
- "Full Case Studies" buttons scroll to the on-page case study for now

## Still placeholder — swap before publishing
- **Gallery** — 2 video tiles say "coming soon." Replace `.gallery-item.video` blocks with real `<video>`/embeds.
- **Client logos** — 4 companies have no logo file yet, shown as text badges: Great Place To Work, Bank of Muscat, Ashvini Eyecare, BCG India.
- **Footer** — email and "Website" link are placeholders.

## Structure
```
index.html
assets/
  images/   — case-study & proof screenshots
  logos/    — client logos
```

## Hosting on GitHub
Works as-is with GitHub Pages — push this folder to a repo and enable Pages on the `main` branch (root), or a `docs/` folder.
