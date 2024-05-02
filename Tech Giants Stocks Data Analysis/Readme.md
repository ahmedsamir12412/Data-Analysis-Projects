# Project Report
![AdobeStock_456009330_Editorial_Use_Only-1024x614](https://github.com/ahmedsamir12412/Data-Analysis-Projects/assets/90070792/fa3f389b-5fb9-478c-8170-7d1a9ffe7217)


## 📢 Project Overview

This project involved conducting a comprehensive financial analysis of four major technology companies: Apple (AAPL), Amazon (AMZN), Google (GOOGL), and Microsoft (MSFT). The data was in time-series format, recording daily stock price information like opening price, closing price, high, low, and volume.

The objective was to explore these financial time series and calculate relevant measures to understand investment performance, risk, and trading activity. The aim was to provide insights into the companies' financial performance over the examined period, contributing valuable information for making investment decisions.


## 📁 Data Sources

The data utilized in this project was a financial dataset scraped from **yfinance** website. The dataset contains daily stock market data of the four companies was. This dataset included the following columns: 'Ticker', 'Date', 'Open', 'High', 'Low', 'Close', 'Volume', and 'Dividends'.

## 🔨 Tools Used
The data analysis was conducted largely using Python and various Python libraries including:
- **Python**: A programming language used for data manipulation and analysis.
- **Pandas**: A Python library employed for data manipulation and analysis, particularly for structuring and organizing the data into a form suitable for analysis.
- **Matplotlib**: A Python plotting library used for creating static, interactive, and animated visualizations in Python.
- **Seaborn**: A Python data visualization library based on matplotlib that provides a high-level interface for drawing attractive and informative statistical graphics.
## 🔔 Processes
The steps undertaken throughout the project included:

1. **Web Scraping**: We performed a web scraping using  **yfinance** library. to get the desired data.
2. **Loading and Inspecting the Data**: The dataset was loaded into a pandas DataFrame and inspected to understand its structure.
3. **Data Preparation**: The dataset was cleaned up for any aberrations, and the data was cast into appropriate types for computation.
4. **Calculating Financial Metrics**: A series of financial metrics, including median trading volume, maximum single-day price changes, count of new highs and new lows, cumulative returns, compound annual growth rate (CAGR), beta of each ticker, Sharpe Ratio, Sortino Ratio, maximum drawdown, recovery factor, and profit factor, were calculated for each ticker.
5. **Data Analysis**: The calculated metrics were analyzed to generate insights into each ticker's performance, risk profile, and trading activity.
6. **Data Visualization**: We created different types of visualizations and plots to uncover all patterns, relations and trends excisting in our data.
7. **Reporting**: All the insights and findings obtained from the analysis have been presented to stakeholders such as investors and financial analysts in a manner that could help in making data-driven decisions.
 
## 💡 Findings
The findings of the analysis offered valuable insights into several facets of the financial performance of the four tickers:

1. Relative Trading Volume: AAPL and AMZN showed higher trading volumes, indicating more substantial trading activity or liquidity in these stocks compared to GOOGL and MSFT.
2. Moving Average Crossings: MSFT's price showed the highest interaction between its short-term and long-term price movements.
3. Cumulative Returns: AAPL demonstrated the highest cumulative return, followed by MSFT, GOOGL, and AMZN.
4. Compound Annual Growth Rate (CAGR): AAPL also showed the highest CAGR, suggesting it had the highest average annual growth rate during the period analyzed.
5. Risk Measures: Amazon experienced the highest maximum drawdown, suggesting it may have the highest downside risk.
6. Recovery: Despite its largest drawdown, AAPL showed the highest recovery and profit factors, pointing out its efficient capacity to bounce back from losses.
## ⬇️ Recommendations

Analysis of the metrics provided several insights into each ticker's performance and risk profiles over the analyzed period:

- AAPL displayed strong performance regarding cumulative returns and CAGR, paired with good recovery from its maximum drawdown. This might make it a suitable investment for those focused on capital growth and willing to ride the downs.
- AMZN showed lower performance compared to the other companies, but understanding the company's business model, growth plans, and market factors is necessary before making an investment decision based purely on these results.
- Caution would be advised for investors with a low-risk tolerance, given the high maximum drawdowns observed in this analysis, particularly for AMZN.
- Depending on individual investment goals, risk tolerance, and market outlook, a diversified portfolio across these high-performance companies might be an option to consider.

## 🚫 Limitations
 
This analysis was restricted by several limitations:

- First, the absence of a complete timeframe and context for the dataset limited our ability to correlate price movements with specific events or trends in the larger market or sector.
- Secondly, we lacked critical data, such as the S&P 500 index, that would have allowed for a relative performance assessment of individual tickers against a broader market benchmark.
- Finally, this analysis strictly focused on historical price and volume movements. It did not take into account other critical factors such as the companies' earnings, assets, liabilities, macroeconomic indicators, industry competition, future growth prospects, or other fundamental or technical aspects that could influence an investment decision.
