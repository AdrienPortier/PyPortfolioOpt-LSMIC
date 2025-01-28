# PyPortfolioOpt-LSMIC

## Introduction

This project was carried out as part of the **LSM Investment Club** (LSMIC), independently, and presented to the **quant team**, which oversees the management of a portfolio exceeding €25,000.

The main objective of this project was to explore and implement portfolio optimization techniques using the **PyPortfolioOpt** library. After discovering this library during a DataCamp training, I presented a demonstration to the quant team, highlighting its practical application for optimizing portfolio allocations.

The project was conducted alongside academic commitments and culminated in a final presentation to all club members, where the club members voted on the most appropriate optimization method for reallocating portfolio weights.

## Objectives

- Utilize the **PyPortfolioOpt** library to optimize portfolio allocations.
- Explore risk metrics and optimization criteria, with a focus on **Conditional Drawdown at Risk (CDaR)**.
- Present the results in an intuitive manner to accommodate members without a technical background.
- Incorporate platform fees into the analysis to evaluate the feasibility of regular reallocations.

## Technologies Used

- **Main Language**: Python
- **Key Libraries**:
  - `pandas`: Data manipulation.
  - `numpy`: Numerical computations.
  - `scipy`: Optimization algorithms.
  - `cvxpy`: Convex optimization for financial applications.
  - `PyPortfolioOpt`: Portfolio optimization.

## Key Files

- **`PyPortfolioOpt_Demo.ipynb`**: A notebook demonstrating the functionalities of the PyPortfolioOpt library. This includes mean-variance optimization, Black-Litterman allocation, and other techniques.
- **`CDaR_Optimization.ipynb`**: A notebook dedicated to implementing portfolio optimization based on Conditional Drawdown at Risk (CDaR). This includes testing various scenarios and analyzing the results.

## Key Results

### PyPortfolioOpt Analysis

The **PyPortfolioOpt** library was used to implement CDaR optimization, among other methods. This technique evaluates portfolio performance based on average drawdown beyond a specified threshold, providing insights into downside risks.

### CDaR Optimization

- CDaR was chosen for its ability to quantify risks related to large portfolio drawdowns.
- Various allocation scenarios were tested, comparing potential returns against defined risk levels.

### Practical Considerations

In addition to pure optimization, platform fees were integrated into the analysis. The goal was to determine if reallocating portfolio weights regularly would remain cost-effective given transaction fees and updated market information.

## Critiques and Limitations

- **CDaR Suitability**: While effective in risk-sensitive contexts, CDaR is not always the most intuitive measure for long-term portfolio management.
- **Optimization Assumptions**: Like most financial models, the effectiveness of CDaR depends on the validity of input data and assumptions, such as stationarity of returns.
- **Transaction Costs**: Frequent reallocations may erode returns, particularly for smaller portfolios.

## Contributor

- **Adrien Portier** ([LinkedIn](https://www.linkedin.com/in/adrien-portier/))

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/AdrienPortier/PyPortfolioOpt-LSMIC.git
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the notebooks:
   - `PyPortfolioOpt_Demo.ipynb` for an introduction to PyPortfolioOpt.
   - `CDaR_Optimization.ipynb` for the CDaR-specific analysis.

