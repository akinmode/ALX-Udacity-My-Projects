# Prosper Loan Dataset Exploration
## by Akinwale Akinjiola


## Dataset

The Prosper Loan Dataset is financial dataset that consists of information on 113,937 loan transactions, with 81 associated variables/characteristics on each loan including amount, interest rate, current status, borrower income, and many others.

## Summary of Findings

While exploring the dataset, I took interest in the impact of employment status of the loan borrowers on the completion status of the Prosper loan.

I found out that the loans were given for durations of 12-<em>short</em>, 36-<em>medium</em> and 60-<em>long</em> months, with majority of the loans of 36 months duration listed from 2005 and 2014. More than 80% of the borrowers in the dataset are either Employed <em>(58.9%)</em> or Full-time <em>(23.3%)</em> workers and 6.7% of the status is not available in the data. I re-labelled the loan status options with 'Past Due (...)' as 'Past Due' and observed that majority (~82%) of the loans listed were either 'Current' or 'Completed'.

I observed in the number of loans listed a decline from 2008 to 2009; a rise from 2010 till 2013; and a sharp drop from 2013 to 2014. This initial decline was reflected in the absence of loans with a 'Current' status <em>i.e. loans were either 'Completed', 'Charged Off' or 'Defaulted'</em>, while the spike in the number of loans may be attributed to the increase in the number of **employed borrowers** in the dataset from 2010.

There were about 67 listed types of 'Occupation' in the dataset. I re-coded the labels into categories/collections as far as possible and observed the presence of an unclassified group as 'Others' which represented approximately 28% of the whole population. I observed quite a number of outliers as borrowers whose original amount of the listed loans were more than the upper boundary for the loan duration (~4% of the borrowers), majority of whom were from the employed category.


## Key Insights for Presentation
My presentation focuses on the contributions of the employment status of the borrower on the listed stated of the loans.

Over the 10 year period of the Prosper loan, the listing of the loans showed that:

1. Prior to 2005, the state of a number of loans were not documented.
2. Only 22 loans were listed for 2005 and completed to the 'Not Available' class of borrowers.
3. **No new loans** were recorded from 2005 to 2009. All loans during these years were listed as either 'Completed', 'Charged Off' or 'Defaulted' and the 'Employed' were not documented as borrowers.
4. The spike in the number of loans from 2010 may be accounted to the isting of the 'Employed' as borrowers of the loan and thus spiking up the number of loans in 'Current' state .
