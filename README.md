# michaelatkinson.me

Personal site for Michael L. Atkinson — Enterprise Venture Architect, creator of Certified Intelligence™, founder and CEO of FohBoh.ai.

## What this is

A single-page static site. No build step, no framework, no dependencies beyond Google Fonts.

```
index.html          the entire site — markup, styles and script in one file
assets/
  michael-atkinson.jpg    portrait, 4:5 crop
  favicon.svg             site icon
```

Routing is hash-based and handled in-page:

| Route         | Page     |
| ------------- | -------- |
| `#/`          | Home     |
| `#/about`     | About    |
| `#/advisory`  | Advisory |
| `#/contact`   | Contact  |

## Editing

Edit `index.html` directly. Open it in a browser to preview — no server required.

## Deployment

Hosted on Vercel, project `static-anchor`, under the `michael-atkinsons-projects` team.

The domain `michaelatkinson.me` is registered at GoDaddy (nameservers `ns15`/`ns16.domaincontrol.com`) and pointed at Vercel.

**Note on GoDaddy DNS:** domain forwarding rules on this registrar have twice blocked apex A records on these domains. Check Forwarding before changing any DNS here.

Once this repo is connected to the Vercel project, pushes to `main` deploy automatically. Vercel settings for a site of this shape:

- Framework preset: **Other**
- Build command: *(none)*
- Output directory: *(root)*

## Conventions

- US English spelling throughout.
- `FohBoh.ai` in camel case — never `FOHBOH`.
- Trademarked terms carry their mark on first use per page: Certified Intelligence™, MGE™, Sentry™, Cortex™.
