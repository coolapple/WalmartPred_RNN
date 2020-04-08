# WalmartPred_RNN
Walmart Sales Projection using Recurrent Neural Network and time series


We are predicting the Walmart sales for different departments of 45 Walmart stores by applying recurrent neural network. 
With 3 years of data samples, we applied recurrent neural network (RNN) with LSTM to include history looking back to improve prediction power. We also include macro-economic factors, store and weather factors into our neural network. 
Overall, we found that RNN with LSTM layers achieved the accuracy of 98% and mean absolute error of around 2K. We also use ARIMA model to do time series analysis of weekly sales data.  

Steps for the RNN implementation:
1.	Show data cleaning and preparation steps: build train data and test data for RNN LSTM inputs. 
2.	Perform EDA on the given dataset and list out findings  
3.	Predict the sales projection with multivariate recurrent neural network algorithms - Use R square and MAE as metrics and provide best possible accuracy. (98% accuracy and MAE of 2K-2.5K on both test and train dataset)
 

Time series modeling:
1.	Integrated data from multiple AWS SQL tables. 
2.	Amputated missing values using 0 for mark down1-5 and mean values for CPI and unemployment. 
3.	Reengineering new holiday variable for pre-thanksgivings and pre-Christmas due to sale spikes. 
4.	Rolling mean and variance of store sales stabilize after removing pre-Thanksgiving and pre-Christmas.
5.	Decompose data into trend, seasonality and residuals. 
6.	Log transformation of weekly sales data and test stationary
7.	Start to apply ARIMA model to total weekly sales. 

 

