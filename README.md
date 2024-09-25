# UpGrad: Lending Club Case Study
> Performing Risk analytics in consumer finance to minimize financial losses of loan defaults. With attributes that include customer and loan data, the objective is to find patterns within Exploratory Data Analysis (EDA) which will help predict whether someone will or won't default on a loan. One of the popular use case is to analyze historical loan data, and reduce risk by rejecting risky applications, or lessening terms of loan for high risk borrowers. Deliverables : Python Analysis, Business Insights PowerPoint Deck, GitHub.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
> The goal of this project is to analyze the dataset related to loans so that one can learn and identify various factors responsible for loan defaults. This dataset is a historical loan data from 2007 to 2011 that can be downloaded from Kaggle and contains many attributes of the borrower and their loan outcome. Main Utilization is to use Exploratory Data Analysis (EDA) techniques to find patterns which show higher chances of loan default. These patterns serve as the basis for its loan approval, interest rate and risk management decisions.
>
> ### Business Problem
> The main business task that this project tackles: is to predict who will pay back their loan on time and who will not. Lending money to people who are likely not to repay you is a guaranteed way of financial loss for lending business. Alternately, turning down loans to creditworthy applicants represents forgone business. This project aims to accomplish a balance by pinpointing indicators of loan default, which can aid in a better-informed lending decision, minimize credit loss and optimize loan approval strategies.
>
> ### Business Understanding
> A company specializing in loans for urban customers, and must approve or decline loan applications based on applicant profiles. 
> – The risks of a loan decision can be broken down into two types:
>
> 1. **Credit Loss**: The loss caused by default of the borrower.
> 2. **Business Loss** :A Possible loss of business if a creditworthy applicant is declined loan.
>
> By knowing the drivers of loan default, a company can modify loan terms or refuse high-risk applications, hedging financial risks.

> ### Dataset Overview
> The dataset includes:
> - **Loan Application Details**: Information about the applicants and their loan requests.
> - **Loan Status**: Outcomes such as Fully Paid, Current, and Charged-Off (defaulted).
> - **Applicant Profiles**: Various attributes of the borrowers, which are critical for predicting loan default.
> 
> The dataset covers a time period from 2007 to 2011 and provides a comprehensive view of loan performance and borrower behavior, which is essential for understanding and predicting loan defaults.


## Technologies Used
> - **Python** - Version 3.17
> - **Pandas** - Version 2.1.4
> - **NumPy** - Version 1.26.4
> - **Matplotlib** - Version 3.8.0
> - **Seaborn** - Version 0.13.2
> - **Jupyter Notebook** - Version 7.0.8


## Conclusions
> - Loan amount increases monthly installments increase, loan amount is highly positively correllated with the monthly installment amount.
> - Borrowers with big loan balances have low lifetime payment obligations
> - Higher annual earners generally get approved for larger loans because those applicants look better to lending institutions.
> - Higher Interest Rates = Bigger Installment Payments → ) Monthly Costs for Affected Borrowers >
> - Higher-income households have lower debt-to-income ratios, signaling better financial well-being.
> - Revolving credit utilization Over-the-years is also correlated with higher interest rates because the risk of lending increases as revolving line usage goes up.
> - Public records such as: public record of bankrupcies all are highly relevant to defaulting.
>
> ### Recommendations to Mitigate Charge-offs:
> 1. Include more risk factors such as revolving utilization, public records and debt-to-income ratios for better loan management and credit scoring accuracy.
> 2. Low-risk borrowers can be offered better terms, so interest rates can be lower and repayment periods can shortened to encouraging timely repayment and reduce risk.
> 3. Tightening underwriting thresholds for loans extended to high-risk purpose types, particularly among 'credit card' and 'debt_consolidation' applicants where default rates are elevated.
> 4. Debt management and responsible borrowing are areas that many people struggle with, so invest time in educating those who borrow from your institution to prevent future defaults.
> 5. Provide individualized debt counseling to high-risk borrowers, giving them advice and methods for well-managing their debts in order to avoid defaults.
> 6. Initiate warning signals for customers in financial distress to take corrective action ensuring minimum loan default.
> 7. Homeownership is associated with greater financial stability and reduced probability of loan default so make sure this option is promoted as high as possible.


## Acknowledgements
> - **Data Source**: The loan dataset provided for this analysis from UpGrad.
> - **Educational Resources**: Various online resources and courses that helped in learning EDA and risk analytics techniques.



## Contact
Created by [@sowmilydutta][@shounakdutta]
