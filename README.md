# Vector Signal Board

Public-facing track record of automated NQ futures signals under Vector Algorithmics.

## What this is

Every weekday, a single strategy is selected for live execution on NQ futures. This board publishes:
- The morning traffic light (GREEN / YELLOW / RED) with VIX, oil, and geopolitical context
- The day's strategy pick
- Results as they resolve, normalized to what a single NQ contract would have earned

No account balances, no personal positions. Just signals, picks, and outcomes.

## Stack

- Single `index.html` static page
- Data source: published Google Sheet CSV
- Write path: Google Apps Script web app endpoint
- Hosting: Vercel
- Auto-refresh every 5 minutes

## Setup

See [SETUP.md](./SETUP.md) for the full deployment guide.

## Disclosure

Per-contract results are reported net of estimated commissions. Futures trading involves substantial risk of loss. Past performance does not guarantee future results. This board is an independent record and is not investment advice.
