
## Problem Set 1

Stock Price Prediction using Machine Learning

Use data set “Prices.csv” and apply a regression model to predict the future prices. 
The answer should include at least 10 prediction data points.


## Problem Set 2

Waiter Tips Prediction with Machine Learning
Use data set “tips.csv”. Data description below.
1.	total_bill: Total bill in dollars including tax
2.	tip: Tip given to waiter in dollars
3.	sex: gender of the person paying the bill
4.	smoker: whether the person smoked or not
5.	day: day of the week
6.	time: lunch or dinner
7.	size: number of people

PART 1:
Do a report for:

1.	the total bill paid by number of people at a table and the day of the week.
2.	the total bill paid by the number of people at a table and the gender of the person paying the bill.
3.	the total bill paid by the number of people at a table and the time of the meal.

PART 2

Use linear regression to predict the future waiter tips (hint: don’t forget to transform your categorical values into numerical values.)


## Problem Set 3

Payments Fraud Detection
Use data set “Fraud.csv”
Data description below.
1.	step: represents a unit of time where 1 step equals 1 hour
2.	type: type of online transaction
3.	amount: the amount of the transaction
4.	nameOrig: customer starting the transaction
5.	oldbalanceOrg: balance before the transaction
6.	newbalanceOrig: balance after the transaction
7.	nameDest: recipient of the transaction
8.	oldbalanceDest: initial balance of recipient before the transaction
9.	newbalanceDest: the new balance of recipient after the transaction
10.	isFraud: fraud transaction

Part 1
-	Do a Transactions distributions chart
-	Do a correlation map
-	transform the categorical features into numerical. Also transform the values of the isFraud column into No Fraud and Fraud labels to have a better understanding of the output:
Part 2
Use Decision Tree algorithm to train a classification model to classify fraud and non-fraud transactions.  
Print out a table with the predictions.

![image](https://github.com/loinguyen1/Machine-Learning-Practices/assets/127418660/f81df624-4122-4a51-9270-2c3c372b67dc)
