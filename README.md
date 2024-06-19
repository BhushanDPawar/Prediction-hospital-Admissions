# Prediction-hospital-Admissions
**Introduction**
Hospital admission rates can be influenced by various environmental factors. This project leverages machine learning models to predict these rates based on parameters such as temperature, humidity, and pollutant levels. By analyzing the impact of these variables, we aim to provide insights that could help in managing healthcare resources more effectively.

**Data Sources**
The data used in this project comes from multiple sources:

**Pollutant Data:** Downloaded from Sentinel 5P.
**Meteorological **Data: Downloaded from MODIS, NOAA, and ERA5 using Google Earth Engine (GEE).
**Ground Station** Data: Provided by ERA, Malta.
**Hospital Data:** Provided by DHIR, Malta.
P**arameters**
The following environmental parameters are used for predicting hospital admission rates:

Temperature
Relative Humidity
Surface Pressure
Wind Speed
Dew Temperature
CO
SO2
NO2
O3
PM2.5
PM10
**Machine Learning Models**
We have employed a variety of machine learning models to find the best predictor for hospital admission rates:

Linear Regressor
MLP Regressor
Decision Tree Regressor
Random Forest Regressor
KNN Regressor
Lasso Regression
Ridge Regression

**Results**
The results of the machine learning models, including their R2 scores and mean squared errors, will be displayed after running the evaluation script. The best performing model will be highlighted.

**Contributing**
Contributions are welcome! If you have any suggestions or improvements, please create a pull request or open an issue.

**License**
This project is licensed under the UM License. See the LICENSE file for more details.
