# LinearRegression

In this project, I analyze finance data comprising 23 different variables related to investors' characteristics. I initially processed the data by encoding certain features to make them compatible with Linear Regression analysis. Next, I generated a correlation matrix and visualized it using a heatmap to identify features most strongly correlated with 'Fixed Deposits'. It became evident that 'Government Bonds' and 'Debentures' exhibited the highest correlation.

Following this, I segregated my dataset into X (all data excluding 'Fixed Deposits') and Y ('Fixed Deposits'). To enhance accuracy, I standardized the values using StandardScaler. Then, I partitioned the data and executed Linear Regression. Subsequently, I assessed the model's performance using metrics such as mean_squared_error and r2_score.

Additionally, I explored the implementation of SGDRegressor, utilizing gradient descent in the Regression model. Again, I evaluated this model using mean_squared_error and r2_score to compare its performance against Linear Regression. Surprisingly, I observed that the Linear Regression model outperformed the SGDRegressor model.

This outcome highlighted that SGDRegressor might not consistently achieve optimal performance. Consequently, I concluded that, in this context, Linear Regression exhibited superior performance over SGDRegressor.
