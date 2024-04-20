# Bank-Term-Deposit

The data is related with direct marketing campaigns of a Portuguese banking institution for subscription to term deposit. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) was subscribed or not.
Data set has 20 predictor variables (features) and around 41K rows.
The dataset is collected from UCI Repository - "https://archive.ics.uci.edu/ml/datasets/bank+marketing"
A term deposit is a type of deposit account held at a financial institution where money is locked up for some set period of time.Term deposits are usually short-term deposits with maturities ranging from one month to a few years.Typically, term deposits offer higher interest rates than traditional liquid savings accounts, whereby
customers can withdraw their money at any time.
## GOAL
Using the data collected from existing customers, we have to build a model that will help the marketing team identify potential customers who are relatively more likely to subscribe to term deposits and thus increase their marketing towards those customers.
Business goal: Reducing marketing resources by identifying customers who would subscribe to term deposit and thereby direct marketing efforts to them.

## Summary
1) Data description
2) EDA
3) Data preprocessing
4) Modelling - 5) Evaluation

## DATA DESRCIPTION
age : age of customer
job : type of job
marital : marital status
education : education qualification
default : has credit in default?
housing : has housing loan?
loan : has personal loan?
contact : contact communication type
month : last contact month of year
dayofweek : last contact day of the week
duration : last contact duration, in seconds
campaign : number of contacts performed during this campaign and for this client
pdays : number of days that passed by after the client was last contacted from a previous campaign
previous : number of contacts performed before this campaign and for this client
poutcome : outcome of the previous marketing campaign
emp.var.rate : employment variation rate - quarterly indicator
cons.price.idx: consumer price index - monthly indicator
cons.conf.idx : consumer confidence index - monthly indicator
euribor3m : euribor 3 month rate - daily indicator
nr.employed : number of employees - quarterly indicator
y : has the client subscribed a term deposit
