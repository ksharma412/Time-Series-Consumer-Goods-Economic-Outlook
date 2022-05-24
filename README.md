# Time-Series-Consumer-Goods-Economic-Outlook

I have picked up consumer goods to form an economic outlook report 2022 as it forms a major portion of GDP of US. The project is divided into three parts- Durable goods, Non-durable goods, and Services. 3-5 time series were analyzed and forecasted in each sector

The project workflow is designed as below:
•	Packages: We installed the required packages
•	Data Preparation: We modified the data as per our needs
•	Durable Goods-Modelling: Here we analyzed the pattern in the series for durable goods of Real personal consumption expenditure, industrial production, producer price index (final demand), consumer price index, and real personal disposable income. Two competitive models were built-Arima and ETS, and the one performing the best on test data set was chosen. This tab consists of all the analysis related to residuals, ACF, PACF, modelling, etc. 
•	Non-Durable Goods-Modelling: Here exact similar to above, we implemented the modelling for non-durables and analyzed the pattern in the series for non-durable goods of Real personal consumption expenditure, industrial production, producer price index (final demand), and consumer price index. Two competitive models were built on training data-Arima and ETS, and the one performing the best on test data set was chosen. This tab consists of all the analysis related to residuals, ACF, PACF, modelling, etc. 
•	Services-Modelling: Here we analyzed series of real personal consumption expenditure in services, net exports, and All employee-service providing. We constructed Arima models and selected one with lowest AICc and did residual analysis
•	Economic Outlook Report: The above chosen models in each series in each category was used on entire series to predict future values and is linked with detailed economic significance and policies.
