# Prosper Loan Data Exploration
## by NGUYEN Duc Huy


## Dataset

This dataset is financial dataset and this is related to the loan, borrowers, lenders, interest rates... Prosper or Prosper Marketplace Inc. is a San Francisco, California based company specializing in loans at low interest rates to the borrowers. 
The dataset is comprised of 81 variables and contains 113937 entries. 

In this project, we are about to analyse it and trying to find the pattern in the Prosper data. 


## Summary of Findings


In the exploration, I found that the BorrowerRate" and "LenderYield" are highly and positively correlated with one another. The other strong relationship is between BorrowerRate and Borrower APR. Moreover, there is a moderate and negative correlation between MonthlyLoanPayment and BorrowerRate/LenderYield. Most of the remaining variables doesn't present a strong correlation.

Outside of the main variables of interest, I verified that the more experience people gain on the job, the less likely they are to choose to borrow.

I found a somewhat surprising result initially that borrowers with poor prospects are subject to higher interest rates than borrowers with better prospects.


## Key Insights for Presentation

For the presentation, I start by introducing the loanStatus variable, followed by the pattern in EmploymentStatusDuration distribution, then plot the histogram.

Afterwards, I introduce each of the categorical variables one by one. I use the boxplots of ProsperScore and BorrowerRate/BorrowerAPR. I'am only looking at the relationship between prospect score and distribution of interest rates. Moreover, I use p Correlation Heatma to identify the correlation between factors interested such as: "Term", "EstimatedEffectiveYield", "EstimatedLoss", "EstimatedReturn", "BorrowerAPR", "BorrowerRate", "LenderYield","EmploymentStatusDuration", "MonthlyLoanPayment", "StatedMonthlyIncome"

