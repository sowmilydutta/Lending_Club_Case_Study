# UpGrad: Lending Club Case Study
> This project focuses on risk analytics in consumer finance which aims to minimize financial losses from loan defaults. Using Exploratory Data Analysis (EDA), the goal is to identify patterns in loan and customer attributes that predict default risk. By analyzing historical loan data, the company can improve its decision-making process by rejecting risky applications or adjusting loan terms for high-risk borrowers. The deliverables include a well-documented Python analysis, insights presented in a business-friendly format, and a GitHub repository containing all relevant files for review and reproducibility.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
> This project involves analyzing a loan dataset to understand and identify factors contributing to loan defaults. The dataset includes historical loan data from 2007 to 2011, detailing various attributes of borrowers and their loan outcomes. The primary goal is to leverage Exploratory Data Analysis (EDA) techniques to uncover patterns that indicate a higher risk of loan default. By identifying these patterns, the company can make informed decisions on loan approvals, interest rates, and risk management strategies.

> ### Business Problem
> The primary business problem addressed by this project is the identification of risky loan applicants who are likely to default on their loans. In the lending business, approving loans to high-risk applicants can lead to significant financial losses. Conversely, denying loans to creditworthy applicants results in missed business opportunities. This project seeks to strike a balance by identifying key indicators of loan default, which can help in making more informed lending decisions, reducing credit loss, and optimizing loan approval strategies.

> ### Business Understanding
> The company specializes in offering various types of loans to urban customers and must decide on loan approvals based on applicant profiles. The two types of risks associated with loan decisions are:
> 1. **Credit Loss**: Loss incurred if a borrower defaults on repayment.
> 2. **Business Loss**: Loss of potential business if a creditworthy applicant is denied a loan.
>
> Understanding loan default drivers helps mitigate financial risks by allowing the company to adjust loan terms or reject high-risk applications.

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
> - Larger loan amounts result in higher installment payments, showing a strong positive correlation between loan amount and monthly installments.
> - Borrowers with larger loans have higher total payment obligations over the loan’s lifetime.
> - Applicants with higher annual incomes typically secure larger loans due to perceived repayment ability.
> - Higher interest rates lead to larger installment payments, increasing monthly costs for affected borrowers.
> - Individuals with higher incomes tend to maintain lower debt-to-income ratios, indicating better financial health.
> - Higher revolving credit utilization correlates with increased interest rates, reflecting greater lending risk.
> - Public records, such as public record of bankrupcies, are strongly linked to a higher likelihood of default.
>
> ### Recommendations to Mitigate Charge-offs:
> 1. *Enhance Credit Scoring Models*: Integrate additional factors such as revolving utilization, public records, and debt-to-income ratios to improve risk assessment and credit scoring accuracy.
> 2. *Tailor Loan Terms*: Offer more favorable terms, such as lower interest rates and shorter repayment periods, to low-risk borrowers to incentivize timely repayment and minimize risk exposure.
> 3. *Strengthen Underwriting Criteria*: Tighten approval thresholds for loans issued for high-risk purposes, particularly for 'small_business' and 'debt_consolidation' applicants, where default rates are elevated.
> 4. *Provide Financial Literacy Programs*: Equip borrowers with essential financial education to enhance their understanding of debt management and responsible borrowing, reducing default rates over time.
> 5. *Expand Debt Counseling Services*: Offer personalized debt counseling to at-risk borrowers, providing guidance and strategies to manage debt effectively and avoid defaults.
> 6. *Implement Proactive Risk Management*: Deploy early intervention systems to identify borrowers displaying early signs of financial distress, enabling timely corrective measures to prevent defaults.
> 7. *Promote Homeownership*: Encourage homeownership as it has been shown to enhance financial stability and reduce the likelihood of loan default.
> 8. *Bolster Verification Processes*: Tighten the verification of borrower information to minimize the risk of extending credit to fraudulent or misrepresented applicants, thus reducing default incidences.


## Acknowledgements
> - **Data Source**: The loan dataset provided for this analysis.
> - **Educational Resources**: Various online resources and courses that helped in learning EDA and risk analytics techniques.



## Contact
Created by [@sowmilydutta][@shounakdutta]
