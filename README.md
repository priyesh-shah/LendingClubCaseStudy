# Lending Club Case study
>Lending club is a consumer finance company which specialises in lending various types of loans to urban customers. 
When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 

Two types of risks are associated with the bank’s decision:
1)If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
2)If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
 If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
 In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

- loan.csv dataset is used as reference to do analysis.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Lending club should stop approving loans if below criterias are majorly fulfilled.
- Loan applications are from CA,NY,FL state
- Loan application is for purpose : small business
- Loan application is in month of December
- Borrower Annual Income is less than 25000 and loan amount is more than 25000
- Borrower work experience is 1 or 10+
- Loan int rates are more than 10%
- Borrower home ownership is RENT and MORTGAGE
- Borrower grades are between D to G. The higher the grade i.e G more possibility for default

## Technologies Used
- Python 3.0

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad
- This project was based on EDA (Exploratory Data Analysis) module


## Contact
Created by [@priyesh-shah] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->