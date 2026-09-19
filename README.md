# Predicting Customer Churn: A Data-Driven Analysis of Subscription Customer Behaviour

IDRA Capstone Project 2026 — Data Science & AI Training Program
**Student:** Qurat Ul Ain | **Enrollment:** IDRA-2026-349978 | **Programme:** Data Science & Analytics

## Overview

This project analyses the IBM Telco Customer Churn dataset (7,043 customers) to identify the
strongest drivers of subscription churn and build a classification model that predicts which
customers are likely to leave. Logistic Regression and Random Forest models are compared; Logistic
Regression is selected as the primary model (79.9% test accuracy, F1 = 57.8%, ROC-AUC = 0.843).

## Repository Structure

```
├── report/
│   ├── Ain_Qurat_Capstone_2026.pdf     # Full research-style report (18 sections + appendices)
│   └── Ain_Qurat_Capstone_2026.docx    # Editable Word version
├── notebook/
│   └── Ain_Qurat_Capstone_Notebook.ipynb   # Full reproducible analysis (Colab-ready)
├── data/
│   └── Telco-Customer-Churn.csv        # Source dataset (IBM Telco Customer Churn)
├── figures/
│   └── fig1 ... fig8 .png              # All charts generated during the analysis
└── README.md
```

## Run the Notebook

Open `notebook/Ain_Qurat_Capstone_Notebook.ipynb` in Google Colab or Jupyter and run all cells —
it downloads the dataset automatically, so no manual setup is required.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/REPLACE_WITH_YOUR_USERNAME/REPLACE_WITH_REPO_NAME/blob/main/notebook/Ain_Qurat_Capstone_Notebook.ipynb)

*(Update the badge link above with your actual GitHub username and repo name once pushed — it will then open the notebook directly in Colab for anyone.)*

## Key Findings

- **Contract type** is the strongest churn driver: month-to-month customers churn at 42.7%, vs 11.3% (one-year) and 2.8% (two-year).
- **Tenure** is strongly protective: churned customers average 18 months tenure vs 37.6 months for retained customers.
- **Higher monthly charges** and **fiber-optic internet** are associated with higher churn.
- The Logistic Regression model achieves 65.3% precision and 51.9% recall on the test set (ROC-AUC 0.843).

## Dataset Source

IBM Telco Customer Churn dataset, distributed via the [plotly/datasets](https://github.com/plotly/datasets) GitHub repository.

## License

Educational capstone project — dataset used under its original open/public terms.
