# diamond-price-prediction
Creating a diamond price prediction model using Python involves using regression techniques.
In this code:

We load a diamond dataset (you should replace 'diamonds.csv' with the path to your dataset).
We select a few relevant features for prediction ('carat', 'cut','clarity', 'depth', 'table' ).
We convert categorical variables ('cut' and 'clarity') into dummy variables.
We split the data into training and testing sets.
We create a Linear Regression model and train it on the training data.
We make predictions on the testing data.
We evaluate the model using Mean Squared Error (MSE) and R-squared (R2) as metrics.
Finally, we create a scatter plot to visualize the predicted prices vs. actual prices.
