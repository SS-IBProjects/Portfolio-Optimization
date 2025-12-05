# Portfolio Optimization & Risk Analytics

This repository demonstrates portfolio optimization using Python and Markowitz’s Modern Portfolio Theory (MPT).

## Objective
To construct an optimal investment portfolio that maximizes return for a given level of risk, using historical stock data of leading Indian companies.

## Methodology
- Collected daily price data for major firms such as HDFC Bank, Reliance, Infosys, HUL, Tata Motors, Sun Pharma, and L&T using `yfinance`.
- Calculated daily and annualized returns, volatility, and covariance matrix.
- Simulated 5,000 random portfolios and computed expected return, risk, and Sharpe ratio.
- Identified the optimal portfolio on the Efficient Frontier.

## Tools Used
Python · pandas · NumPy · matplotlib · seaborn · SciPy · yfinance

## Key Insights
A diversified portfolio balancing Banking, Energy, and IT sectors achieved the best risk-adjusted performance.  
The Efficient Frontier visualization highlights the trade-off between return and volatility.

## Future Work
- Include ESG-weighted portfolios.  
- Integrate macroeconomic indicators like inflation or interest rate data.  
- Develop a Streamlit dashboard for live portfolio tracking.

## How to Run
To install dependencies, run this in the first code cell of the notebook:

```python
!pip install yfinance numpy pandas matplotlib seaborn scipy
```
## Author
**Sanjana Stephen**  
MBA (Finance) | CFA Level I Candidate (Aug 2026)
