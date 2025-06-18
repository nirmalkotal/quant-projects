# Quant Projects:

---


## 1. 📉 Value at Risk Estimation and Backtesting: Integrating Extreme Value Theory and GARCH Models

- This project builds a comprehensive market risk modeling framework using a SENSEX-weighted portfolio. It includes:
  - VaR estimation using Historical Simulation, Variance-Covariance, Monte Carlo, GARCH, EVT, and GARCH+EVT
  - Backtesting with Violation Ratio, Kupiec Test, and Basel Traffic Light framework
  - Tail risk modeling using Generalized Pareto Distribution (GPD) and Extreme Value Theory (EVT)

- Scenarios Covered: Normal market (2021–2022) and stressed market (COVID-19 crash, 2019–2020)

- Models used: Normal VaR, GARCH(1,1), EVT (GPD), Monte Carlo

- Metrics: Violation Count, Violation Ratio, Kupiec p-value

- Also includes return distribution fitting, mean excess analysis, and EVT-based risk calibration.

- Tools: Python, NumPy, pandas, matplotlib, seaborn, arch, scipy, statsmodels



🔗 **Resources**:  [📄 Report in PDF](https://github.com/nirmalkotal/quant-projects/blob/main/value_at_risk/VaR-sensex.pdf) | [📓 Jupyter Notebook](https://github.com/nirmalkotal/quant-projects/blob/main/value_at_risk/VaR-sensex.ipynb) | [📁 Folder](https://github.com/nirmalkotal/quant-projects/tree/main/value_at_risk)

---

## 2. 📉 Extreme Value Theory and GARCH-EVT-Based VaR Modeling of NIFTY 50 Returns:

This project develops a GARCH-EVT framework to estimate and validate Value at Risk (VaR) for NIFTY 50 returns. Heavy tails are captured via the Generalized Pareto Distribution, while GARCH models short-term volatility clustering. Backtesting shows GARCH-EVT outperforms pure EVT, with a violation ratio near 1 and a Kupiec test p-value of 0.901.

🔗 **Resources**:  [📄 Report in PDF](https://github.com/nirmalkotal/quant-projects/blob/main/extreme_value_theory/evt_var.pdf) | [📓 Jupyter Notebook](https://github.com/nirmalkotal/quant-projects/blob/main/extreme_value_theory/evt_var.ipynb) | [📁 Folder](https://github.com/nirmalkotal/quant-projects/tree/main/extreme_value_theory)

---


## 3. 📊 Credit Risk Classification Using Machine Learning on the German Credit Dataset

Built and evaluated supervised machine learning models: Logistic Regression, SVM, Random Forest, XGBoost, and KNN and to classify credit risk (good vs. bad credit) using the German Credit dataset. The project includes EDA, model performance comparison via cross-validation and train-test split, and ROC AUC-based evaluation. Ensemble methods and linear models were found to outperform KNN, with Logistic Regression offering the best overall consistency.

🔗 **Resources**: [📄 Report in PDF](https://github.com/nirmalkotal/quant-projects/blob/main/credit-risk-classification/credit_risk_classification.pdf) | [📓 Jupyter Notebook](https://github.com/nirmalkotal/quant-projects/blob/main/credit-risk-classification/credit_risk_classification.ipynb) | [📁 Folder](https://github.com/nirmalkotal/quant-projects/tree/main/credit-risk-classification)

---

## 4. 📉 Calibrating the Implied Volatility Surface of NIFTY Options

Calibrated NIFTY option implied volatility surface using polynomial regression on log-moneyness and maturity. Computed IV via Black-Scholes with Newton-Raphson, optimized model degree using k-fold cross-validation, and visualized 3D surface. Conducted residual diagnostics capturing volatility skew, term structure, and nonlinear effects.

🔗 **Resources**: 📄 [Report in PDF](https://github.com/nirmalkotal/quant-projects/blob/main/volatility_skew/volatility%20surface%20calibration.pdf) | 📓 [Jupyter Notebook](https://github.com/nirmalkotal/quant-projects/blob/main/volatility_skew/volatility%20surface%20calibration.ipynb) | 📁 [Folder](https://github.com/nirmalkotal/quant-projects/tree/main/volatility_skew)

---


## 5. 📉 Optimal Portfolio Construction Based on Modern Portfolio Theory: Outperforming the Benchmark Index

This project applies Modern Portfolio Theory (MPT) to construct optimal 10-stock portfolios from the BSE Sensex constituents (2012–2025). Using Monte Carlo simulations and a rolling window backtesting framework (2-year training, 1-year testing), the project identifies portfolios that maximize the Sharpe ratio and consistently outperform the benchmark index (Sensex).

🔗 **Resources**: [📄 Report in PDF](https://github.com/nirmalkotal/quant-projects/blob/main/modern_portfolio_theory/optimal_portfolio.pdf) | [📓 Jupyter Notebook](https://github.com/nirmalkotal/quant-projects/blob/main/modern_portfolio_theory/optimal_portfolio.ipynb) | [📁 Folder](https://github.com/nirmalkotal/quant-projects/tree/main/modern_portfolio_theory)

---

## 6. 📉 European Option Pricing and Variance Reduction Techniques:

Implemented Black-Scholes, Binomial Tree, and Monte Carlo methods for pricing European options. Analyzed error convergence and runtime trade-offs, and applied variance reduction techniques: Antithetic Variates and Control Variates, to improve Monte Carlo efficiency while maintaining pricing accuracy.

🔗 **Resources**:  [📄 Report in PDF](https://github.com/nirmalkotal/quant-projects/blob/main/european_option_pricing/European%20option%20pricing%20and%20variance%20reduction.pdf) | [📓 Jupyter Notebook](https://github.com/nirmalkotal/quant-projects/blob/main/european_option_pricing/European%20option%20pricing%20and%20variance%20reduction.ipynb) | [📁 Folder](https://github.com/nirmalkotal/quant-projects/tree/main/european_option_pricing)

---


## 7. 📉 Yield Curve Modeling, Bond Portfolio Risk, and Recession Forecasting using US Treasury Data:

Modeled US Treasury yield curves using Nelson-Siegel and spline methods; evaluated bond portfolio risk (DV01, duration, convexity), time series analysis of spread (difference of 10Y and 2Y bond yield), and built machine learning models to forecast US recessions using macro-financial data.
Key results: Cubic spline outperformed Nelson-Siegel (RMSE: 0.045 vs 0.091); portfolio metrics showed DV01 1.43/bp with Duration 6.56y and 99% VaR 18.44; ARIMA(3,1,0) achieved optimal spread forecasting (RMSE: 0.024). Logistic regression recession model achieved 84% recall and 88% AUC with residential investment and spread as the most predictive features.


🔗 **Resources**:  [📄 Report in PDF](https://github.com/nirmalkotal/quant-projects/blob/main/yield-curve-framework/yield_curve_recession.pdf) | [📓 Jupyter Notebook](https://github.com/nirmalkotal/quant-projects/blob/main/yield-curve-framework/yield_curve_recession.ipynb) | [📁 Folder](https://github.com/nirmalkotal/quant-projects/tree/main/yield-curve-framework)

---

## 8. 📊 Credit Risk Modeling Using LendingClub Data: A Comprehensive Framework for PD, LGD, EAD, and Scorecard Development

This project builds a full credit risk modeling pipeline using LendingClub loan data. It includes:
- *PD, LGD, EAD modeling*
- *Expected Loss & Credit VaR estimation*
- *Scorecard development with WOE & logistic regression*

Models used: Logistic Regression, Random Forest, XGBoost  

Metrics: AUC, Brier Score, RMSE

Also includes simulation of portfolio losses and cutoff-based approval policy.

Tools: Python, scikit-learn, xgboost, scorecardpy, matplotlib, seaborn

🔗 **Resources**: [📄 Report in PDF](https://github.com/nirmalkotal/quant-projects/blob/main/credit-risk-modeling/credit_risk_modeling.pdf) | [📓 Jupyter Notebook](https://github.com/nirmalkotal/quant-projects/blob/main/credit-risk-modeling/credit_risk_modeling.ipynb) | [📁 Folder](https://github.com/nirmalkotal/quant-projects/tree/main/credit-risk-modeling)


