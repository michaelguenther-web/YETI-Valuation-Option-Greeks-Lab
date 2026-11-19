# Development History

## Initial Model
The original notebook combined a DCF/comparable valuation, five analyst-informed states, scenario payoffs, and a CRR option lattice. It is preserved in `original_model/valuation_option_lab_original.txt`.

## Model Improvement
The revised model aligns the option quote, stock price, volatility, rate, and maturity to November 13, 2026; adds the contract multiplier and liquidity fields; uses 500 CRR steps for the primary value; retains convergence tests; and explicitly discloses the equity-valuation and analyst-horizon mismatches.

## Module 5 Greeks Extension
Added analytic Black-Scholes Greeks, finite-difference validation, per-contract scaling, delta-only and delta-gamma tests, a combined-factor approximation, full repricing, Greek sensitivity grids, and a Plotly dashboard. For this zero-dividend American call, the European analytic benchmark is appropriate because early exercise should not be economically beneficial.
