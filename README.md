# Lending Club Case Study
> The project involves utilizing the Lending Club dataset to develop a predictive model that forecasts the likelihood of a loan default. Through data science techniques, the goal is to identify patterns and factors that can accurately predict whether a borrower will default on their loan.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Project Overview
This is a data science project aimed at predicting whether a loan will default using the Lending Club dataset. The goal is to build a model that can identify the likelihood of a loan default, helping mitigate financial risks.

### Project Background
Lending Club is the largest online platform for personal and business loans, including medical financing. It offers borrowers a streamlined process to access lower-interest loans through an easy-to-use online interface. However, like all lending companies, they face significant financial risk when extending loans to high-risk borrowers. The biggest contributor to financial loss, known as credit loss, occurs when borrowers fail to repay their loans. These defaulted loans—referred to as ‘charged-off’—represent the primary source of financial loss for the company.

### Project Statement
The objective is to uncover the key factors that contribute to loan defaults, which have a major impact on the company’s financial health.

### Dataset
The dataset is in CSV format, containing loan-related information from Lending Club, which will be used to analyze and predict loan defaults.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Primary factors that can be leveraged to forecast the probability of loan default and reduce credit loss.
 - Loan Grade: Borrowers with a loan grade of B or C exhibit a higher likelihood of default.
 - Loan Term: 36-month loans show a marginally higher proportion of defaults compared to 60-month loans.
 -  Home Ownership: Renters are more prone to default than homeowners, making "RENT" a critical indicator.
 -  Employment Length: Borrowers with over 10 years of employment tend to have a slightly higher risk of default than 
those with shorter employment histories.
 - Annual Income: Borrowers with an annual income between 30,000 and 60,000 are more likely to default. 
Additionally, the analysis indicates that the probability of default decreases as income rises, with lower-income groups 
showing a higher risk.
 - Loan Amount: Borrowers requesting loan amounts in the range of 4,000 to 6,000, particularly for debt consolidation, 
are more likely to default.
 - Loan Purpose: Debt consolidation loans and credit card refinancing have higher default rates. Other categories such 
as small business loans, general loans ("other"), and home improvement loans also present elevated risks.
 - Inquiries in the Last 6 Months: Borrowers with a higher number of credit inquiries within the past six months are 
more likely to default, indicating a relationship between recent credit activity and default risk.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas     - version 2.2.2
- NumPy      - version 1.26.4
- Seaborn    - version 0.13.2
- MatplotLib - version 3.8.4
   

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project was undertaken as part of the Machine Learning and Artificial Intelligence course in the UpGrad IITB Programme. 

## Contact
Created by [@adith90] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
