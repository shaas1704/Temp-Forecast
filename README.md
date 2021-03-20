# Temperature Forecasting<br>
I was given a task to predict the temperature of a city for the next 10 years (2011 to 2020) based on the previous 30 years data (1981 to 2010).<br>

I have done so using the versatile FbProphet package and have tuned the model according to the dataset given to me.<br>

Dataset given for Training the data - "train.csv".<br>
Dataset given for Testing the data (Values to be predicted for the given dates) - "test.csv".<br><br>



# Predictions and Methodology<br>

First step was to determine the seasonality of the city using graphs and then using that the model had to made and fit on the dataset. <br>
I have uploaded 3 predictions: Final, last 10 years and last 4 years to see the change in the results.<br><br>

# Results<br>

The predicted values were compared to the actual values using the Root Mean Squared Error (RMSE) method and the results were as follows:<br>

Final - 3.99 <br>
Last 10 years - 4.08 <br>
Last 4 years - 4.11 <br>

<br><br><br><br>

Done using Google Colab :)
