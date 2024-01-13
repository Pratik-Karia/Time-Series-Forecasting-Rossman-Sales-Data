# Time Series Forecasting Rossman Sales using Machine Learning

The research objective was to determine which models best fit the time series data, which would help organisations take measurable steps to improve their revenue and sales, not only provide financial assistance but also help businesses manage their inventory so they are never out of stock of any product, prevent overstocking, which would result in throwing away the products, incurring loss to the company, and reach their targeted sales to grow business.
As a part-time employee at one of the retail stores, I am aware of how various factors influence sales, thus for this study, I used the Rossmann store dataset, which takes into account all of the variables required to determine their impact on sales. 

### Objective 1: 
Is to investigate various effects such as whether or not a promotion is available in the store, whether or not there is a state or public holiday, whether or not there are any competitors stores nearby and, if so, how far are they from the Rossmann store and how long have they been open, what day of the week because sales are typically higher on Sundays, and which month of the year because December has the highest sales due to Christmas. 

### Objective 2: 
Is Implementing different machine learning models to forecast sales with higher accuracy.

### About the Rossman Store Dataset:
• The dataset was obtained from Kaggle.com. Link for the Kaggle Dataset https://www.kaggle.com/c/rossmann-store-sales.

• The dataset contains historical sales information for 1,115 Rossmann locations. It has three different datasets: training dataset, Store dataset and Test dataset.

• Training dataset: which contains information about whether that particular store was open or not, how much sales were made on that particular day of that particular month, and how many customers came to that particular store.

• Store dataset: which contains information about the type of store in a different location, what assortment is in that store, whether the promotion is applied in that store, and whether any competition exists.

• Test dataset: Test datasets contain the same variables as the training dataset but without the Sales variable, but they are used to validate our model's accuracy. 

• This dataset was part of a $35,000 Feature Prediction Competition on Kaggle.com.

### About the project:
My first purpose was to investigate and obtain a deeper grasp of the dataset. The dataset was then analysed by plotting several graphs and correlation plots, which enabled us in finding the parameters crucial for predicting Rossmann store sales and trends. After analysing the dataset and identifying its pattern, preprocessing was performed in preparation for machine learning. Using diverse machine learning models, the second objective was to forecast the sales variable. The first model employed was the Autoregressive integrated moving average (ARIMA), one of the most widely used linear models for time series forecasting over the past three decades. The second model employed was Facebook Prophet, an open-source algorithm developed by Facebook in 2017 for time series data that incorporates a few classic concepts with new twists. I utilised the Random Forest Regressor as my third model. It is an ensemble method that uses averaging to improve predicted accuracy and control overfitting by fitting a number of classifying decision trees to different subsamples of the dataset. The XGBoost regression model was the final one applied to our dataset. Extreme Gradient Boosting (XGBoost) is open-source software that efficiently and effectively implements the gradient boosting algorithm. In machine learning competitions, it is widely utilised to win with answers to a variety of issues. After generating predictions from each model, the models were evaluated using the Root Mean Squared Error (RMSE). RMSE is calculated by taking the square root of the mean of the squared differences between actual and projected outcomes.

### Conclusion: 
Our hypothesis of Facebook Prophet, a popular model for forecasting that takes seasonality and trends into account, was not successful in outperforming other models, and after evaluating the results, XGBoost performed better for our case study. The future scope of this project is to work on making Facebook Prophet a better model suitable for all type of time series data set, as it has proven to vary depending on the dataset, and in order to deploy Facebook Prophet, we need data to be specified in a specific format, which can be time-consuming.

