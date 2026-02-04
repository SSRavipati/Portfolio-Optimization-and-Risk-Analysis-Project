# Portfolio-Optimization-and-Risk-Analysis-Project
Portfolio Optimization and Risk Analysis Project
Executive Summary
This project demonstrates a robust quantitative approach to modern portfolio theory (MPT) by analyzing the historical performance and risk-return profiles of a diversified multi-asset portfolio. Using a dataset spanning from late 2018 through late 2023, I constructed a Co-Variance Matrix and developed an Efficient Frontier model to optimize asset allocation across varying risk tolerances.

The analysis focuses on three distinct tickers representing different market sectors: BRK.B (Financials/Conglomerate), NKE (Consumer Discretionary), and TTE (Energy).

Technical Competencies Demonstrated

Quantitative Modeling: Construction of Co-Variance and Correlation matrices to understand inter-asset relationships.


Portfolio Optimization: Development of 11 distinct portfolio iterations (PF2 through MAX RET PF) to identify the optimal risk-return tradeoff.


Risk Metrics: Calculation of expected returns, standard deviation (volatility), and portfolio risk.


Data Visualization: Created dynamic charts and dashboards (via Excel/VBA) to visualize the Efficient Frontier and asset weightings.



VBA Automation: Utilized Macro-enabled workbooks (.xlsm) to streamline complex financial calculations and data processing.


Data Insights & Financial Analysis
1. Asset Performance Metrics
Based on the five-year historical period, the individual asset profiles were identified as: | Asset | Mean Monthly Return | Volatility (St. Dev) | | :--- | :--- | :--- | | TTE | 1.12% | 9.06% | | BRK.B | 1.06% | 5.91% | | NKE | 1.04% | 8.60% |


Insight: While TTE offered the highest individual returns, BRK.B provided the most stability, serving as the foundational low-volatility anchor for the portfolio.

2. Portfolio Optimization (The Efficient Frontier)
By shifting weightings between the assets, I identified the Minimum Variance Portfolio and the Maximum Return Portfolio:


Minimum Variance (PF2): Prioritizes capital preservation with a risk profile of 25.8% and a monthly return of 1.06%.


Maximum Return: Aggressively weighted toward TTE, yielding a monthly return of 1.11% but increasing risk to 40.5%.

3. Co-Variance & Correlation
The model highlights how diversification reduces unsystematic risk. The positive but varied co-variance between NKE and TTE (0.058) versus BRK.B and TTE (0.059) allowed for strategic rebalancing to optimize the Sharpe ratio (risk-adjusted return).

Project Structure

Data Engine: Comprehensive monthly return tracking from November 2018 to November 2023.

Analytical Layers:


Sheet 5: Core calculations for the Co-Variance matrix and portfolio weighting.


Charts: Visual representation of the Efficient Frontier and historical price action.



VBA: Backend automation for iterative testing of portfolio weights.

Strategic Recommendations
As an analyst, I would use this model to advise stakeholders based on market cycles:


Defensive Stance: Shift weight toward PF2 during high-volatility periods (e.g., matching the volatility seen in early 2020) to maintain a return of ~1.05% while minimizing drawdown.


Growth Stance: Increase exposure to the TTE-heavy Max Return portfolio during energy sector upswings to capture the higher mean return of 1.11%
