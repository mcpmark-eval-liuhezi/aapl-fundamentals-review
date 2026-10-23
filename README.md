# aapl-fundamentals-review

Fundamentals pack for **Apple Inc. (AAPL)** — a one-stop deep-dive for an investment club's monthly company review, built entirely from Yahoo Finance data pulled on **2026-10-23**.

## What's in this repository

- **[report.md](report.md)** — the single consolidated write-up, one section per topic:
  1. **Annual statements** — income statement, balance sheet and cash flow statement (FY2022–FY2025)
  2. **Quarterly trend** — the five most recent quarters
  3. **Profile and valuation** — sector/industry, market cap, key margins, multiples
  4. **Ownership** — overall breakdown plus the ten largest institutional holders
  5. **Dividends and splits** — full split history and the recent dividend run
  6. **Analyst moves** — every rating action from the past 12 months
  7. **Recent news** — the source's status on the day of the pull
  8. **1-year price performance** — anchor closes, monthly path and the computed return

  Every figure is exactly as returned by Yahoo Finance, each labeled with the period it belongs to — no rounding.

- **`.github/workflows/refresh.yml`** — a manually triggered (`workflow_dispatch`) GitHub Actions workflow that checks out the repository and echoes that the pack is current. Run it from the **Actions** tab → **Refresh fundamentals pack** → **Run workflow**.

## Housekeeping

- Notifications for this repository are **muted** (subscription set to *ignore*), so workflow runs will not flood anyone's inbox.
