{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "7fc420b3",
   "metadata": {},
   "source": [
    "First, I load the training data and make a copy of it, then I begin preprocessing the data and fill in the missing values in the given data set, and finally, I use the label encoder on object data points and scale them while also performing all of the above on test data sets.\n",
    "\n",
    "After finishing all of the data preprocessing steps, I divided the training data into train and test segments,and started building the model.\n",
    "\n",
    "I train the data on X train and Y train and make predictions on X test and Y test to see how my models perform.\n",
    "\n",
    "after employing models such as Linear Regression, Lasso Regression, Ridge Regression, Support Vector Regressor, and Random Forest Regresso, GradientBoostingRegressor\n",
    "\n",
    "Linear, Lasso, Ridge, GradientBoostingRegressor provide the best Rmse value for me.\n",
    "\n",
    "\n",
    "However, GradientBoostingRegressor provide the lowest rmse value\n",
    "\n",
    "I choose the GradientBoostingRegressor model and made the prediction after which I converted the datafame into an excel file."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "a8503003",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.9.12"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
