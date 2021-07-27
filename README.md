# Time Series Models with LSTM

- Dataset : [Kaggle - Temperature Aomori City](https://www.kaggle.com/akioonodera/monthly-temperature-of-aomori-city)

## Details

In this project I only tested the LSTM models using a time series datasets containing monthly temperatures from Aomori City. Long Short-Term Memory networks, or LSTMs for short, can be applied to time series forecasting.

To evaluate a time series model, we can calculate the errors made in the model just as we evaluate a regression model. We can get the error by calculating the distance between the predicted value of the model and the true value.

The evaluation metric used for the time series model is MAE or Mean Absolute Error. The MAE value of the optimal model is one that has a number below 10% of the data scale.

## Results

The results of the model training are as follows which show the model has a relatively low MAE compared to the data scale.

![image](https://user-images.githubusercontent.com/87906938/127169051-6d2fe27f-a4e7-40ff-8535-c2937e5b6637.png)


_Evaluation_

This project is still lacking in the data visualization section, where time series graphs should be carried out every month every year, so that the trend of temperature changes can be more visible.

It will be repaired immediately to make it better.
