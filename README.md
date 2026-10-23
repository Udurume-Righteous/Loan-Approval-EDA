# Loan Approval EDA

Exploratory data analysis on loan applications. The analysis looks at what drives loan approval and what the business can do to approve more good loans and reduce risk.

## What's in this repo
- `Loan_Prediction_Analysis.ipynb`: the full analysis, covering data cleaning, preprocessing, EDA, insights, recommendations and conclusion
- `train.csv`: 614 past loan applications with the approval decision
- `test.csv`: 367 applications without a decision (used for consistent cleaning only)

## Key findings
- Credit history is the strongest driver of approval: about 80% approval when it meets guidelines, versus about 8% when it does not
- Semiurban applicants have the highest approval rate and the largest share of approved loan value
- Applicants with a co-applicant, married applicants and graduates are approved more often
- Income and loan size have almost no relationship with approval

## Tools used
Python, pandas, matplotlib, seaborn
