# Hugo Hoenn

I build systematic investment strategies and explain them to people who don't write code.
Economics & International Relations at Syracuse (quantitative economics, AI minor), class of 2027. Passed CFA Level I.
Everything below has public code and ends with a section on what the evidence cannot show. Site: **[hugohoenn.com](https://hugohoenn.com)**

| Project | What it is | Headline | Links |
|---|---|---|---|
| **Multi-factor equity strategy** | Value, momentum, quality tilt on the S&P 500, sector- and beta-neutral, built from point-in-time SEC filings and then re-run on 35 years of survivorship-free CRSP/Compustat data | **0.38 IR, t = 2.3** over 1990–2024; the premium came from the 1990s and 2000s and has been flat since 2010 | [repo](https://github.com/hugohoenn/factor-strategy) · [factsheet & dashboard](https://hugohoenn.com/factor/) · [v3 note](https://hugohoenn.com/factor/v3/) |
| **Goldman Sachs QIS product review** | Client-style notes on the QIS team's public funds: the Absolute Return Tracker reverse-engineered, ActiveBeta U.S. Large Cap rebuilt from its rulebook | 10 ETFs explain 89% of GARTX; OOS clone at **2.0% TE / 0.94 corr**. Rulebook recovers **0.40** correlation of GSLC's active returns, stable out of sample | [repo](https://github.com/hugohoenn/gs-qis-review) · [notes](https://hugohoenn.com/review/) |
| **Cross-asset trend & carry program** | 21 equity, bond, FX and commodity markets; vol targeting, risk parity, costs; benchmarked against GS Managed Futures Strategy; ML overlay tested under purged walk-forward validation | **0.41 Sharpe, −21% max DD, −0.15 corr to S&P 500**, positive in 2008/2020/2022. The ML overlay lost to the rule (IC 0.03 vs 0.06) and is reported as such | [repo](https://github.com/hugohoenn/macro-program) · [note](https://hugohoenn.com/macro/) |
| **Fund X-ray** | Interactive returns-based analysis of 45 funds: ETF exposures, Kalman-filtered drift, Fama-French tilts, OOS clone tracking error, fee-vs-clone gap, plain-English readouts | Every public GS QIS product included | [open it](https://hugohoenn.com/xray/) · [code](https://github.com/hugohoenn/gs-qis-review/blob/main/src/xray.py) |

**Stack:** Python (pandas, NumPy, statsmodels, scikit-learn, Plotly), SEC EDGAR XBRL, CRSP/Compustat via WRDS, Fama-French data library.
**Contact:** hhoenn@syr.edu · [LinkedIn](https://www.linkedin.com/in/hugohoenn)

*Independent research for discussion. Not investment advice. Not affiliated with Goldman Sachs or any fund sponsor.*
