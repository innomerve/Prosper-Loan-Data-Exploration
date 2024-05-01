#  Prosper Loan Data Exploration
#### by Murielle Souvenir LOKONON

## Dataset

>Here i analyze the prosper loans dataset. It contain 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and more.

> They  columns description are <a href="https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000"> here</a>.

> The dataset is available <a href="https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000"> here</a>.

## Summary of Findings

> During the exploration, i found that there wasn't any bivariate relationship between the numerical features except the one which is normal between the loan original amount and the monthly loan payment (More is the loan original amount more is the monthly loan payment). I also found this bivariate relationships: 
+ The prosper score and the borrower rate: the worse is the posper score (10 to 1),  the higher is the borrower rate
+ The prosper score and the loan original amount: the best is the prosper score (1 to 10), the higher is the loan original amount
+ The income range and the borrower rate: the best is the income range, the lower is the borrower rate
+ The  income range and the loan original amount: the best is the income range, the higner is the loan original amount.
+ The  income range and the borrower open credit lines: the best is the income range, the higner are the the borrower open credit lines.

> Surprisingly there was'nt relationship between the feature of interest (loan status) and others features. Howerver i noticed that: 

+  most of the past due loan status have a high borrower rate and most of the current and completed status have a low borrower rate.
+ most of the loan chargedoff and Past Dues status has a small debt to income ratio but have high delinquencies last 7 years.

+ Most of the borrowers have a small debt to income ratio ( whic means that they daon't have a large amount of debt).

+ more is the prosper score and the income range , the lower is the borrower rate and the higner is the loan original amount.
 
 
## Key Insights for Presentation

> At this step  I wanted to present the effects of borrower income range and  prosper score on the loan rate and original amount. Thus i firstly present the impact of the prosper score on the borrower rate   then loan original amount. Secondly i present the impact of the borrower income range on the borrower rate  then loan original amount. Finally i present the impact of all of them.
