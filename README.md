# Detect default credit card using Machine Learning
Default is to fail to make a payment on a debt by the due date. If someone miss the minimum card payment six months in a row, their credit card will be an default.

We are going to use classification method to classify two two-feature groups. What if the number of features increase? How can we use the method we learned from the class to solve more complicated problems. Following you will need to solve a Credit Card Default Detection Case where you will classify two multiple-feature groups.

Data Description:

id: A unique Id field which represents a customer

X1: Credit line

X2: Gender (1 = male; 2 = female).

X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others). X4: Marital status (1 = married; 2 = single; 3 = others).

X5: Age (year).

X6 - X11: History of past payment. X6 = September, 2015;

X7 = August, 2015;

X11 =April, 2015. -1 = pay one month ahead; -2 = pay two month ahead; 0 = pay on time; Positive means the payment delayed months, 1 = delay 1 month, 2 = delay 2 months, etc.X12- X17: Amount in bill statement.

X12 = amount of bill statementSeptember, 2015

X13 = amount of bill statementAugust, 2015

X17 = amount of bill statementApril, 2015.

X18-X23: Amount of previous payment

X18 = amount paid in September, 2015; X19 = amount paid in August, 2015; X23 = amount paid in April, 2015.

Y: A binary response variable to indicate whether the customer is default (1) or not (0).

This is a real problem to classify multi-feature data into two groups.

