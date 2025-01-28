# Time-Series-Prediction

<h2>Description</h2>
This project aimed at predicting the future price of forex pairs and commodities using the ARIMA model. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b>
  <h2>Python Packages Used</h2>
  <b>datetime, math, matplotlib, statsmodels, statsmodels.api, statsmodels.tsa.arima_process, yfinance, pmdarima.arima, statsmodels.tsa.statespace.sarimax import SARIMAX
</b>

<h2>Environments Used </h2>

- <b>Jupyter Notebook</b>

<h2>Program walk-through:</h2>

<p align="center">
Getting data from yfinance: <br/>
<img src="https://i.imgur.com/eYqVcPl.png" height="80%" width="80%" alt = "Data Collection"/>
<br />
<br />
Fitting linear regression model to au_usd:  <br/>
<img src="https://i.imgur.com/8Mt6kpH.png" height="80%" width="80%" alt="Trend Removal"/>
<br />
<br />
Checking Residuals of above regression for trend: <br/>
<img src="https://i.imgur.com/YxUavbf.png" height="80%" width="80%" alt="Trend Removal"/>
<br />
<br />
Checking First difference of time series:  <br/>
<img src="https://i.imgur.com/XQZ6lxn.png" height="80%" width="80%" alt="Trend Removal"/>
<br />
<br />
Plotting Autocorrelation function of first difference:  <br/>
<img src="https://i.imgur.com/oh14Ct6.png" height="80%" width="80%" alt="Trend Removal"/>
<br />
<br />
Choosing the best ARIMA setting using auto_arima package from pmdarima.arima:  <br/>
<img src="https://i.imgur.com/59xGyLR.png" height="80%" width="80%" alt="Modelling"/>
<br />
<br />
Plotting price prediction (within predetermined confidence intervals) versus Actual Data:  <br/>
<img src="https://i.imgur.com/KzzzwNc.png" height="80%" width="80%" alt="Modelling"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
