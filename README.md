Corporate Solvency Analysis & Bankruptcy Prediction
Project Overview
This project performs an in-depth exploratory data analysis (EDA) of the Company Bankruptcy Prediction dataset to identify the microeconomic indicators that signal corporate insolvency. By utilizing a "UBM" (Univariate, Bivariate, Multivariate) structured analytical framework, this project uncovers the structural "Leverage Trap" that leads failing firms toward terminal bankruptcy.

Key Business Objectives
Early Warning: Develop a diagnostic framework to flag companies drifting into high-risk financial zones (Low ROA, High Debt, Low Liquidity).

Risk Mitigation: Provide stakeholders with actionable insights to prevent capital destruction through unsustainable debt-fueled expansion.

Operational Efficiency: Quantify the impact of asset velocity and gross margins on corporate sustainability.

Methodology
The analysis follows a rigorous, production-grade pipeline:

Data Wrangling: Sanitization of 96+ financial metrics, standardization of column headers, and creation of new categorical features (Debt Risk Tiers).

UBM Exploration: - Univariate: Analyzing distributions to identify industry baselines.

Bivariate: Mapping profitability against leverage to uncover "leverage traps."

Multivariate: Systemic correlation and pair plots to define the multi-variable survival boundaries of firms.

Exception Handling: The analysis pipeline includes production-grade error logging and data validation to ensure the notebook is fully executable.

Technologies Used
Language: Python

Libraries: pandas, matplotlib, seaborn, numpy, logging

Key Insights
The Survival Triad: The analysis confirms that bankruptcy is rarely an isolated event; it is the final stage of a systemic collapse in ROA, Debt-to-Equity, and Liquidity.

The Leverage Trap: Companies that mask declining asset efficiency with increased debt are mathematically guaranteed to face negative terminal growth.

Cash Velocity: Even "profitable" firms fail if they cannot convert their assets and inventory into physical cash fast enough to service debt.
