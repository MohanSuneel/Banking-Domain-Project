# Banking Domain - Credit Risk Analysis Insights

Welcome to the Credit Risk Analysis Insights project! This repository is dedicated to unraveling game-changing insights from a dataset associated with credit risk. Here's a glimpse into the transformative discoveries made in this project:

## Business/Domain Understanding

- Financial markets are fundamental institutions in any developing economy, playing a crucial role in promoting economic growth.
- A major concern for financial institutions is credit risk, which, if not managed properly, can lead to a banking collapse.
- Credit risk is the potential that a bank’s borrower or counterparty fails to meet its obligations in repaying the loan borrowed from the financial institutions.
- The study of credit risk is essential for banks to manage risks in their portfolio and assess the success/failure of lending activities.
- Machine learning technology is highly efficient in predicting loan defaulters, reducing Non-Performing Assets.

### What is Credit Risk?

- Credit risk refers to the likelihood that a borrower will fail to meet their obligations in repaying a debt.
- It's the risk that a borrower might default on a loan or be unable to meet their contractual obligations, resulting in financial loss for the lender.
- Managing and assessing credit risk is crucial for both lenders and borrowers.

#### Detailed data description of Credit Risk dataset:

- `person_age`: Age
- `person_income`: Annual Income
- `person_home_ownership`: Home ownership
- `person_emp_length`: Employment length (in years)
- `loan_intent`: Loan intent
- `loan_grade`: Loan grade
- `loan_amnt`: Loan amount
- `loan_int_rate`: Interest rate
- `loan_status`: Loan status (0 is non-default, 1 is default)
- `loan_percent_income`: Percent income
- `cb_person_default_on_file`: Historical default
- `cb_preson_cred_hist_length`: Credit history length

# Task - Exploratory Data Analysis

Assume that you are working as a Data Scientist with one of the world's leading financial institutions. This is an open-ended question. Kindly apply all your knowledge to perform an exploratory data analysis on the given dataset.

#### It is known that the target variable is Loan Status.

However, you are mandatorily supposed to solve the below-mentioned EDA Task for your presentation:

1. Which variables are most significant with respect to the target variable?
2. Explore the data distribution of each column. Identify some important patterns.
3. Insights and Recommendations.

## Key Insights:

🎯 **Age Insights:**
- The dataset revealed a wide age range, from 20 to 144. However, an outlier at 144 was carefully addressed with median imputation.
- The probability of default payment is higher for individuals aged 20 to 28, gradually decreasing as age advances. This highlights the dynamic relationship between age and creditworthiness.

💰 **Loan Amount Implications:**
- Loan amount proved to be a pivotal factor. Borrowers securing loans with higher amounts tend to have a higher default probability.
- As loan amounts exceed a specific threshold, the probability of default decreases. This finding speaks to the importance of loan amount determinations.

💸 **Interest Rates and Borrower Behavior:**
- A high interest rate correlates with a higher probability of borrowers defaulting. This underlines the need for a more comprehensive risk assessment associated with interest rates.
- The density of loan defaulters is linked to higher interest rates as lenders respond to elevated risk.

💡 **Loan Intent Matters:**
- Borrowers intending to use loans for Medical purposes exhibit high default rates.
- Debt Consolidation loans, designed to alleviate debt burdens, also reflect a higher default rate, indicating that borrowers face challenges in managing their obligations.

🔍 **Recommendations for Lenders:**
- Evaluate creditworthiness holistically, considering factors like age, loan amount, and loan intent.
- Tailoring loan terms, interest rates, and financial counseling for borrowers in need can significantly reduce default rates and foster financial well-being.

Feel free to explore the detailed insights provided in the project's documentation. For a more in-depth analysis and additional recommendations, refer to the associated notebooks and data files. If you have any questions or suggestions, please don't hesitate to reach out. Happy exploring!
