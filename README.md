# JPMorgans-Chase-Co-Quantitative-Research-Job-Simulation

## Overview
This repository contains my completed solutions for the JPMorgan Chase Quantitative Research Virtual Job Simulation hosted on Forage.

The project focuses on solving real-world quantitative research and risk analysis problems using Python, data analysis, forecasting, and credit risk modeling techniques.

---

# Tasks Completed

## Task 1 — Natural Gas Price Analysis
- Analyzed historical natural gas price data
- Identified market trends and seasonal patterns
- Built forecasting logic for future price estimation

### Key Insight
Natural gas prices showed seasonal fluctuations where winter months generally experienced higher prices due to increased demand.

---

## Task 2 — Commodity Storage Contract Pricing
Built a pricing model for commodity storage contracts by considering:

- Injection costs
- Withdrawal costs
- Transportation costs
- Storage fees

### Key Insight
Storage profitability depends heavily on market timing and spread between buying and selling prices.

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

### Key Insight
Borrowers with:
- lower FICO scores,
- higher debt,
- and lower income

showed significantly higher default probability.

---

## Task 4 — FICO Score Bucketization
Implemented bucket-based credit risk segmentation using quantile-based FICO score grouping.

### Performed:
- FICO bucket creation
- Default rate calculation
- PD estimation
- Expected Loss calculation

### Expected Loss Formula

```python
Expected Loss = PD × LGD × Loan Amount
```

Where:
- **PD** = Probability of Default
- **LGD** = Loss Given Default

### Key Insight
Expected Loss increases rapidly for high-risk borrowers with large loan exposure.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

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

# Business Applications

These models and techniques are widely used in:

- Banking
- Risk Management
- Credit Underwriting
- Financial Forecasting
- Commodity Trading
- FinTech

---

# Future Improvements

## Credit Risk Model
- Add Logistic Regression evaluation metrics
- Implement Random Forest and XGBoost models
- Add ROC-AUC and Confusion Matrix analysis
- Use SHAP for model explainability

## Natural Gas Forecasting
- Apply ARIMA and Prophet models
- Add advanced time-series decomposition
- Include external economic indicators

## Dashboard & Deployment
- Build Streamlit dashboard
- Deploy ML model using Flask/FastAPI
- Create interactive visual analytics

## Data Engineering
- Automate data pipelines
- Add real-time risk monitoring
- Improve scalability using cloud services

---

# Certificate

Successfully completed the JPMorgan Chase Quantitative Research Job Simulation on Forage. :contentReference[oaicite:0]{index=0}

---

# Author

## Lucky Singh

Aspiring Data Scientist passionate about:
- Machine Learning
- Credit Risk Analytics
- Quantitative Research
- Financial Data Science
