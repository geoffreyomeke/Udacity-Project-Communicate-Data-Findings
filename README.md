# Loan Data Exploration
## by Geoffrey Mosongo


## Dataset
There are 113,937 loans in the dataset with 81 characteristics. Most variables are numeric and categorical in nature. The characteristics included original loan amount, borrower's Prosper rating, loan term, borrower's stated monthly income, as well as many other features such as borrower's employment status, debt to income ratio, current loan status etc.

The dataset can be downloaded from https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv.

Broadly speaking, the dataset can be grouped into two main categories:

* Borrower information
* Loan performance metrics



## Summary of Findings

The analysis determined that, the borrower APR is negatively correlated with original loan amount. The APR decreases with an increase in the loan amount. As the rating improves, the APR also decreases. Borrowers with the best Prosper ratings have the lowest APR. It means that the Prosper rating has a strong effect on borrower APR. 
When Prosper ratings changed from HR to A or better, the APR slightly improves. This can be attributed to the fact that people with A or AA ratings tend to borrow more money.
The loan amount is also correlated positively with stated monthly income. This could mean that individuals with higher monthly earnings will tend to borrow more money. Also, as the loan term increases, it was observed that the loan amount also increases.


## Key Insights for Presentation

For the presentation, the focus is on exploration of the features of interest to discover which loan parameters are most important for les risky borrowers.

The presentation begins with the introduction of the parameters of interest, followed by how they relate to one another and eventually how they correlate with borrower rating scores for credit advancement.