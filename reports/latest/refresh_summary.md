# Data refresh 15 Oct 2026

Run `20261015-105328` · as of **2026-09**

## Headline

Composite misalignment +15.7% → **+15.7%** (2026-09 → 2026-09); fair value 82.50 → **82.50**; spot 95.41 → 95.41. Change in the ECT by component: REER component -0.0pp, FEER +0.0pp.

## Gates

- All hard gates passed.
- warning: MOSPI CPI ends Aug 2026 in both the RBI API and data/raw/manual/mospi_cpi_2024base.csv; Sep 2026 should be out. If the API lags, add it from https://www.mospi.gov.in/themes/product/9-consumer-price-index-cpi (Annexure IV).
- warning: REER anchor fundamentals are not cointegrated with the REER (Engle-Granger p=0.85); the anchor is reported, not relied on.
- warning: BEER residuals are not cointegrated (Engle-Granger p=0.97); treat the BEER fair value as descriptive.

## Data changes

| File | New obs | New range | Revised | Largest revision | Lost |
|---|---|---|---|---|---|
| fred/CPIAUCSL.csv | 1 | 2026-09–2026-09 | 0 |  | 0 |
| fred/DCOILBRENTEU.csv | 5 | 2026-09–2026-10 | 0 |  | 0 |
| fred/DTWEXBGS.csv | 10 | 2026-09–2026-10 | 0 |  | 0 |
| fred/VIXCLS.csv | 9 | 2026-10–2026-10 | 0 |  | 0 |
| fred/WALCL.csv | 1 | 2026-10–2026-10 | 0 |  | 0 |
