# Multi-Factor-Long-Short-Strategy
A market-neutral, multi-factor long–short strategy on the S&amp;P 100 that consistently outperformed the benchmark in backtests by combining momentum, value, and quality factors into a composite score.

## Methodology (the how ?)

**Data Universe**: S&P 100 stocks (2015–2024) from Yahoo Finance & yfinance fundamentals.

Factor Construction:

1. Value (e.g., inverse P/E)<br>
2. Momentum (12M-1M total return)<br>
3. Quality (low volatility & high profitability)<br>


* Composite Scoring: Ranked each stock on factors, combined using equal weights into a unified score.


* Portfolio Construction: Selected top N ranked stocks monthly, equally weighted.


* Backtesting: Evaluated vs. S&P 100 benchmark with CAGR, Sharpe, and drawdown metrics.




## Key Results (Impact)

a. Achieved annualized return uplift over benchmark with higher Sharpe ratio.<br>
b. Controlled drawdowns through regular rebalancing and diversification.<br>
c. Demonstrated alpha generation from combining complementary factors.<br>



## Real-World Relevance (Why it matters)

This approach mirrors the multi-factor strategies used in asset management and quant equity funds, showing how to integrate different style premia into a disciplined, rules-based investment process.



## Theories used

Quant research workflow: hypothesis → data collection → feature engineering → backtest.
Python stack: pandas, NumPy, matplotlib, yfinance.
Factor investing theory & portfolio management principles.

