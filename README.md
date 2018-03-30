# To Assess the Relationship between the Economic Growths of India and Neighbouring Countries

The statistics indicate disparity in GDP, with China having the highest GDP. The standard deviation of Chinese GPD is the highest, indicating substantial fluctuation over the time period under study.First step of our analysis consisted of determining the order of integration of the three variables by means of the ADF test. The test was first performed with only a drift term and then with constant and trend for the series in levels and first difference. *We concluded that log of GDP's of India, China and Pakistan are integrated of order one.* 


We then performed Engle-Granger two step test for cointegration. After fitting the cointegrating regression models, the residuals were tested for stationarity by means of ADF test. The results imply that there is an equilibrating mechanism that keeps the countries' GDP from drifting too far apart from each other. 


When two variables are cointegrated, there should be granger causality in at least one direction.The results of Toda-Yamamoto Granger causality test show strong evidence of causality running from India to Pakistan. But Pakistan's GDP does not granger-cause India's GDP. We also found that *China and India together granger-cause Pakistan's GDP. One possible reason for this could be the enormous volumes of exports from China and India to Pakistan. Exports from Pakistan to these countries are very small as compared to the imports from these countries.* Based on the results of the causality analysis, we can conclude that India and China affect Pakistan's economic growth more than Pakistan's economic growth affect those countries'.


In the end, an VECM (Vector Error Correction Model) was fitted. The fit looks good with a MAPE of 0.64 except that the model is slightly over-predicting. 


####GDP_DATA and gdp_analysis contains the data and code for analysis.
