# Telecom-Churn-using-Keras-Neural-Network

Telecom service provider is experiencing customer churn in their wireless subscriber base and would like to seek insight into the reasons for this churn

Seek out data to determine reasons for customer churn Determine if customer churn can be predicted and determine the best level of prediction Neural Net
Continuous and categorical variables.

Performed: Verification that there is no missing data or outliers General mean and correlation analysis across all attributes Feature selection

Churn data is highly imbalanced churn ~500 vs no churn 2,700. It would make sense to rebalance the dataset.

Finding "Charge" and "Mins" attributes have linear correlation. Minutes , "Mins"" is considered redundant for each Type and can be removed.

Neural Net exhibited the very good predictive accuracy Using Keras framework model.add(Dense(20,input_dim=15,activation='relu’)) model.add(Dense(4,activation='relu’)) … model.add(Dense(2,kernel_initializer = 'uniform',activation='sigmoid’))
