# Lending Club Case Study
> A data-driven approach to improving loan approval processes and minimizing credit losses.

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- **Project Overview**: The study focuses on identifying high-risk loan applicants in an online lending marketplace using data analysis. The aim is to improve risk assessment, reduce credit losses, and refine lending criteria.
- **Business Problem**: 
  - High default rates among borrowers result in significant financial losses.
  - Current loan approval processes are inefficient and lack data-driven insights.
  - Ineffective risk management impacts profitability and sustainability.
- **Dataset**: The analysis is based on a dataset of 39,717 loan records with 111 variables. Key fields include:
  - Loan details (`loan_amnt`, `int_rate`, `term`)
  - Borrower characteristics (`grade`, `sub_grade`, `annual_inc`)
  - Credit history metrics (`pub_rec_bankruptcies`, `last_credit_pull_d`)
  - Loan status and payment details (`loan_status`, `installment`, `last_pymnt_amnt`)

## Conclusions
1. Applicants with lower salaries (e.g., $0–$20K) are more likely to default, while those earning $80K+ are less likely to face charge-offs.
2. Loans with higher interest rates are associated with a greater likelihood of defaults.
3. Risk-prone purposes include loans for "Renewable Energy" and "Small Business."
4. Higher-grade loans (A, B) tend to involve smaller loan amounts and lower interest rates compared to lower-grade loans (C, D, E).
5. Longer loan terms (60 months) carry higher interest rates, reflecting greater associated risks.
6. A risk heatmap was developed to visualize the correlation between loan grades, interest rates, and likelihood of defaults.

## Technologies Used
- Python (e.g., Pandas, NumPy, Matplotlib)
- Jupyter Notebook
- Data visualization tools for EDA

## Acknowledgements
- This project was inspired by challenges faced in the lending industry regarding risk management.
- Data and insights were derived from the Lending Club dataset.
- The analysis was prepared by Rahul Gupta and Kiran Kumar Rao K.

## Contact
Created by:
- Rahul Gupta ([Rahul7185@gmail.com](mailto:Rahul7185@gmail.com))
- Kiran Kumar Rao K ([kirankumarraok@gmail.com](mailto:kirankumarraok@gmail.com))
