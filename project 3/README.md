# Loan Dataset exlporation
## by (Dakhouche Salah Eddine)


## Dataset

The data set contain 113937 records of loans and 82 columns, to 
explore the dataset to answer the questions about what 
are the characteristics that impact the number of investors and the percent 
funded, I choosed 12 column (['ListingKey','Term','LoanStatus','LoanOriginalAmount',
'EstimatedReturn','ProsperScore','DelinquenciesLast7Years','DebtToIncomeRatio'
,'IncomeRange','IncomeVerifiable','PercentFunded','Investors']) that I consider have 
the potentiel of having impact on the two variables.
**the link for the data set** : https://www.google.com/url?q=https://www.google.com/url?q%3Dhttps://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv%26amp;sa%3DD%26amp;ust%3D1581581520570000&sa=D&source=editors&ust=1664916302954266&usg=AOvVaw12YjGUPF3is1YM6g1DBnbW
**the documentation for the dataset** : https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0


## Summary of Findings

In the exploratory phase, I found that there was no correlation between the 
percent funded and the other variable mainly because the majority of loans 
are fully funded, and this question cannot be answered with this data set, 
On the other side, I found some correlation between the number of investors 
with the original amount of the loan, with the estimated return surprisingly 
a negative one, but when I added the prosper risk I found that the lower the 
risk the lower the estimated return and the higher the investors are willing 
to invest, with the proper score and with the income range.
finally, I found that there is a positive relationship between the prosper 
risk and the income range, which means that the higher the income range the higher
the prosper risk or the lower the risk of the loan.



## Key Insights for Presentation

For the presentation, I will focus on showing the impossibility to find any relation
between the variables and the percent funded and showing the relations that I found 
between the number of investors with the original loan amount, estimated return, 
prosper risk and the income range.
but before I will introduce the distribution of each of those variables to explain 
the problems that are found with the percent funded variable too.
