# Credit Approval Optimization — Red Ventures Case Study

This project is an end-to-end data science case study modeling credit approval probabilities for three partner lenders using logistic regression, calculating expected revenue, and designing an optimized routing strategy to maximize total approved revenue. The analysis includes data cleaning, exploratory analysis, model development, evaluation, and business recommendations.

---

## **Project Overview**

Red Ventures receives loan applications and must decide which lender to route each applicant to.  
Each lender has different approval behavior and different revenue impacts.

The goals of the project are to:

- Estimate approval probability for each lender  
- Calculate expected revenue per applicant  
- Build an optimized routing strategy that maximizes total expected revenue  

---

## **Key Steps**

- Cleaned and transformed raw borrower data  
- Conducted exploratory analysis to understand feature distributions  
- Built logistic regression approval models for all three lenders  
- Computed expected revenue using:  
  **expected_revenue = probability_of_approval × revenue_per_approval**
- Recommended an optimal routing strategy for maximum revenue  
- Evaluated tradeoffs between approval likelihood and revenue impact  

---

## **Repository Structure**

Red_Ventures_Case.ipynb — Full analysis notebook

README.md — Project documentation

LICENSE — MIT license

2026__28Candidate_29_Personal_Loans_Case.pdf — Original case prompt

---

## **How to Run**

1. Clone the repo  
2. Open `Red_Ventures_Case.ipynb`  
3. Run cells in sequence:
   - Data cleaning  
   - EDA  
   - Logistic regression modeling  
   - Expected revenue calculations  
   - Routing optimization  

---

## **Technologies Used**

- Python  
- pandas  
- numpy  
- scikit-learn  
- matplotlib / seaborn  
- Jupyter Notebook  

---

## **License**

This project is shared for personal and educational use.  
See the **LICENSE** file for details.

