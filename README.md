# credit-card-fraud-detection
# Link to the dataset
https://www.kaggle.com/mlg-ulb/creditcardfraud
# Problem Statement
Let’s go through the problem statement once as it is very crucial to understand the objective before working on the dataset.The problem statement is as follows:

The dataset consists of 284807 rows and 31 columns.Our objective is to find whether credit card is fraud or not.

# Procedure implemented in acheiving our objective:
Load required libraries and the dataset.

Check for any null values.As we see there are no null values,there is no need to do imputing.

visualize the correlations between independent and dependent columns to check how they are correlated.

Now divide the dataset into x_train,x_test,y_train and y_test using train_test_split and scale the columns using standard scalar

Import logistic regression module and fit (x_train,y_train) into it.

use predict function to make predictions of x_test.

use classification_report function for knowing precision and recall of the model.

Also calculate accuracy for the model.We have got accuracy of 99%.which means model is accurate

check the accuracy using random forest model.here random forest model's accuracy is lower than logistic regression. So Logistic regression model can be saved using pickle module.






