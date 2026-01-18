# Trade AI

Analysis-first AI investment adviser that turns market news into structured hypotheses and daily validation. Web shell is Next.js + TypeScript (Tailwind v4) in `js/app`; Python microservices will land in later phases.

## Structure
- `js/app`: Next.js App Router, marketing/landing shell.
- `.design`: design docs and phase plans (phase0, web rules, overview).

## Getting Started (web)
```bash
cd js/app
npm install
npm run dev
# visit http://localhost:3000
```

## Notes
- Tailwind v4 (configless) with design tokens in `src/app/globals.css`.
- Sections/components for landing live in `src/components/sections` and `src/components/section.tsx`.
- Favicon and SI logo assets are under `public/`.

## Roadmap (high level)
- Phase 0: Web shell (done).
- Milestone 1: Data ingestion + calendar/dashboard.
- Milestone 2–4: Hypothesis agent, validation loop, confidence/coverage surfacing.
