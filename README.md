#  Options Pricing Engine — Black-Scholes + Monte Carlo

> Quantitative Finance project replicating core pricing tools used at Goldman Sachs, BNP Paribas & JPMorgan.

##  Overview
Full options pricing engine built in Python with real market data (AAPL).

##  Features
- **Black-Scholes** pricing for European calls & puts
- **Monte Carlo** simulation (50,000+ paths, antithetic variates)
- **Greeks** — Delta, Gamma, Vega, Theta, Rho
- **Implied Volatility** extraction via Brent numerical method
- **3D Volatility Surface** (interactive Plotly)
- **Options strategies** P&L — Bull Spread, Straddle, Risk Reversal
- **Sensitivity heatmap** — price vs spot & volatility

##  Tech Stack
`Python` `NumPy` `SciPy` `Pandas` `Matplotlib` `Plotly` `yfinance`

##  Run it
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/clemenconhector-glitch/options-pricing-engine/blob/main/Options_Pricing_BlackScholes_MonteCarlo.ipynb)
