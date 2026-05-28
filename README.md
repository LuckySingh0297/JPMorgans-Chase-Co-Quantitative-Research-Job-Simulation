# JPMorgans-Chase-Co-Quantitative-Research-Job-Simulation

## Overview

This repository contains my completed solutions for the **JPMorgan Chase Quantitative Research Virtual Job Simulation** hosted on Forage.

The project focuses on solving real-world quantitative research, financial analysis, time series forecasting, and credit risk modeling problems using Python and data science techniques.

---

# Tasks Completed

## Task 1 — Natural Gas Price Analysis & Forecasting

Performed exploratory analysis and forecasting on historical natural gas prices using Time Series Analysis techniques.

### Work Done
- Cleaned and analyzed historical gas price data
- Identified trends and seasonal behavior
- Estimated future prices
- Applied interpolation and forecasting techniques
- Visualized price movement patterns

### Time Series Concepts Used
- Trend Analysis
- Seasonal Analysis
- Forecasting
- Interpolation
- Exponential Smoothing

### Key Insights
- Natural gas prices showed strong seasonal fluctuations
- Winter months generally had higher prices due to increased demand
- Time series forecasting helps companies make better trading and storage decisions

---

## Task 2 — Commodity Storage Contract Pricing

Built a pricing model for commodity storage contracts.

### Factors Included
- Injection costs
- Withdrawal costs
- Transportation costs
- Storage fees

### Key Insights
- Storage profitability depends heavily on market timing
- Profit opportunities increase when future prices are significantly higher than current prices
- Storage valuation is important in energy trading and risk management

---

## Task 3 — Credit Risk Modeling

Developed a Probability of Default (PD) prediction system using borrower financial information.

### Features Used
- Credit lines outstanding
- Loan amount outstanding
- Total debt outstanding
- Income
- Years employed
- FICO score

### Process
- Data preprocessing
- Feature scaling
- Model prediction
- Probability estimation

### Key Insights
Borrowers with:
- lower FICO scores,
- higher debt,
- lower income,
- and larger loan exposure

showed significantly higher default probability.

---

## Task 4 — FICO Score Bucketization & Expected Loss

Implemented FICO score segmentation and Expected Loss estimation.

### Work Done
- Created quantile-based FICO buckets
- Calculated default rate per bucket
- Estimated Probability of Default (PD)
- Calculated Expected Loss

### Expected Loss Formula

```python
Expected Loss = PD × LGD × Loan Amount
```

Where:
- **PD** = Probability of Default
- **LGD** = Loss Given Default

### Key Insights
- Lower FICO score buckets had higher default rates
- Expected Loss increased rapidly for risky borrowers
- Bucketization simplifies credit risk segmentation for banks

---

# Technologies Used

## Programming & Analysis
- Python
- Pandas
- NumPy

## Visualization
- Matplotlib

## Machine Learning
- Scikit-learn

## Time Series Forecasting
- Exponential Smoothing
- Interpolation
- Trend & Seasonal Analysis

## Development Environment
- Jupyter Notebook

---

# Business Applications

These techniques are widely used in:

- Banking
- Quantitative Research
- Risk Management
- Credit Underwriting
- Financial Forecasting
- Commodity Trading
- FinTech

---

# Project Structure

```bash
├── loan.ipynb
├── Nat.ipynb
├── Nat_Gas.csv
├── Loan_Data.csv
├── README.md
```

---

# Major Learnings

Through this project, I learned:

- How financial institutions estimate risk
- How Probability of Default models work
- How Expected Loss is calculated
- How FICO scores impact lending decisions
- How Time Series forecasting works in energy markets
- How quantitative research is applied in real-world finance

---

# Future Improvements

## Credit Risk Model
- Add Logistic Regression evaluation metrics
- Implement Random Forest and XGBoost models
- Add ROC-AUC analysis
- Use SHAP for explainability
- Improve feature engineering

## Time Series Forecasting
- Implement ARIMA and Prophet models
- Add advanced forecasting techniques
- Include external economic indicators
- Improve seasonal decomposition

---

# Certificate

Successfully completed the **JPMorgan Chase Quantitative Research Job Simulation** on Forage. :contentReference[oaicite:0]{index=0}

---

# Author

## Lucky Singh

Aspiring Data Scientist passionate about:
- Quantitative Research
- Machine Learning
- Credit Risk Analytics
- Financial Data Science
- Time Series Forecasting
