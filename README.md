# CPSE ETF Portfolio Risk Assessment - Monte Carlo Simulation

## Overview

This project aims to assess the risk of a portfolio comprising 11 stocks from the **CPSE ETF (Central Public Sector Enterprises ETF)**. The ETF primarily focuses on public sector enterprises (PSEs) in India, with an emphasis on the energy sector. The goal is to predict future returns and estimate portfolio risk using **Monte Carlo Simulation**. By generating thousands of potential future outcomes, this method provides a robust way to estimate the probability distribution of portfolio returns and calculate the **Value at Risk (VaR)**.

## Key Characteristics of CPSE ETF

- **Sector Focus:** The CPSE ETF predominantly invests in public sector enterprises in the **energy** sector, including energy production, transmission, and related operations.
- **Government-Backed:** The ETF includes key enterprises that play a significant role in India's energy infrastructure, supported and backed by the government.

## Problem Statement

As part of this analysis, a financial analyst is tasked with assessing the potential risk for a portfolio consisting of 11 stocks from the **CPSE ETF**. The Monte Carlo simulation is used to predict future returns and estimate the risk, helping to understand how the portfolio may perform under various market scenarios.

## Why Monte Carlo Simulation?

Monte Carlo simulation is a **stochastic** method used to model the probability of different outcomes by generating a range of possible scenarios. The simulation accounts for uncertainty in the future by considering factors such as **historical volatility** and **returns**. The key benefits of using Monte Carlo simulation are:

- **Estimation of Portfolio Return Distribution:** The simulation generates a wide range of possible outcomes, helping to understand the potential return distribution.
- **Risk Quantification:** The method allows for the calculation of **Value at Risk (VaR)**, which quantifies potential downside risks by predicting the worst-case returns.

## Portfolio Performance Metrics

The portfolio performance metrics calculated for this analysis are based on the 11 stocks selected from the CPSE ETF.

- **Mean Daily Return:** 0.00178
- **Annualized Mean Return:** 44.77%
- **Daily Volatility (Standard Deviation):** 0.00586
- **Annualized Volatility:** 9.31%

These metrics provide an overall snapshot of the portfolio's return and risk characteristics, serving as inputs for the Monte Carlo simulation.

## Market Scenarios Analyzed

To understand how the portfolio behaves under different market conditions, the analysis includes three potential market scenarios:

### 1. **Market Crash**
- **Mean Return:** -14.82%
- **Standard Deviation:** 0.59%
- **Worst Case Return (5th Percentile):** -15.74%

In a market crash, the portfolio is expected to experience significant losses, with the potential for returns as low as -15.74%.

### 2. **Energy Sector Shock**
- **Mean Return:** 0.16%
- **Standard Deviation:** 0.53%
- **Worst Case Return (5th Percentile):** -0.69%

An energy sector shock leads to a slight reduction in returns, with a potential worst-case return of -0.69%. This scenario helps assess the impact of adverse conditions in the energy sector on the portfolio.

### 3. **Volatility Spike**
- **Mean Return:** 0.09%
- **Standard Deviation:** 1.22%
- **Worst Case Return (5th Percentile):** -1.91%

In the case of a volatility spike, the portfolio faces higher levels of risk, with increased standard deviation and the worst-case return reaching -1.91%.

## Conclusion

This analysis provides a comprehensive view of the CPSE ETF portfolio’s potential behavior under different market shocks. By utilizing Monte Carlo simulation, we can estimate the **probability distribution** of portfolio returns and assess the risk through **Value at Risk (VaR)**, helping guide **risk management strategies** for investors. This approach can be particularly valuable for portfolios with exposure to the energy sector, where volatility can be high and market shocks can have a significant impact.

## Data Used  
- <a href="https://github.com/NikhilChoudhary-93/Road-Safety-Analytics-Project/blob/main/Road%20Accident%20Data.csv">Dataset</a>

## Contact  
For questions or collaboration, reach out via [LinkedIn](https://www.linkedin.com/in/nikhil-choudhary-6163a8263/).
