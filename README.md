
## Getting Started

This project retrieves Stock prices using a YFinance API and does basic mean variance analysis on stock prices. We implement an ensemble based bootstrap sampling to devise returns, using a betavariate distribution to bias sampling for more recent times. We then create a plot of Sharpe ratio's to allow comparison of all stocks. 

## 
The script includes the following features
- `Correlation Matrix`: Showcases correlation between stock returns to allow for diversification. 
- `Normalized Plot`: Plot showing normalized returns to allow for asset comparison.
- `Financial Analysis`: Provides functionality to retrieve competitors, financials and balance sheets for fundamental analysis.

##
Version 2.0 updates (in process)
- Portfolio creator, a generic mean maximizing variance minimizing function that allocates fractional amounts to construct an efficienct portfolio
- Provide implementation for different sampling techniques.
- Provide confidence intervals for distribution of returns and confidence intervals for means on bootstrap sample.
- Additional Fundamental Analysis including code to compare fundamental ratios - Price / Equity, EPS etc. to rank assets. 

