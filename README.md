# retail-sales-forecasting

**Retail Sales Forecasting (Python, Statsmodels):**  
Analyzed daily online sales data using seasonal decomposition, moving averages, and ADF test for stationarity. Built Holt‑Winters Exponential Smoothing model to forecast 30 days ahead, visualized trend/seasonality, and detected demand spikes.

##  Methods
- Seasonal decomposition (trend + seasonality)
- 30‑day moving average smoothing
- Augmented Dickey‑Fuller (ADF) test for stationarity
- Holt‑Winters Exponential Smoothing (additive trend & seasonality)

##  Results
- Series found **non‑stationary** (ADF p‑value > 0.05)  
- Generated **30‑day forecast** with clear trend & seasonality  
- Detected sudden demand spikes (e.g., Mar 3, Apr 8, Jun 13)  
- No major drops observed

##  Tools
- Python  
- Pandas  
- Matplotlib  
- Statsmodels
