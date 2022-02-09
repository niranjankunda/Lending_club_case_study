# Lending Club Case Study

> The data given contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.


## General Information

- For a consumer finance company which specialises in lending various types of loans to urban customers, when the company receives a loan   application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

- If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study

- For this case study,Loan Dataset is used. It contains the complete loan data for all loans issued through the time period 2007 t0 2011.


## Conclusions

- Most of the charged off are in the year 2011
- Most of the charged off are in the Month December
- Most the the borrowers who gets the loan are under 'RENT' category and there is a very less impact of 
  'home_owner' on dafaulters
- Grade B are the most defaulters and among B grade, B5 is the most
- Those who take loan for debt_consolidation tends to default the loan most among all other reasons
- Borrowers employed for < 1 year have high high tendency to default
- High-interest rate is one of the major drivers for defaulters
- For Funded amount, amount in the 14125-35000 bucket has the most defaulters



## Technologies Used

Numpy Version: 1.19.5
Pandas Version: 1.2.4
Seaborn Version: 0.11.1



### Contributors
- Kazi Mohiuddin Zoheb
- Niranjan Kunda