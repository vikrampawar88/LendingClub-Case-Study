# Lending Club Case Study
> In this project, we are working on applying the knowledge of Exploratory Data Analysis to understand how consumer attributes and loan attributes influence the tendency of default for the Lending Club using dataset which includes complete loan data for all loans issued by Lending Club through the time period 2007 t0 2011.


## Table of Contents
* [Problem Statement](#problem-statement)
* [Business Objective](#business-objective)
* [Analysis Approach](#analysis-approach)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Team](#team)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
LendingClub is an online peer-to-peer lending platform that connects borrowers and investors.The platform operates as an intermediary, facilitating loans between individual borrowers and investors who are seeking to earn interest on their funds.

Borrowers who are seeking personal loans can apply for loans through LendingClub's website. The platform evaluates the creditworthiness of the applicants using various factors, including credit history, income, and debt-to-income ratio. Approved borrowers are then assigned an interest rate based on their credit profile.

Two __types of risks__ associated with the Lending Club’s decision:
* If the applicant is __likely to repay the loan__, then not approving the loan results in a __loss of business__ to the company
* If the applicant is __not likely to repay the loan__, i.e. he/she is likely to default, then approving the loan may lead to a __financial loss__ for the company


Like most other lending companies, __lending loans to ‘risky’__ applicants is the largest source of financial loss __(called credit loss)__. The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, __borrowers who default__ cause the largest amount of __loss to the lenders__. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

## Business Objective
The goal is to **identify these risky loan applicants**, then risky loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, **the company wants to understand the driving factors (or driver variables)** behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

- Data Set : Loan Lending Club loans dataset provided through the time period 2007 t0 2011

## Analysis Approach
1. Importing required libraries & loading data
2. Basic data understanding
3. Data Cleaning
4. Univariate Analysis
5. Bivariate Analysis
6. Multivariate Analysis
7. Conclusion

## Conclusions
Detailed conclusion is provided in LendingClub_Case_Study.pdf.
Final Recommended driving factors (or driver variables) to consider possible loan default are as follow:

<br/>

**Customer Attributes**

**dti :** A ratio calculated using the borrower’s total monthly debt payments on the total debt obligations, excluding mortgage and the requested LC loan, divided by the borrower’s self-reported monthly income.
<br/>
**annual_inc :** The self-reported annual income provided by the borrower during registration.

<br/>
<br/>

**Loan Attributes**

**term :** The number of payments on the loan. Values are in months and can be either 36 or 60.
<br/>
**grade :** LC assigned loan grade.
<br/>
**purpose :** A category provided by the borrower for the loan request.
<br/>
**int_rate :** Interest Rate on the loan
<br/>
**loan_amnt :** The listed amount of the loan applied for by the borrower. If at some point in time, the credit department reduces the loan amount, then it will be reflected in this value.
<br/>
**funded_amnt :** The total amount committed to that loan at that point in time.


## Technologies Used
- Python - Version 3.9.13
- numpy - Version 1.21.5
- pandas - Version 1.4.4
- matplotlib - Version 3.5.2
- seaborn - Version 0.11.2
- Jupyter Notebook - Version 6.4.12
- Anaconda - Version 2.3.2

## Acknowledgements
- The project references insights and inferences from live presentation given by Dr. Pooja Jain
- EDA course material from upGrads curriculum at [https://learn.upgrad.com/](https://learn.upgrad.com/).
- [What is Exploratory Data Analysis? by Prasad Patil](https://towardsdatascience.com/exploratory-data-analysis-8fc1cb20fd15)
- [https://www.geeksforgeeks.org/what-is-exploratory-data-analysis/](https://www.geeksforgeeks.org/what-is-exploratory-data-analysis/)
- [https://www.financialexpress.com/money/how-do-lenders-determine-your-personal-loan-eligibility/1496832/] & some more google search links on how banks check customer credit worthiness

## Team
[Vikram Pawar](https://www.linkedin.com/in/vikrampawar88/)


## Contact
Created by [@vikrampawar88] - feel free to contact me!



<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->