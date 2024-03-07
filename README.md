# Apple-Stock-Analysis

I performed Apple Stock Analysis for the year 2022 by importing the necessary libraries, including Yahoo finance, pandas, matplotlib, and numpy, for financial analysis using Python. 

# EDA
The data includes columns such as open, high, low, close, volume, and adjusted close, but the focus is on the adjusted close as it provides valuable insights. To calculate the daily returns, a new column is created using the adjusted close column, representing the percentage change in stock price day over day. 
The daily returns are then plotted using matplotlib. Moving on to quantity metrics, the 50-day moving average is calculated and a new column is created for it.
The last entries of the 50-day moving average column are displayed, and a visualization is created showing both the adjusted close and the 50-day moving average for Apple's stock price.

![Screen Shot 2024-03-07 at 17 19 10](https://github.com/kphanipramod/Apple-Stock-Analysis/assets/118381849/3272838a-9103-44de-b550-00dfc6f98c79)


# Calibrating the Volatility of the Stock price and the Sharpe ratio
Volatility is defined as a measure of dispersion of returns, indicating higher risk but potentially higher rewards. 
The daily return standard deviation is used to calculate volatility, with a higher number indicating higher volatility. 
The Sharpe ratio measures the performance of an investment in relation to a risk-free asset, adjusting for risk. A higher Sharpe ratio indicates better risk-adjusted returns. 
The calculation of Sharpe ratio using a risk-free rate of one percent and the mean of daily returns. The annual volatility is also calculated using the standard deviation of daily returns. 
The resulting value of the Sharpe ratio for Apple stock indicates a bad performance with a downward movement in stock prices. The next topic discussed is Beta, which measures a stock's volatility compared to the market. 
However, calculating beta requires S&P 500 data, which is downloaded from Yahoo Finance.
Daily returns, also known as percent change, is a common measure used in financial analysis. Concatenated the daily returns of the Apple stock and the S&P 500 index and then calculated the beta, which represents the risk of the Apple stock compared to the market. 

![Screen Shot 2024-03-07 at 17 18 54](https://github.com/kphanipramod/Apple-Stock-Analysis/assets/118381849/1ee6dd87-7637-4868-a70e-096b289f0b90)

