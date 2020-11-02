<h6>Auto Regressive Model-using TF 2.0</h6>

<p align=justify>An autoregressive (AR) model predicts future behavior based on past behavior. It’s used for forecasting when there is some correlation between values in a time series and the values that precede and succeed them.</p>

<p align=justify>
The AR(p) model is defined by the equation:
yt = δ + φ1yt-1 + φ2yt-2 + … + φpyt-1 + At<br>
Where:
<ul>
<li> yt-1, yt-2…yt-p are the past series values (lags).</li>
<li> At is white noise (i.e. randomness).</li>
</ul>
</p>
