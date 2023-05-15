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

**1.Data Collection:** The first step is to collect appropriate data for training the model. This covers rainfall data from previous years as well as other meteorological    factors including temperature, humidity, wind speed, air pressure, and cloud cover.
  
**2.Data Preprocessing:** After collecting the data, it must be preprocessed to ensure its quality and effectiveness for training the machine learning model. Data            cleaning,removing outliers, dealing with missing numbers, and normalizing or scaling the data are all part of this stage.
  
**3.Feature Selection:** The most relevant features or variables from the dataset are selected in this step. This can include statistical analysis, domain knowledge, and    correlation analysis to determine which features have the most effect on rainfall forecast. 
  
**4.Model Selection:** Regression models (such as linear regression, decision trees, and random forests), time series models such as autoregressive integrated moving average (ARIMA), support vector machines (SVM), neural networks, and ensemble methods can all be used to predict rainfall. The model used is determined by the problem's      specific requirements as well as the dataset's features.
  
**5.Model Evaluation:** The trained model's performance is evaluated using the validation set. Mean absolute error (MAE), root mean squared error (RMSE), coefficient of      determination (R-squared), and correlation coefficients are common evaluation metrics for rainfall prediction.
  
  
  
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



  # 6.Feature Engineering
  We have approached this method of feature selection using XGB Classifier and Here are the important features that have more impact on the target variable.

  ![image](https://github.com/DATA-606-SPRING-2023-TUE/Sivaji_Data_606/assets/112666192/ea3f346a-11c7-489a-8c02-8e30df920dae)
  
  
  
  # 7.Machine Learning Models
  Several machine learning models can be used to figure out what the weather will be like. The choice of model relies on a number of things, such as the data that is         available, the specifics of the problem, and the level of accuracy that is needed. Here are some of the most well-known machine learning models that I have been used to     predict rainfall:
  
  **1.Logistic Regression:** Logistic regression is a machine learning approach that is used for binary classification. It is not, as the name implies, a set of rules for     regression problems with non-stop results. Instead, logistic regression is the preferred method for binary classification. This gives a discrete binary value between 0     and 1. Logistic regression estimates probabilities using its core logistic feature to assess the relationship between dependent variables and one or more independent       variables. These probabilities are then transformed into binary numbers for an estimation.
  
  Its range is fixed to be between zero and one. Additionally, R performs well when there is a large gap between the groups. here we have gained accuracy for LR is  84%.

  Here is the confusion matrix for Logistic regression:
  
  ![image](https://github.com/DATA-606-SPRING-2023-TUE/Sivaji_Data_606/assets/112666192/95d6faf7-87d0-449b-866c-dda6aee12206)



  **2.Random Forest:** Random forest is an algorithm used in behavior analysis that is built on modeling assumptions and decision trees. It consists of several decision       trees representing a different example of the classification of data input into a random forest.and here we achieved Accuracy of 86% for Random Forest.

  Here is the confusion matrix for Random Forest:

  ![image](https://github.com/DATA-606-SPRING-2023-TUE/Sivaji_Data_606/assets/112666192/e3759fab-9c72-454d-9f43-0f5e8a95ed45)



  **3.Decision Tree:** Decision trees are models that begin with root split into branches at nodes representing the predictor variables using the rules. 
  
  Each node Is then divided into multiple nodes. The goal is to use the decision tree to divide the data space into dense and thin regions.

  As the number of splits increases the time required to build the tree also increases. And here we achieved Accuracy of 78% for Decision tree .
  
  Here is the confusion matrix for Decision Tree:
  
  ![image](https://github.com/DATA-606-SPRING-2023-TUE/Sivaji_Data_606/assets/112666192/ada78e0d-1daa-4033-ba9d-da9ca543734c)



  **4.XGB Classifier:** XGBoost stands for extreme Gradient Boosting and it’s an open-source implementation of the gradient boosted trees algorithm. It has been one of the   most popular machine learning techniques in Kaggle competitions, due to its prediction power and ease of use. It is a supervised learning algorithm that can be used for     regression or classification tasks. and we achieved Accuracy of 86% for XGB Classifier
  
  Here is the confusion matrix for Decision Tree:
  
  ![image](https://github.com/DATA-606-SPRING-2023-TUE/Sivaji_Data_606/assets/112666192/7f51bb77-af18-4399-b655-7291a55dc7f5)

  

  **5.GB Classifier:** Gradient boosting is a machine learning technique used in regression and classification tasks, among others. It gives a prediction model in the form   of an ensemble of weak prediction models, which are typically decision trees.
  
  When a decision tree is the weak learner, the resulting algorithm is called gradient-boosted trees; it usually outperforms random forest.
  
  A gradient-boosted trees model is built in a stage-wise fashion as in other boosting methods, but it generalizes the other methods by allowing optimization of an           arbitrary differentiable loss function. and we achieved Accuracy of 85% for GB Classifier

  Here is the confusion matrix for GB Classifier:
  
  ![image](https://github.com/DATA-606-SPRING-2023-TUE/Sivaji_Data_606/assets/112666192/b6debd28-a843-4cd2-b92d-0fd24bc08c24)

  

  # 8.Conclusion:
  In conclusion, rainfall prediction is an important task in meteorology and has significant implications for various sectors such as agriculture, water resource             management, and disaster preparedness. Based upon the prediction results, the Machine learning models  we conclude that our prediction is correct, and the factors which     we have considered has significant impact in predicting the Rainfall.
  
