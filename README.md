# Overview
This project analyses the perfomance of loans and generates a loan risk analysis tool.

# Data

The dataset contains 45,000 records of loan applicants, with various attributes related to personal demographics, financial status, and loan details. The dataset can be used for predictive modeling, particularly in credit risk assessment and loan default prediction.

## Dataset Content
The dataset includes 14 columns representing different factors influencing loan approvals and defaults:

### Personal Information

1. person_age: Age of the applicant (in years).
2. person_gender: Gender of the applicant (male, female).
3. person_education: Educational background (High School, Bachelor, Master, etc.).
4. person_income: Annual income of the applicant (in USD).
5. person_emp_exp: Years of employment experience.
6. person_home_ownership: Type of home ownership (RENT, OWN, MORTGAGE).

### Loan Details

1. loan_amnt: Loan amount requested (in USD).
2. loan_intent: Purpose of the loan (PERSONAL, EDUCATION, MEDICAL, etc.).
3. loan_int_rate: Interest rate on the loan (percentage).
4. loan_percent_income: Ratio of loan amount to income.

### Credit & Loan History

1. cb_person_cred_hist_length: Length of the applicant's credit history (in years).
2. credit_score: Credit score of the applicant.
3. previous_loan_defaults_on_file: Whether the applicant has previous loan defaults (Yes or No).

### Target Variable

1. loan_status: 1 if the loan was repaid successfully, 0 if the applicant defaulted.