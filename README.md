## Bike Sharing Prediction by Using Time Series Analysis
- **Objective**: Leveraging Time Series Analysis (TSA) approach to predict total bike rentals.

`Dataset`: Bike Sharing <br>
`Available from`: https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset

### Here I implemented:
1. Meta Prophet for univariate and multivariate variables.
2. Auto-ARIMA for multivariate variables.
   
### Conclusion:
- Initially, we used Prophet univariate model for prediction and the result was 0.29. With the addition of variables such as weather and temperature, the model performance improved to 0.61.
- We compare the results of different time series models. In the Auto-ARIMA model, the best result is 0.63, which is not much different from the performance of Prophet.

### Future Steps:
- Time series models are suitable for predicting values that are highly periodical and have few changing factors. On the contrary, if the greater impact is non-periodic events, such as irregular rainy days, fog, etc., it may be more appropriate to choose another regression model.
