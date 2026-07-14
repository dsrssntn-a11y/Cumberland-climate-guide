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

## Security checks

This repo includes a GitHub Actions secret scan workflow at [.github/workflows/secrets-scan.yml](.github/workflows/secrets-scan.yml) that runs on pushes, pull requests, and weekly.

To run a local scan with Gitleaks:

```bash
pnpm run security:secrets
```

If you prefer a containerized run:

```bash
docker run --rm -v "$PWD:/workdir" -w /workdir zricethezav/gitleaks:latest detect --source . --verbose --redact
```

To enable GitHub Secret Scanning for the repository:

1. Open the repository on GitHub.
2. Go to Settings → Security → Secret scanning.
3. Enable Secret scanning and Push protection.

---

Built for [Terra Studio](https://studio.terra.do). Free to use and adapt.
