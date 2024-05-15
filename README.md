# Lending-Club Case Study
> Lending Club stands out as the leading digital loan marketplace, catering to personal, business, and medical financing needs. With a streamlined online platform, borrowers can easily secure loans at competitive interest rates. However, akin to many other lending institutions, extending credit to high-risk applicants poses the greatest risk of financial loss. Credit loss, defined as the funds forfeited by the lender due to borrower non-payment or default, is primarily attributed to those categorized as 'charged-off' customers, indicating defaulters. The company aims to discern the primary factors influencing loan defaults, known as driver variables. Understanding these indicators is crucial for portfolio management and risk assessment. By identifying high-risk loan applicants through exploratory data analysis (EDA), the company can mitigate potential credit losses by reducing exposure to such applicants.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The loan request is graded by LendingClub and then listed for loan. Now it is up to the investor who decides which loan listing to invest in looking at the loan detail and borrowers information. Only those variables should be chosen for analysis that will be available to the investor at the time of deciding whether to invest in a loan request or not.
- We need to identify key driving factors for loan defaults to improve risk assessment and minimize financial losses in our lending portfolio.
- The given data contains information about past loan applicants and whether they ‘defaulted’ or not. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Pandas version: 2.2.0
- Matplotlib version: 3.8.3
- Seaborn version: 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusions
- LC assigns loan grades from A to G, with a higher likelihood of default as the grade descends. Grades F and G, in particular, see over 30% of loans being charged off.
- Loans with a 36-month term exhibit a better payoff percentage compared to those with a 60-month term, where defaulters are more common.
- Interest rates impact loan defaults, with higher rates correlating to increased charge-offs.
- Installment amounts are higher for charged-off loans.
- Debt consolidation is the most common loan purpose and also accounts for the highest number of defaults.
- Higher loan amounts are associated with a greater likelihood of charge-offs.
- Debt-to-income ratio (DTI) influences loan defaults, with higher DTIs indicating a greater chance of default.
- The loan-to-income ratio is positively correlated with loan default probability.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Contact
Created by [@zeebee48] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
