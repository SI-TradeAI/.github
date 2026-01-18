# Trade AI

Analysis-first AI investment adviser that turns market news into structured hypotheses and daily validation. 

## What the app can do
- Landing page with polished marketing sections and CTA into the app shell.
- Dashboard view with market cards and drill-in to stock detail pages.
- Calendar view for market events with deep-linked event detail pages.
- News & Insights feed with filtering and deep-linked detail pages.
- Stock detail experience with chart, key metrics, events timeline, AI analysis, and hypotheses.
- Hypothesis & Validation placeholder page wired into the app navigation.

## Notes
- Tailwind v4 (configless) with design tokens in `js/app/src/app/globals.css`.
- Landing components live under `js/app/src/components/landing`.
- App components live under `js/app/src/components/app` (calendar, dashboard, news, stock, utils).
- Shared app types are under `js/app/src/types/app`.
- Favicon and SI logo assets are under `js/app/public`.

## Roadmap (high level)
- Phase 0: Web shell (done).
- Milestone 1: Data ingestion + calendar/news/dashboard.
- Milestone 2–4: Hypothesis agent, validation loop, confidence/coverage surfacing.
