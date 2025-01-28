# Walmart-Sales-Prediction   
The two source codes use different methods for sales prediction.  
1. w GBR model  
  In this folder the code shows a sales prediction service for inventory management.
  By entering in date, id, ,,, user can get the expected number of sales.
  The prediction model used Gradient Boosting Regressor which showed the best performance among Gradient Boosting Regressor, Random Forest Regressor, KernelRidge, Linear Regressor
  In addition to original data, three features (Population, Temperature, Unemployment rate) were retrieved from additional sources and were selected through EDA and correlation analysis for more accurate performance.

2. SVD smoothing and Sales Forcasting  
   This code more focuses on scratch coding of SVD.
   Train data splited into weekly sales of each department goes through the SVD function and becomes smoother data.
   Smoothened train data and test data are pre-processed with the same pre-process function.
   The result data are used for sm.OLS linear regression function.
