## TCS Financial Model — 3-Statement Model + DCF Valuation

A fully integrated three-statement financial model for **Tata Consultancy Services (TCS)**, built from FY24–FY26 annual report data, with a 5-year forecast (FY27E–FY31E) and DCF-based equity valuation.

### What's inside
- **P&L, Balance Sheet, Cash Flow** — fully linked, with a balance-check row confirming Assets = Equity & Liabilities across all periods
- **Supporting schedules** — PPE roll-forward, ROU assets, intangibles, and equity, so the core statements pull from auditable sub-schedules rather than hardcoded plugs
- **Revenue build** — driven by headcount × revenue-per-employee, rather than a flat top-line growth assumption
- **DCF valuation** — FCFE discounted at Cost of Equity (CAPM-based), with a Gordon Growth terminal value and a two-variable sensitivity table (Cost of Equity × Terminal Growth Rate)

### Methodology notes
- All hardcoded assumptions are color-coded (blue) and sourced via cell comments (e.g., risk-free rate, beta, market risk premium)
- Formulas (black) and cross-sheet links (green) follow standard financial modeling color conventions
- Model recalculates cleanly with **zero formula errors**

### Key assumptions
| Driver | Assumption |
|---|---|
| Revenue growth | Headcount growth + revenue/employee growth |
| Dividend payout | Ramps from ~80% to 92% over the forecast |
| Terminal growth rate | 4.5% |
| Cost of Equity | ~11.7% (CAPM) |

### File
- `TCS_Financial_Model.xlsx` — the full model (Excel)

### Disclaimer
Built for educational/portfolio purposes as part of an MBA Finance specialization. Not investment advice.
