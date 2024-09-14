# Project-Credit-Card-Fraud-Analysis
Deep dive into a Kaggle dataset of EU credit card holders transactions from random 48 hours of 2013

Credit card fraud is a well known problem around the world. Although it is mostly not an issue for the end user as the bank is always responsible for security of its customers. In this project we tried to find if there is any pattern of this fraud transaction to happen in any specific time of the day. If there is any relation between the time of the hour and the ammount of fraudelent transactions.

## Stage 1: Data Collection and data wrangling
- Data collected from Kaggle. But for privacy reason most of the data was hidden.
- From original dataset "Time" , "Amount" & "Class" data was useful for analysis.
- The time column needed to be modified in order understand the exact time of the day the transaction happend.
- The class column store the data either the transaction was fraud or not.

## Stage 2: Connecting SQL with Python 
- After completing the necessary cleaning in python the datset kept in .csv format.
- Established a connection between python and SQL.
- Run SQL query to fetch important insights.

## Stage 3: Plotting useful insights
- Total number of transaction
- Total number if fraud transaction
- Hourly Fraudelent transaction
- Average transaction amount (fraud & non fraud)
- The realtion of fraud amount and hour

## Conclusion:
- Total Transactions: ≈285K 
- Fraudulent Transactions: 492
- Percentage of Fraudulent Transactions: 0.172%
- Max fraud transaction amount: €2125.87

### Prject Presentation Link: https://docs.google.com/presentation/d/1YjX47pNujaN8cuZuYnUGUSEW0sjDvH7gniyoE0jGIQQ/edit?usp=sharing
 
