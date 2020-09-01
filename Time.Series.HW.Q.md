# Part 1:

## 1) Based on your time series analysis, would you buy the yen now?

No, i would not buy the Yen now. Based on the ARIMA model and its prediction of where the dollar/yen future price is predicted to be over the next 5 days, the model tells me that the Yen will depreciate from 9224yen to the dollar to 9228yen to the dollar.  Aditionally, the returns are expected to be relatively decreasing over time (as seen in the plot subsequent to the ARMA modeling) while the GARCH plot shows volatility is expected to rise over the 5 days.  All these things contribute to what looks like an investment with poor potential.


## 2) Is the risk of the yen expected to increase or decrease?

The risk (volatility) of the yen is expected to increase over the next 5 days as predicted by the GARCH model. Day one's expexted risk is supposed to be 7.43 on day one and it increases over to be 7.59 by the 5th day.

## 3) Based on the model evaluation, would you feel confident in using these models for trading?

ARMA Model: No, I would not be confident using this model because when looking at the "results summary" all of the p-values are greater than 5% meaning that the coefficients for those parameters are not statistically relevant.
ARIMA Model:  No, I would not be confident using this model because when looking at the "results summary" all of the p-values are greater than 5% meaning that the coefficients for those parameters are not statistically relevant.
GARCH Model: No, I would not be confident using this model because when looking at the "results summary" 4 of the 5 p-values are greater than 5% meaning that the coefficients for those parameters are not statistically relevant thus making the model untrustworthy.

# Part 2:

## 1) Does this model perform better or worse on out-of-sample data compared to in-sample data?

** Hints and Considerations:

* Out-of-sample data is data that the model hasn't seen before (Testing data).
* In-sample data is data that the model was trained on (Training data).


This model performs better on Out-of-Sample data (Testing data) as it has a lower Root Mean Squared Error (RMSE) than the In-Sample data (Training data).
The testing data's RMSE is 0.4154832784856737 and the Training data's RMSE is 0.5963660785073426.