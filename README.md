### Credit Approval Optimization – Red Ventures Case Study

This project is an end-to-end data science case study modeling credit approval probabilities for three partner lenders using logistic regression, calculating expected revenue, and designing an optimized routing strategy to maximize total approved revenue. The analysis includes data cleaning, exploratory analysis, model building, evaluation, and business recommendations.

### Project Overview

Red Ventures receives loan applications and must decide which lender to route each applicant to.
Each lender has:

Different approval models

Different expected revenue outcomes per approval

Different risk tolerance

Your goal is to build an approval probability model and design a routing framework that maximizes total expected revenue.

### Key Steps

Cleaned and prepared applicant data

Conducted exploratory analysis to understand borrower characteristics

Built logistic regression models to estimate approval probability for each lender

Calculated expected revenue:
expected_revenue = P(approval) × revenue_per_approval

Designed an optimized routing strategy mapping applicants to the lender with the highest expected revenue

Evaluated model performance and business tradeoffs

### Files in Repository
├── 2026__28Candidate_29_Personal_Loans_Case.pdf   # Case prompt
├── Red_Ventures_Case.ipynb                        # Full analysis
├── README.md                                      # Documentation
└── LICENSE                                        # MIT license

### Tools & Libraries

Python

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

Jupyter Notebook

### How to Run

Open the notebook:

jupyter notebook Red_Ventures_Case.ipynb


Run all cells to reproduce:

Data cleaning

Feature preparation

Model training

Optimization logic

Final routing recommendations

### Results Summary

Logistic regression provided stable and interpretable approval probability models

Lender-specific revenue calculations revealed that top-earning lenders were not always the most likely to approve

Optimized routing significantly increased expected total revenue compared to uniform or random assignment

### License

This project is released under the MIT License. See the LICENSE file for details.