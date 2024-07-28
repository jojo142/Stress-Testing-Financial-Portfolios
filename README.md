# Stress Testing Financial Portfolios

### Data Info from Kaggle: https://www.kaggle.com/datasets/camnugent/sandp500/data
S&P 500 Stock Data: The dataset provides historical stock prices for companies in the S&P 500 index over the last five years, aiming to facilitate analysis and model building for potential financial payoff. The dataset was compiled using a script available on GitHub, and it includes updates accounting for changes in the S&P 500 index as of February 2018.

### Content:
Formats: The data is available in two formats:
Merged Data: all_stocks_5yr.csv - contains combined data for all stocks.
Individual Data: individual_stocks_5yr folder - contains separate files for each stock, named by their ticker.

### Columns:
- Date: Stock price date in yy-mm-dd format.
- Open: Opening price of the stock in USD.
- High: Highest price reached during the day.
- Low Close: Lowest price reached during the day.
- Volume: Number of shares traded.
- Name: Stock's ticker symbol.

### Acknowledgements:
- Data Source: Due to volatility in Google Finance, the data was sourced from The Investor's Exchange API.
- Tools Used: Kaggle, GitHub, pandas_datareader, and The Market.

### Inspiration:
- Visualization Opportunities: Users can visualize price changes over time, compare multiple stocks, and generate new metrics.
- Analytical Potential: The dataset allows for the calculation of stock statistics such as volatility and moving averages.
- Challenge: Develop a model that can outperform the market and enable statistically informed trades.

### how I am using the dataset: 

1. Scenario Analysis for Portfolio Stress Testing

Objective: Evaluating the performance of financial portfolios under different economic scenarios.

Approach: Developing models to simulate the impact of various macroeconomic scenarios (e.g., financial crises, interest rate changes) on portfolio returns.


2.  Value at Risk (VaR) and Conditional Value at Risk (CVaR)

Objective: Calculating and compare the Value at Risk (VaR) and Conditional Value at Risk (CVaR) for different portfolios.

Approach: Implementing historical simulation and Monte Carlo simulation techniques to estimate VaR and CVaR.


3. Stress Testing with Factor Models

Objective: Useing factor models to stress test portfolios by simulating the impact of factor movements (e.g., interest rates, inflation) on portfolio returns.

Approach: Implementng multi-factor models (e.g., Fama-French) to analyze the sensitivity of portfolios to different economic factors.


4. Liquidity Risk Assessment in Stress Testing

Objective: Assessing the liquidity risk of portfolios under stressed market conditions.

Approach: Developing models to simulate the impact of liquidity shocks on portfolio performance, considering factors like bid-ask spreads and trading volumes.
