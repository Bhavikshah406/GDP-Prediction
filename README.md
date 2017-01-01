# GDP-Prediction
Come up with a result as to which window size is the best that should be used as a training set to predict the GDP in the future and also point out which sector contributes most towards the GDP of INDIA.

File GDP_and_Major_Industrial_Sectors_of_Economy_Dataset.xls contains contributions of various following sectors in crores to India's Gdp
-Agriculture & Allied Services
-Agriculture
-Industry
-Mining and Quarrying
-Manufacturing
-Services

The methods used to Predict the Gdp are Arima and Holtwinters.
Experiments with these number show that Arima model is ay better than predicting Gdp;

Running the GdpPrediction R file on the GDP_and_Major_Industrial_Sectors_of_Economy_Dataset.xls will lead to following conclusions.

Conclusions
1)On predicting GDP based on time series , we have found a correlation (both positive and negative) among various sectors contributing to the GDP.In short, as some sectors reduced contribution, other sectors have increased contribution towards GDP. 
2)The ARIMA model had the lowest  MAPE and RMSE  of all forecasting methods, thus prediction based on the ARIMA model is the best since it  detects both the trend and the seasonality of the series.
3)For predicting the gdp , stats suggest that higher the window size better is the predicted value.It is observed that a window size of 60 is optimal.



