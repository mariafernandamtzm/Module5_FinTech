# Module5_FinTech

## Description
This project consists of two financial analysis tools built using a single Jupyter notebook:

Financial Planner for Emergencies: This tool allows members to visualize their current savings and determine if they have enough reserves for an emergency fund.

Financial Planner for Retirement: The retirement planner forecasts the performance of a retirement portfolio in 30 years using Monte Carlo simulations based on historical price data obtained via the Alpaca API.

## Technologies Used
Jupyter Notebook
Python
Requests Library
Alpaca SDK
Pandas
MCForecastTools (Monte Carlo simulation library)
Languages
Python

### Part 1: Create a Financial Planner for Emergencies
In this section, we evaluate the cryptocurrency wallet and stock/bond holdings to determine if the member has enough savings for an emergency fund.

Evaluate the Cryptocurrency Wallet by Using the Requests Library:

We collect the current prices for Bitcoin (BTC) and Ethereum (ETH) using the Python Requests library.
Calculate the value of the member's cryptocurrency wallet.
Evaluate the Stock and Bond Holdings by Using the Alpaca SDK:

We make an API call to Alpaca via the Alpaca SDK to get the current closing prices of SPDR S&P 500 ETF Trust (SPY) and iShares Core US Aggregate Bond ETF (AGG).
Calculate the value of the stock and bond portions of the portfolio.
Evaluate the Emergency Fund:

Create a DataFrame to display the composition of the member's portfolio using savings_data.
Determine if the portfolio has enough to create an emergency fund (three times the monthly income).
Part 2: Create a Financial Planner for Retirement
In this section, we use the Alpaca API to get historical closing prices for a retirement portfolio and run Monte Carlo simulations to forecast the portfolio performance in 30 years.

Create the Monte Carlo Simulation:

Make an API call to Alpaca to get 3 years of historical closing prices for a 60/40 portfolio.
Run a Monte Carlo simulation of 500 samples and 30 years for the 60/40 portfolio and plot the results.
Plot the probability distribution and confidence interval.
Generate summary statistics for the Monte Carlo simulation.
Analyze the Retirement Portfolio Forecasts:

Answer questions about the lower and upper bounds for the expected value of the portfolio with a 95% confidence interval.
Forecast Cumulative Returns in 10 Years:

Forecast the cumulative returns for 10 years from now using a 20% bonds and 80% stocks portfolio.
Answer questions about the expected value of the portfolio with the new weights and whether members can retire after only 10 years.
Conclusion

## Conclusion
This Jupyter notebook provides two powerful financial analysis tools for credit union members. The emergency fund planner helps users assess their current savings, while the retirement planner forecasts the performance of their portfolio using Monte Carlo simulations.

By utilizing Python, Requests library, Alpaca API, Pandas, and MCForecastTools, these tools enable better financial planning and decision-making for credit union members, empowering them to make informed choices for their future financial security.
