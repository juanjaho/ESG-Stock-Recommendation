# ESG-Stock-Recommendation
Finding best portfolio weightings based on a predefined set of ESG stocks. Project done for the course "IS453 Financial Analytics" at Singapore Management University. 

## Context
The asset management company you work for, Best Investment Group (BIG), is planning to launch an ESG equity fund that it will offer as an actively managed ETF.  As an financial analytics specialist at the company, you have been assigned to come up with the best portfolio weightings based on a predefined set of ESG stocks. 

## Recommendation methodology
The methodology used to come up with the recommendation is as follows:
1. 30 stocks were selected from the top 100 ESG Stocks list while maintaining the following criteria:
    - Only “A” and “B” SMR Ratings
    - At least 1 stock from each of the 10 industries

2. The risk adjusted return (RAR) of each stock was calculated using the following methods:
    - Sharpe Ratio
    - Treynor Ratio
    - Beta adjusted Sharpe Ratio

3. The highest RAR and lowest Volatility portfolios were selected as candidate portfolios

4. The candidate portfolios were then ranked based on the following criteria:
    - RAR
    - Annualized Return
    - Volatility
    - Excess Kurtosis
    - Beta
    - Correlation

5. Final dicision was then made based on the above criteria and market conditions

## Recommended Portfolio
The recommended portfolio report can be found [here](Recommendation.pdf)



