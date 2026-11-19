# Canvas Submission Template

**GitHub Repository:** [Paste repository URL after uploading]

**Published Dashboard:** https://michaelguenther-web.github.io/Respoitory-test/

**Company and Ticker:** YETI Holdings Inc. (YETI)

**Selected Option:** American call, $40 strike, November 20, 2026 expiration, 100-share multiplier

**Model Improvement:** Aligned the market inputs to one option-pricing date, added liquidity and multiplier fields, expanded CRR convergence, and added analytic Greeks with independent finite-difference validation and full repricing.

**Primary Analytical Claim:** The option's near-expiration risk is dominated by gamma and daily theta, while rho is economically negligible.

**Most Important Greek:** Theta = -0.0592 per share per calendar day, or -5.92 per contract, holding other inputs constant.

**Measurable Reversal Condition:** Revise the conclusion if a documented strike-specific IV or liquid same-day quote moves the 500-step CRR estimate outside the observed $0.80-$1.20 market range.

**AI-Use Disclosure:** See `AI_USE_DISCLOSURE.md`.
