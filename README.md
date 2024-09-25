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
    - Grade: B, C
    - Term: 36 months
    - Home Ownership: RENT
    - Employee Length: 10+ years
    - Annual Income: 30K-60k
    - Loan Amount: 4k - 6k
    - Purpose: debt_consolidation- 60k
      
- Other considerations for 'defaults' :
    - Inquiry in last 6 months: The analysis suggests that borrowers with a higher number of inquiries might be more likely to default.
    - The proportion of Charged Off loans decreases as annual income increases. This indicates that borrowers with higher incomes are less likely to default. Borrowers with 30-60K annual income are more likely to default.
    - Debt consolidation and credit card loans appear to have the most defaults (charged off). Categories like small business, other, and home improvement show higher risks.
    - 36-month loans have a slightly higher proportion of Charged Off loans compared to 60-month loans.
    - Borrowers with 10+ year of employment have a slightly higher proportion of Charged Off loans compared to those with shorter employment lengths.

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
