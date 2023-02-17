# # PROSPER DATA EXPLORATORY ANALYSIS

###  OKOH VICTOR 

# Prosper_loan_data
This project is part of Udacity's Data Analyst Nanodegree, and its objective is to explore Prosper Loans dataset and uncover the relationship between borrowerAPR and it effect on demand for loans and repayment ability to get actionable insights using exploratory and explanatory data analysis techniques.

This project is meant to unveil any sort of insights from my data exploration.

# Structure of dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount (demand for credit), borrower rate (or interest rate), estimated returns( on loans), current loan status, borrower income, and many others. Categories first include Borrower information: Basic attributes of the borrowers such as annual income, condition of employment, interest rate, loan status, etc. While the second category include Loan performance information: Metrics evaluating the risk associated with the loans such as Prosper score and bank card utilization, etc

[Source of the data](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000)

[See this data dictionary to understand the dataset's variables](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000)


## Installation

The following libraries are used in this project:
1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn

## Summary of Findings

- The overall objective of this research work is to investigate the effect of interest rate on te demand for loan and also on loan repayment. Also, to determine the factors are influencing effective loan repayment

- Also, the distribution of APR looks multimodal.This is because of the multiple maxima values found in the graph. Generally, borrowers tend to prefer APR with the lowest as this would make repayment more easier

- The highest frequency comes from a  C prosper rating with the least 6.1%. Higher grades are intended to represent a lower probability of default. 

- I expect BorrowerAPR will have a negative effect on demand for credit. The higher the BorrowerAPR to be specific, are often associated with low demand or appetite for credit. Moreover, it is also believed to negatively affect loan repayment amongst borrowers.

-  Also, it was observed that interest rate (borrower APR) was lowest in 2014 and in 2007 while demand for loans was highest in this same for period. And when interest rate was at it all time high  in 2012, demand for loans was at it lowest. This  shows the inverse relationship between intrest rate and demand for credit

- Further into my exploration, I found a negative relationship between intrest rate and effective loan repayment This implies that a higher intrest rate would discourage repayment ability to loans. High interest rates discourage business to grow in the sense that a big part of the profit generated goes back to the financial institution to service the loan that was once given to the borrower.


- I found also that there are some negative and strong relationships between the categorical/ordinal variables selected and the interest rate. As an example, BorrowerAPR and ProsperScore are negative because borrowers with lower score are more likely to pay higher APR.


- Another observation is that borrowers who have collaterals(or homeowners) have lower rates than those who doesn't have any collateral(house).


- In parallel, for all Prosper Ratings except for "A",and "AA", Defaulted and charged off loans usually have a higher Borrower APR compared to completed or current loans(good records).

- Finally, having a collateral and a higher wage help getting higher loan amount. It is clearly visible that being a home owner is a very important element to get a higher loan amount.

## Key Insights for Presentation

- Focus on the overall objective of the study which is the effect of intrest rate on demand for credit and loan repayment 


- Elaborate on the univariate aspects of the key varaibes in the dataset 


- Focus on the relationship between intrest rate (borrower apr) and demand for credit 
(loanoriginalamount)


- Focus on intrest rate effect on other variables such as debt to income ratio


- Offer a minimal note on the interconnedness of the selected multivariate relationships 


- Call of action would be on strategies to get access to loans 

