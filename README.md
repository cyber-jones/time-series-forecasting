# Time Series Forcasting

To model and forecast monthly airline passenger demand using historical data to understand long term growth and recurring seasonal travel patterns.

Time series forecasting predicts future values by learning patterns like trend and seasonality from historical, time ordered data.
Unlike regular ML, the order of data matters, and past values directly influence future predictions.

## ARIMA

Full form: AutoRegressive Integrated Moving Average

One-liner: Predicts future values by removing trend and learning from past values and past errors.

(P, D, Q)

- P → past values used
- D → trend removal
- Q → past errors used

⸻

## SARIMAX

Full form: Seasonal AutoRegressive Integrated Moving Average with eXogenous variables

One-liner: ARIMA extended to learn repeating seasonal patterns and optional external inputs.

Seasonal (P, D, Q, S)

- P, D, Q → seasonal memory and corrections
- S → season length (12 for monthly data)

⸻

Quick rule

- ARIMA → no seasonality
- SARIMAX → seasonality present
