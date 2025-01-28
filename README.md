# Portfolio Optimization with PyPortfolioOpt

This project explores portfolio optimization using the Python library [PyPortfolioOpt](https://github.com/robertmartin8/PyPortfolioOpt). 
After discovering this library during a DataCamp course, I presented the idea to the manager of the quant team, who showed interest in its application. 
Subsequently, I conducted a demonstration for the quant team on utilizing PyPortfolioOpt to enhance our asset allocation strategies.

## Context

The primary objective of this project was to explore various portfolio optimization methods to propose allocations that meet different criteria, aiming to improve the club's current allocation.
Each team member focused on a specific optimization method. I chose to explore optimization based on Conditional Drawdown at Risk (CDaR).

## Methodology

### PyPortfolioOpt

PyPortfolioOpt is an open-source Python library that implements various portfolio optimization methods, including classical mean-variance optimization techniques and Black-Litterman allocation. 
It offers an intuitive interface for applying these methods to financial data. ([pyportfolioopt.readthedocs.io](https://pyportfolioopt.readthedocs.io))

### Conditional Drawdown at Risk (CDaR)

CDaR is a risk measure that evaluates the average loss beyond a certain drawdown threshold. Introduced by Chekhlov, Uryasev, and Zabarankin in 2000, this approach is similar to Conditional Value at Risk (CVaR) but focuses on drawdowns rather than returns. 
It is particularly useful for managing downside risk in portfolios.

## Implementation

In my approach, I used PyPortfolioOpt to optimize the portfolio based on CDaR. 
I also considered the fees associated with the platform we use to assess the feasibility of regularly reallocating weights based on new information about the club's assets.

## Results

After presenting the project at the end of the term, the team voted on the portfolio optimization method to adopt. 
The weights were reallocated accordingly, taking into account the defined criteria and analyses performed.

## Conclusion

This project allowed for the exploration of applying modern portfolio optimization methods using open-source tools. 
The use of PyPortfolioOpt and the integration of risk measures such as CDaR offer interesting perspectives for improving asset allocation strategies while remaining accessible to club members without a deep mathematical background.
