# R-Walmart-Project
Forecasting demand for 45 Walmart stores.

I worked on this capstone project towards completion of final assessment for Data Science course from Simplilearn. The aim was to analyze the sales datasets for 45 Walmart stores predict the sales and demand accurately. Part of the challenge presented in this project was modelling the effects of markdowns on holiday weeks in the absence of complete/ideal historical data. 

# Problem Statement
Walmart would like to predict the sales and demand accurately. There are certain events and holidays which impact sales on each day. There are sales data available for 45 stores of Walmart. The business is facing a challenge due to unforeseen demands and runs out of stock sometimes, due to the inappropriate machine learning algorithm. An ideal ML algorithm will predict demand accurately and ingest factors like economic conditions including CPI, Unemployment Index, etc.
Walmart runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of all, which are the Super Bowl, Labour Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks. 

Holiday Events are:
Super Bowl: 12-Feb-10, 11-Feb-11, 10-Feb-12, 8-Feb-13 Labour Day: 10-Sep-10, 9-Sep-11, 7-Sep-12, 6-Sep-13 Thanksgiving: 26-Nov-10, 25-Nov-11, 23-Nov-12, 29-Nov-13 Christmas: 31-Dec-10, 30-Dec-11, 28-Dec-12, 27-Dec-13

# Objectives:
1.  Find which store has maximum sales.
2.  Find which store has maximum standard deviation i.e., the sales vary a lot. Also, find out the coefficient of variance i.e. ratio of standard deviation to mean.
3.  Find which store/s has good quarterly growth rate in Q3’2012
4.  Some holidays have a negative impact on sales. Find out holidays which have higher sales than the mean sales in non-holiday season for all stores together
5.  Provide a monthly and semester view of sales in units and give insights
6.  For Store 1 – Build prediction models to forecast demand. Hypothesize if CPI, unemployment, and fuel price have any impact on sales.

# Data available: 
We have historical data available which covers sales from 2010-02-05 to 2012-11-01, in the file Walmart Store sales. This file has following fields:
- Store - the store number
- Date - the week of sales
- Weekly Sales - sales for the given store
- Holiday Flag - whether the week is a special holiday week 1 – Holiday week 0 – Non-holiday week
- Temperature - Temperature on the day of sale
- Fuel Price - Cost of fuel in the region
- CPI - Prevailing consumer price index
- Unemployment - Prevailing unemployment rate
