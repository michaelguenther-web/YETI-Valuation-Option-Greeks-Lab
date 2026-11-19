# YETI Valuation-to-Option Pricing and Greeks Lab

A reproducible FIN Applied Finance artifact extending the prior YETI DCF into scenario payoffs, CRR option pricing, Greeks, numerical validation, approximation testing, and interactive Plotly sensitivities.

## Selected contract
- YETI Nov. 20, 2026 $40 American call
- Valuation date: Nov. 13, 2026
- Spot: $39.42; bid/ask: $0.80/$1.20; IV: 37.9%; risk-free rate: 4.32%
- Multiplier: 100; volume: 129; open interest: 80

## Run
```bash
pip install -r requirements.txt
jupyter notebook valuation_option_lab.ipynb
```
Run all cells from top to bottom. The notebook reads `data/*.csv` and exports `docs/model_results.json`. Open `docs/index.html` to view the dashboard.

## Repository structure
- `valuation_option_lab.ipynb`: completed and executed analysis
- `data/`: company, analyst, and source documentation CSVs
- `docs/`: GitHub Pages dashboard
- `reports/`: memo and numerical output tables
- `original_model/`: preserved original notebook and DCF workbook
- `CHANGELOG.md`: model progression
- `AI_USE_DISCLOSURE.md`: required disclosure

## Important limitations
Analyst targets are 12-month opinions while the option has seven days remaining. The 37.9% input is expiration-level ATM implied volatility, not a verified strike-specific value. The $0.40 spread is wide relative to the $1.00 midpoint. Educational analysis only, not investment advice.
