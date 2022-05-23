# **Bike Sharing Demand Prediction**

# **Project Title : Seoul Bike Sharing Demand Prediction**

# **Problem Description**

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

***Data Description***

The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

***Attribute Information:***

Date - year-month-day

Rented Bike count - Count of bikes rented at each hour

Hour - Hour of he day

Temperature-Temperature in Celsius

Humidity - %

Windspeed - m/s

Visibility - 10m

Dew point temperature - Celsius

Solar radiation - MJ/m2

Rainfall - mm

Snowfall - cm

Seasons - Winter, Spring, Summer, Autumn

Holiday - Holiday/No holiday

Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

# **Data Summary:**

**Data Set Name :-** SeoulBikeData.csv

**Statistics – **
**Rows -** 8760
**Features –** 14

**Columns:-**

'Date', 'Rented Bike Count', 'Hour', 'Temperature(°C)', 'Humidity(%)', 'Wind speed (m/s)', 'Visibility (10m)','Dew point temperature(°C)',
'Solar Radiation (MJ/m2)', 'Rainfall(mm)', 'Snowfall (cm)', 'Seasons', 'Holiday', 'Functioning Day'

# **Problem Statements**

Our task is to predict the demand of bike rent based on the historical usage over different factors such as seasons, weather, temperature, humidity etc.

![image](https://user-images.githubusercontent.com/101592102/169794048-d2c39944-198c-403a-ad4a-a5ac2e6b4248.png)

# **Methodology**

![image](https://user-images.githubusercontent.com/101592102/169794533-241222d4-66ed-4997-9c10-0b1e0fa598ac.png)

# **ML Prediction Model**

* Linear Regression
* Lasso Regression
* Ridge Regression
* Decision Tree Regression
* Random Forest Regression
* Gradient Boosting Regression
* XGBoost Regression

# **Model Evaluation Result**

![f result](https://user-images.githubusercontent.com/101592102/169795477-3d743f28-e9ef-4e9f-aff3-e3b90aaa1ad9.png)

![r res plot](https://user-images.githubusercontent.com/101592102/169795366-7653a274-9acd-41c3-9d73-0b59c5c841c3.png)

# **Conclusion**

As we can see the total amount of bike rentals increases with the temperature per month. Whereas it seems that the rentals are independent of the wind speed and the humidity, because they are almost constant over the months. This also confirms on the one hand the high correlation between rentals and temperature and on the other hand that nice weather could be a good predictor. So people mainly rent bikes on nice days and nice temperature. This could be important of planning new bike rental stations.

It is quite evident from the results that XGBoost is the best model that can be used for the Bike Sharing Demand Prediction since the performance metrics (mse, rmse) shows lower and (r2,adjusted_r2 = 92 %) show a higher value for the XGBoost model. So, finally this model is best for predicting the bike rental count on daily basis.

# **References**

https://www.kaggle.com/

https://www.analyticsvidhya.com/

https://www.geeksforgeeks.org/

https://learn.almabetter.com/


