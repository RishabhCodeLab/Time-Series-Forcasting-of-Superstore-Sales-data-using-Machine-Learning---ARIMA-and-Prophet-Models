# Time Series Forcasting of Superstore-Sales data using Machine Learning - ARIMA and Prophet Models
Time series analysis is a statistical method to extract meaningful statistics and predict future values using previously observed values. It is widely used for non-stationary data like economics, weather, stock price, and retail sales. We have used ARIMA and Prophet models for forecasting Superstore Sales data.

**Data source -**
[Superstore](https://community.tableau.com/s/question/0D54T00000CWeX8SAL/sample-superstore-sales-excelxls)

**In order to start this project we have to install some static model libraries which are helpful in running Prophet model such as -**
```Python 
pip install statsmodels
pip install Cython
pip install convertdate
!pip install prophet
from prophet import Prophet
import statsmodels.api as sm
```
**We also use data analysis and data visualization libraries in order to get good insights of data, such as -**
```Python
%matplotlib inline
import matplotlib.pyplot as plt
import warnings
import itertools
import numpy as np
warnings.filterwarnings("ignore")
plt.style.use('fivethirtyeight')
import pandas as pd
from pylab import rcParams
```
