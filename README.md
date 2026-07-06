# Terra Studio City Guide — Starter Template

A minimal Astro + Tailwind starter for the Terra Studio Week 7 Build 2 exercise.

## What's included

- **Astro** — static site framework, reads your data at build time
- **Tailwind CSS** — utility-class styling, no CSS files to manage
- `src/data/verified.json` — sample Toronto data (replace with your city)
- `src/data/flagged.json` — empty placeholder for flagged entries
- `src/pages/index.astro` — starter page with category grouping

## Quick start

```bash
pnpm install
pnpm dev
```

Open http://localhost:4321 to see your site.

## How to use with Claude Code

1. Replace `src/data/verified.json` with your own data from the Cowork skill
2. Open Claude Code and describe the design you want in plain language
3. Claude Code will edit `src/pages/index.astro` and add components as needed
4. When it looks right: push to GitHub, deploy to Vercel

## Deploy

Push to GitHub, then import into Vercel. Astro is auto-detected — zero config needed.

---

Built for [Terra Studio](https://studio.terra.do). Free to use and adapt.
