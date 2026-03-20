# financial-market-analysis-gmm
Financial Market Analysis & Predictive Modeling
Overview

This project analyzes the key drivers of firm valuation using panel data for NIFTY 100 companies. The goal was to understand how operational efficiency and firm characteristics impact market capitalization growth using econometric modeling.

Dataset

Source: Bloomberg L.P. Terminal

Coverage: 100 firms (NIFTY 100)

Structure: Panel data with time-series observations

Features: Market cap, energy intensity, firm size, and derived lag variables

Methodology

Data processing and feature engineering using Python (programming language) (pandas)

Panel regression with firm fixed effects

Applied Generalized Method of Moments (GMM) to address endogeneity

Created lag-based variables to capture temporal relationships

Key Findings

Overall models were statistically significant (p < 0.05)

Energy efficiency showed a consistent relationship with firm valuation (significant at 5–10% levels)

Firm size emerged as a strong predictor (p < 0.01, positive impact on growth)

Results highlight how operational efficiency and scale influence market performance

Key Takeaways

Data-driven modeling can uncover hidden drivers of firm value

Accounting for endogeneity (via GMM) improves reliability of insights

Combining financial + operational metrics leads to better predictive understanding

Tech Stack

Python (pandas, numpy, statsmodels)

Bloomberg Terminal

Jupyter / Google Colab

Future Improvements

Expand to mid-cap and small-cap firms

Incorporate additional ESG and macroeconomic variables

Build a predictive dashboard for real-time insights
