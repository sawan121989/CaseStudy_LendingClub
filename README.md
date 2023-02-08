# Project Name
> Lending Club Case Study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- In this case study we are trying to solve real time problem of risk analytics for a finance company called Lending Club
- Lending Club specialises in lending various types of loans to urban customers and facing two major problems we will try to solve
- Two types of risks are:
    1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
    2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.
- Lending Club Loan Dataset is used to perform EDA and provide suggestions to Lending Club


## Conclusions
- It was observed that there are no defaults for loans having less than 10% interest rate,hence Lending club should consider accepting more loans with less than 10% ineterest rate.
- Lending club should consider to accepting more loans request for borrowers who are "owning house" as they have lees probabilty for Charged_off.
- Lending club should consider to accepting more loans request for grade A as it has just 5% Charge off loans.Other Grades have high Charge off probablity.
- Lending club should consider to accepting more loans request for borrowers which have loan amount less than 20% of their annual income.
- Lending club need to accept more loan for 36 month term as they have less chances of Charged off.
- Lending club need to accept loan for individuals owning house, loan amount less than 20% of their annual income and interest rate is less then 10%.This combination is have less chances to charged_off.
- Lending club should accept more loan  applied for wedding, major_purchase, car and credit_card as the chances of charged_off is less(~10%) but for small business they should avoid as they have 26.8% charged_off.
- Lenading club should accept the loan request for small loan amount.
- Lenading club should accept the loan request for coming from addres state IN, IA and NE as they are having low risk of charged off.


## Technologies Used
- Python 3
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Jupyter Notebook


## Acknowledgements
Give credit here.
- This project was inspired by IIITB ML and AI course from Upgrad


## Contact
Created by @sawan121989 and @pramod-prasad01 - feel free to contact!
