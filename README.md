# VCB Stock Price Forecasting with ARIMA
Collecting and processing VCB stock data from Yahoo Finance and applying the ARIMA model to forecast prices.

## Post-Training Diagnostics

<div align="center">

<img width="752" height="562" alt="rs1" src="https://github.com/user-attachments/assets/bc21cdc4-8408-4ca8-80b2-a4230d701ac3" />
<br>
<small>Figure 1: Diagnostics plot after training</small>

<br><br>

<img width="807" height="482" alt="rs2" src="https://github.com/user-attachments/assets/1a730381-5224-4dc4-818b-052506c89ba6" />
<br>
<small>Figure 2: Detailed statistical summary</small>
</div>

- Prob(Q) = 0.92 > 0.05 => residuals are approximately random, indicating that the ARIMA model captured most of the autocorrelation patterns in the data.

- Prob(JB) = 0.00 < 0.05 => residuals are not normally distributed; the model may not fully satisfy normality assumptions, but this has limited impact on forecasting performance.

## Forecast Results (60 Days)

<div align="center">

<img width="1266" height="647" alt="rs3" src="https://github.com/user-attachments/assets/77fcfa48-844d-4efd-945d-3483670e1378" />
<br>
<small>Figure 3: 60-day forecast</small>

</div>
