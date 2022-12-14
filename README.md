Lending Club Case Study
Lending Club allows a user to issue loans to other users or allows the
user to apply for a loan. As a creditor (or lender), the user provides monetary funds upfront to
Lending Club; the lender is then allowed to issue portions of this pool of money (called notes) to
loan applicants in twenty-five dollar increments. In order to apply for a loan, a user must provide
credit history and credit factors to Lending Club itself. Lending Club has the authority on
whether or not to list a loan request. Ultimately however, lenders choose the particular applicants
to which to issue notes; the lender's choice is contingent on other profile data that loan applicants
3
provide during that application process. Applicant profile data includes information such as a
user's employment information, age, current geographic location of an applicant, and a history of
credit information (this is not exhaustive)

Business Understanding


You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

When a person applies for a loan, there are two types of decisions that could be taken by the company:

Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)
 

Business Objectives


This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

 
 
Steps involved:

Data Understanding

Data Cleaning

Univariate Analysis

Bivariate Analysis


Multivariate Analysis

Conclusion
