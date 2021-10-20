# Prosper Loan Data Exploration
## by Reem Alshehri


## Dataset


There are 113,937 loans in the dataset with 81 features. Most variables are numeric and categorical in nature.

The dataset features can be split into two main categories:

1- Borrower information
2- Loan performance information


## Summary of Findings


In the univariate exploration, I visualized and addressed minor quality and tidiness issues for the following features:
Numerical Features: Debt To Income Ratio, Average stated monthly income,Loan Original Amount, BorrowerAPR, BorrowerRate, Stated Monthly Income.
Categorical Features: List of Categories, BorrowerState, Loan Origination Year, Loan Origination Quarter.

The bivariate exploration revealed the numerical categories did have obvious correlations between BorrowerRate and BorrowerAPR, The relationship is approximately linear between BorrowerRate and BorrowerAPR when BorrowerAPR is transformed to be on
a logarithmic scale. and for categories the highest average of loan amount was for debt consolidation and the lowest was for student use
- the states AL,ND and AR have the highest Bowrrower Rate and ME,IA have the lowest.

The Multivariate exploration revealed that :
-during 2012 average BorrowerAPR was between 0.20-0.30 but in the 2013 it seems like it narrow down to became between 0.20 and 0.25.
- CA state on the first quarters the houshold expenses has the highest average loan Amount followed by vacation,for NY state the medical category it has one of the lowst averages but on the second quarters it did increase significantly,in TX baby&Adoption category has the highest average of all quarters.
- the three top states started the first quarter of 2011 with average BorrowerRate of 0.20,but on 2013 the trends were reversed.
-CA state the average monthly income relarively constant at around 6000 - 7000,ny state show no big difference the avarege income were about 6000-7000 on most quarters except for the second quarter on 2011 it had grwo smaller,for tx state on 2011 and 2012 the average income was about 5000-6000.
-the last visualization illustartes that the three states have a very similar debt average to one anothe.

## Key Insights for Presentation

For the presentation, I focus on the journey of exploring the features of interest to discover which loan features are most important like  BorrowerAPR, debt to income ration and the Borrower Rate.

I begin with introducing the destirbution of debt to income ration feature of interest,then followed by how the Borrower APR and Rate are relate to one another and eventually a comparsion between the average income for the top three states.
