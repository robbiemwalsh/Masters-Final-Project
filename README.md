# Masters-Final-Project
A capstone project for my masters degree.  

The assignment for this project was to find our own dataset, conduct a statistical analysis on it, and write a report.  

I decided to use a dataset from Fannie Mae which has loan-level performance data on multifamily loans and build a model for forecasting defaults.
This is a common type of model used in the credit risk industry, while my analysis wouldn't be enough to build a full loss forecasting framework, it would be a critical component of such a framework.

This project was somewhat contrained by the fact that there was a lot of COVID-era data that was difficult to model, as well as the fact that multifamily datasets tend to not be as large as some of the other consumer credit datasets I was used to working with.  Finally, the loans were not homogeneous, with some loans having I/O periods, drawdown periods followed by an amortization term, and balloon payments, which made building a model difficult because I did not have enough data to create segment models for each type of loan that appeared in the dataset.

Nonetheless, for a model that did not have any sort of credit score or credit grade and did not use any delinquency status, it performed well.  Layering on another model that made use of delinquency status would be an obvious area for improvement.
