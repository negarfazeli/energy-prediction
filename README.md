## Summary
Investors in Energy Infrastructure are using outdated tools to bet on future electricity markets. By current market standards, commodity prices are treated as over-simplified features that are
incapable of generating reliable long-term predictions. Our group wants to change this practice
by predicting retail energy prices to a five year horizon. This project utilizes statistical feature
selection methods, time series modeling, and time-variant feature segmentation to develop a
flexible tool that can yield insight into financial and policy-based decisions.

### Feature Engineering, Selection and Prediction
#### Selection and Engineering
- LASSO regularized regression and VIF are used for feature selection. 

#### Time series SARIMA is used for feature predictions
- Implementatin is don in following notebooks:

```
time_series_feature_predictor.ipynb
ARIMA & S-ARIMA.ipynb
```

### Price Prediction
- Price prediction is implemented using Linear Regression, implementation is in:

```
baseline_model.ipynb
```
