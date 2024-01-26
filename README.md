An additive time series model was used to determine seasonality.
It can be represented by: y(t) = Level + Trend + Seasonality + Noise (A linear trend. In our situation, the linear seasonality has the same amplitude and frequency)

Source for seasonality is excel-file with monthly registration stat.
Using Statsmodels library and function seasonal_decompose we able to find 3 components, plot graphs and output absolute values.

This script also could be run in PowerBI wwith dataset from SSAS.
