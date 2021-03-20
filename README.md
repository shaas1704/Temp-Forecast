# Temperature Forecasting
I was given a task to predict the temperature of a city for the next 10 years (2011 to 2020) based on the previous 30 years data (1981 to 2010).

I have done so using the versatile FbProphet package and have tuned the model according to the dataset given to me.

Dataset given for Training the data - "train.csv".
Dataset given for Testing the data (Values to be predicted for the given dates) - "test.csv".



# Predictions and Methodology

First step was to determine the seasonality of the city using graphs and then using that the model had to made and fit on the dataset.
I have uploaded 3 predictions: Final, last 10 years and last 4 years to see the change in the results

# Results

The predicted values were compared to the actual values using the Root Mean Squared Error (RMSE) method and the results were as follows:

Final - 3.99
Last 10 years - 4.08
Last 4 years - 4.11



Done on Google Colab :)
