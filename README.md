# 🔥 Kindling

A home page concept for **Kindling** — a habit-streak app that turns daily
consistency into a flame you can actually see grow, instead of a generic
streak counter or points system.

Built for a frontend take-home challenge (Part 2: "The Premium Home Page").

## Live demo

https://zingy-lolly-4a8235.netlify.app

## What's here

- Hero section with the core value prop and a single clear call to action
- A product mockup (labeled as example data) showing what the app actually
  looks like in use — not just marketing claims about it
- A three-step "how it works" section
- A feature grid explaining the product's philosophy
- Full responsive layout: tested at 390px (mobile) and 1440px (desktop),
  no horizontal scroll
- Full dark mode support (all-or-nothing, toggle in the nav)
- One deliberate micro-interaction: scroll-triggered reveals, plus a small
  hover state on the feature cards
- A hidden easter egg (click the flame icon three times)

## Tech

Plain HTML, CSS, and vanilla JavaScript — no build step, no framework,
no dependencies beyond two Google Fonts (Poppins for display, Inter for
body text). Colors are all CSS named colors (`orangered`, `gold`,
`firebrick`, `seagreen`, `ivory`, `dimgray`, `darkslategray`) rather than
hex codes, chosen to keep the palette easy to read and tweak directly in
the CSS.

Kept intentionally simple — one file, no dependencies to install — so it's
easy to read top to bottom and defend line-by-line.

## File structure

```
kindling/
├── index.html      # everything: markup, styles, and script in one file
├── DECISIONS.md     # design rationale, trade-offs, and AI-tool disclosure
└── README.md        # this file
```

## Running it locally

No build step needed. Either:

- Open `index.html` directly in a browser, or
- Serve it locally for a closer-to-production feel:
  ```bash
  python3 -m http.server 8000
  # then visit http://localhost:8000
  ```

## Deploying

Since it's a single static file, any free static host works:

- **Netlify Drop** — drag the `kindling` folder onto [app.netlify.com/drop](https://zingy-lolly-4a8235.netlify.app)
- **GitHub Pages** — push this folder to a repo, enable Pages on the `main`
  branch, and it'll serve `index.html` automatically
- **Vercel** — `vercel deploy` from inside the folder

## Notes

`DECISIONS.md` covers the reasoning behind the design direction, a trade-off
made under time pressure, and where AI tooling was used versus what was
personally verified — worth reading before the follow-up call.
