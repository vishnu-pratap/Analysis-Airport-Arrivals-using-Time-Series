# Analysis-Airport-Arrivals-using-Time-Series
In this project, I forecast aircraft arrivals using ARIMA models.The dataset used is ‘Monthly No. of Aircraft Arrivals at Changi Airport from 1980 to 2015’, published by Civil Aviation Authority of Singapore (CAAS) on Data.gov.sg
Model building consisted of 4 steps : 
1) Splitting Data : Training: 2004 to 2014 (11 years),Testing: 2015 (1 year)
2) Data Transformation :No Transformation, Logarithm, Square-root
3) Data Differencing: Apply Differentiation and/or Seasonal Differentiation Fix d & D
4) Stationarity Check : Using Augmented Dickey Fuller Test (ADF) to test transformed and differenced data

Tool : R
Conclusion : ARIMA(1,1,0)(0,1,1)[12] model built with sqaure-root transformed data provided good predictions of 2015 arrivals 

