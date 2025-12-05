[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1c4WKSIM0lEfm8YRTgVGxnVFEc6NSd94O?usp=sharing)
# Portfolio Optimization & Risk Analytics

This repository demonstrates portfolio optimization using Python and Markowitz’s Modern Portfolio Theory (MPT).

## Objective
To construct an optimal investment portfolio that maximizes return for a given level of risk, using historical stock data of leading Indian companies.

## Methodology
- Collected daily price data for major firms such as HDFC Bank, Reliance, Infosys, HUL, Tata Motors, Sun Pharma, and L&T using `yfinance`.
- Calculated daily and annualized returns, volatility, and covariance matrix.
- Simulated 5,000 random portfolios and computed expected return, risk, and Sharpe ratio.
- Identified the optimal portfolio on the Efficient Frontier.


## Objective
To construct an optimal investment portfolio that maximizes return for a given level of risk, using historical stock data of leading Indian companies.

## Methodology
- Collected daily price data for major firms such as HDFC Bank, Reliance, Infosys, HUL, Tata Motors, Sun Pharma, and L&T using `yfinance`.
- Calculated daily and annualized returns, volatility, and covariance matrix.
- Simulated 5,000 random portfolios and computed expected return, risk, and Sharpe ratio.
- Identified the optimal portfolio on the Efficient Frontier.

## Portfolio Optimization Workflow
1. Download stock data (yfinance)
2. Compute returns & volatility
3. Calculate covariance matrix
4. Simulate 5000 portfolios
5. Compute Sharpe ratio
6. Plot Efficient Frontier
7. Find optimal portfolio

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
--------------------------------
1. Download stock data (yfinance)
2. Compute returns & volatility
3. Calculate covariance matrix
4. Simulate 5000 portfolios
5. Compute Sharpe ratio
6. Plot Efficient Frontier
7. Find optimal portfolio

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
