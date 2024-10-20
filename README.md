Bank Customer Classification
This is a classification model to predict which bank customers are most likely to churn.
Step 1:
# Importing the “Bank_Churn.csv” file and set an appropriate data type for each column
# Checking for missing values and calculate the min, max, and mean for numeric columns
# Building box plots for each numeric column broken out by the target variable, “Exited”
# Building bar charts that show the percentage of “Exited” by category for each categorical column
step 2:
# Dropping columns that aren't suitable for modeling from the dataset
# Creating a new column, "balance_to_income", by dividing "Balance" by "EstimatedSalary"
# Creating a new column, "income_v_products", by dividing "EstimatedSalary" by "NumOfProducts"
# Creating dummy variables for categorical columns
# Splitting the data into train and test sets, with 20% of the rows in the test set
step 3:
# Fitting a logistic regression model on your training data
# Building a confusion matrix to evaluate your model
# Calculating accuracy, precision, recall, and F1 for your test data
# Plotting an ROC curve and calculate the AUC statistic
# Plotting precision and recall against the model threshold (set the threshold to the value where recall is the highest, but precision is still above 50%)
step 4
# Fitting a random forest model with default hyperparameters
# Using cross validation to tune model's hyperparameters
# Reporting the final test accuracy and AUC score
# Building a bar chart that shows feature importance

