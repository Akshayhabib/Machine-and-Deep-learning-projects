First, I load the training data and make a copy of it, then I begin preprocessing the data and fill in the missing values in the given data set, and finally, I use the label encoder on object data points and scale them while also performing all of the above on test data sets.

After finishing all of the data preprocessing steps, I divided the training data into train and test segments,and started building the model.

 I train the data on X train and Y train and make predictions on X test and Y test to see how my models perform.
 
 After employing models such as Linear Regression, Lasso Regression, Ridge Regression, Support Vector Regressor, and Random Forest Regresso, GradientBoostingRegressor
 
 "Linear, Lasso, Ridge, GradientBoostingRegressor" provide the best Rmse value for me.
   
   However, GradientBoostingRegressor provide the lowest rmse value.
 
 I choose the GradientBoostingRegressor model and made the prediction after which I converted the datafame into an excel file.
