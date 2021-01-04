# Feni Rahmi Portfolio
My data science portfolio 

# [Project 1 : Credit Card Customer Segmentation](https://github.com/FeniRahmi/CC_segmentation)
* Created a model that estimate credit card customer segmentation to help the company to define marketing strategy.
* The sample Dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months.
* The file is at a customer level with 18 behavioral variables.
* Using K-Means algorithm with the K value determined by silhouette score.
* Using PCA for dimension reduction and better visualization.
![](images/ccs.png)

# [Project 2 : Titanic Survival Passenger using Random Forest Algorithm](https://github.com/FeniRahmi/Titanic)
* For this example project I predicted the survival status (0 = No, 1 = Yes) from the Titanic passenger.
* Using Random Forest classifier.
* Creating new feature (feature engineering).
* The submission score in kaggle is 0.76, which not bad for the first attempt.

# [Project 3 : Exploratory Data Analysis : Nutrition Fact for McDonald's Menu](https://github.com/FeniRahmi/McDonald_EDA)
I have explored the McDonald's dataset to find the answers for the following questions:
* How many calories does the average McDonald's value meal contain?
* How much do beverages, like soda or coffee, contribute to the overall caloric intake?
* Does ordered grilled chicken instead of crispy increase a sandwich's nutritional value?
* What about ordering egg whites instead of whole eggs?
![](images/mcd.png)

# [Project 4 : Estimation of CO2 Emission using Simple Regression](https://github.com/FeniRahmi/Regression)
* This project give a model to predict CO2 emission from car using simple regression algorithm.
* There is one feature which I used in the modeling.
* I have selected the feature using .corr method and manual plotting (features vs target).
![](images/regression.png)

# [Project 5 : Payment Matching](https://github.com/FeniRahmi/payment_matching)
At Shopee, the buyer who chooses to place an order using bank transfer is supposed to make the transfer within 2 days after he/she places the order. After that, Shopee will receive a bank statement from the bank and Shopee needs to compare and match the bank statement with the checkout information in order to confirm that this particular order has been paid. Two criteria need to be met in order to match a bank statement with a checkout : amount match and name match. A proper match occurs when both the amount and the name matches on both bank statement and checkout list. Based on the two criteria, I have matched the bank statement IDs to the checkout IDs.
