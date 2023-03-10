# Gas_Prices_in_Brazil

The Brazilian National Agency of Petroleum, Natural Gas and Biofuels releases weekly reports of gas, diesel and other fuels prices used in transportation across the country. These datasets provide the mean value per liter, number of gas stations analyzed, and other information grouped by regions and states across the country. These gas prices can be very unpredictable and experience significant change frequently. Understanding the variables that affect these prices and the autocorrelation in the data can improve understanding of future prices in the market and enable forecasting of gasoline prices.

The primary task for this project is developing a forecasting model for future Brazilian gas prices. Several benchmarks models are implemented - Mean, Naive, Seasonal Naive, Drift, Exponential Smoothing (ETS), AutoRegressive Integrated Moving Average (ARIMA), and Neural Networks. The time series created from the data set is a monthly one with test period as 2019 and train period of  2004-2018. In conclusion, it is discovered that a simpler model actually performs better and is more accurate for this data set than an ARIMA or ETS model. A possible explanation for this result is that the trend component is the only significant component that we have identified in the model apart from the error component. In the absence of a strong seasonal trend or additional component, a simple Naive method performed the best among the models we tested. The Naive model had a MAPE value of 5.26%
As part of future scope of work, hierarchial time series forecasting can be performed to validate if it enhances the forecast of the gas prices.

Dataset: https://www.kaggle.com/datasets/matheusfreitag/gas-prices-in-brazil

