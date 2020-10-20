# Predicting-price-of-used-cars

Problem Statement:
There is a huge demand of used cars in the Indian Market today. As sale of new car have slowed down in the recent past, the pre-owned car market has continued to grow over the past year and is larger than the new car market now. Consider this: In 2018-19, while new car sales were recorded at 3.6 million units, around4 million second-hand cars were bought and sold. There is a slowdown in new car sales and that could mean that the demand is shifting towards the pre-owned market. In fact, some car sellers replace their old cars with pre-owned cars instead of buying new ones.
The goal here is to predict the Price of an Old car based on the variables provided in the data set.
Working with Data
Data has been split into two groups and provided in the module:

training set 
test set 
The training set is used to build your machine learning model. For the training set, we provide the price of a car (also known as the variable Price) for each participant.
The test set should be used to see how well your model performs on unseen data. For the test set, it is your job to predict price of the car (Price) for each participant.

Metric to measure
The measure of accuracy will be RMSE (root mean square error). The predicted Price for each car in the Test dataset will be compared with the actual Price to calculate the RMSE value of the entire prediction. The lower the RMSE value, the better the model will be.
Mathematical definition of Root Mean Square Error: √(2&Σ(pi- p ̂ )2/n)
Here, pi refers to the actual Price of the cars and p̂ refers to the estimated Price. ‘n’ is the number of observations of the test data set.

Submission File Format:
You are to submit a csv file with exactly 5615 entries plus a header row. The file should have exactly two columns
	Unique Id
	Price





