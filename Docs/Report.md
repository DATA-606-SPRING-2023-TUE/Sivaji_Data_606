# **Rain fall prediction and Analysis using Machine learning Modeles**

#### PPT Link: https://github.com/DATA-606-SPRING-2023-TUE/Sivaji_Data_606/blob/main/Docs/SIVAJI%20FINAL%20PROJECT%40final.pptx

#### Youtube video link: 

# Contents:
1.Introduction

2.Abstract

3.Data Source

4.Methodology

5.Data Visualization

6.Feature Engineering

7.Machine Learning Models

8.Conclusion

9.Future Scope



# 1.Introduction:
Rainfall prediction is an important part of weather forecasting. It involves using multiple methods and strategies to forecast the amount of precipitation that will fall in a given location. 

Also, Rainfall prediction accuracy has improved significantly over the years as a result of technological improvements and the development of sophisticated models and algorithms.

This information is essential for various sectors like agriculture, water management, disaster management, and more. Like Accurate rainfall prediction is crucial for agricultural activities as farmers heavily rely on weather forecasts to make informed decisions regarding irrigation, crop planting, and harvesting. Timely and precise predictions help optimize water usage, enhance crop yield, and minimize the risk of agricultural losses.

Water resource management heavily depends on rainfall predictions to efficiently allocate water supplies for irrigation, hydroelectric power generation, and urban water consumption. By monitoring rainfall patterns, authorities can manage reservoir levels, plan water supply to cities, and implement water conservation measures during drought conditions.



# 2.Abstract:
Rainfall forecast is influenced by several factors, including atmospheric pressure, humidity, wind patterns, and temperature.

In general, data must be collected from a variety of sources, including meteorological stations, satellites, and radar systems, in order to predict rainfall. then, the data is analyzed using statistical models and machine learning algorithms to identify patterns and trends that can be used to forecast future rainfall events.

The main goal of this Project is to develop a predictive model on the Rainfall Dataset in order to forecast whether or not it will rain in  Australia tomorrow. The collection of data contains around ten years of daily weather measurements from numerous places throughout Australia.



# 3.Dataset
This data is collected from Australian Government Bureau of Metrology.

Data source: http://www.bom.gov.au/climate/dwo/ and http://www.bom.gov.au/climate/data.

Definitions adapted from http://www.bom.gov.au/climate/dwo/IDCJDW0000.shtml

This Data set consist of 145460 rows and 23 columns

This dataset has data from 2000-01-01 to 2017-06-06.

This dataset includes (Data, Location, min temparature, Max temparature, Rainfall, Evaporation, Sunshine, Wind Gust, Humidity, pressure, Cloud timings, RainToday, RainTomorrow).



# 4.Methodology:
There are many different methods for using machine learning algorithms for rainfall prediction. The following is an overview of the typical stages required in creating a machine learning model for rainfall prediction:

**1.Data Collection:** The first step is to collect appropriate data for training the model. This covers rainfall data from previous years as well as other meteorological         factors including temperature, humidity, wind speed, air pressure, and cloud cover.
  
**Data Preprocessing:** After collecting the data, it must be preprocessed to ensure its quality and effectiveness for training the machine learning model. Data                cleaning,removing outliers, dealing with missing numbers, and normalizing or scaling the data are all part of this stage.
  
**Feature Selection:** The most relevant features or variables from the dataset are selected in this step. This can include statistical analysis, domain knowledge, and         correlation analysis to determine which features have the most effect on rainfall forecast. 
  
**Model Selection:** Regression models (such as linear regression, decision trees, and random forests), time series models such as autoregressive integrated moving average     (ARIMA), support vector machines (SVM), neural networks, and ensemble methods can all be used to predict rainfall. The model used is determined by the problem's             specific requirements as well as the dataset's features.
  
**Model Evaluation:** The trained model's performance is evaluated using the validation set. Mean absolute error (MAE), root mean squared error (RMSE), coefficient of           determination (R-squared), and correlation coefficients are common evaluation metrics for rainfall prediction.
  
  
  
  # 5.Data Visualization:
  This graph shows the Plotting Distribution of null values in the data set using pictorial representation.
  
  Here the columns: Evaporation, Sunshine,Cloud9am,cloud3pm contribute highest number of null values in this data set.


  ![image](https://github.com/DATA-606-SPRING-2023-TUE/Sivaji_Data_606/assets/112666192/6793a398-01cf-4826-aeae-fb7827487b4c)



This graph shows the instances of the target variable, that is rain tomorrow.

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sivaji_Data_606/assets/112666192/fafa6864-6a1b-41d9-90fc-01d61e4cdbc4)



This graph depicts that when there is minimum temperature, we can expect the rain fall as per the data.

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sivaji_Data_606/assets/112666192/ff3c076c-dee0-42fc-acb2-c2876bf5790c)



The graph depicts that when there is maximum temperature, we cannot expect the rain fall as per the data.

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sivaji_Data_606/assets/112666192/69011cc9-d6ea-4152-b483-00bad13307a3)



The graph depits that when there is rainfall the sunshine gradually decreases.

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sivaji_Data_606/assets/112666192/574d0736-3143-4a4d-b2aa-621ee9f00e72)



The graph depicts that when there is gradual increase in sunshine  the amount of evaporation also increases.

![image](https://github.com/DATA-606-SPRING-2023-TUE/Sivaji_Data_606/assets/112666192/4c6aa146-015f-450f-80a2-f32ae072537c)




