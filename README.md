# S&P 500 Stock Prediction

This data science project is aimed to predict the performance of the S&P 500 stock, utilizing data from Yahoo Finance from the earliest date possible i.e. <ins>December 29th, 1927 to January 16th, 2023</ins>. The project had three research questions: **what significant events have impacted the stock performance, whether we could successfully model the stock and predict short term, and whether we could predict future movements.**

To answer the first research question, we analyzed historical events that might have impacted the S&P 500 performance. We found that various global and domestic events, economic crises, and pandemics significantly affected stock performance.

To answer the second research question, we attempted to use an ARIMA model but found that it did not perform well due to a constant prediction value. We then attempted K-Nearest Neighbors, which improved after cross-validation but still was not strong. Finally, we utilized Lasso Regression, which successfully modeled the S&P 500 with a low Mean Squared Error (MSE) after creating an interaction model. This model successfully predicted up to two months of untrained data with high accuracy.

For the third research question, we attempted to utilize a Long-Short Term Memory network and Random Forest with Randomized Search Cross Validation to predict long-term performance. We got a considerably high level of accuracy with LSTM as compared to Random Forest, but it could be because of using large chunks of data set for training purpose and accounts for overfitting. Hence for professional usage a lot more modifications are required. 

In summary, this project successfully modeled the S&P 500 stock and predicted short-term stock performance with high accuracy using a Lasso Regression model with an interaction model. The project also identified various historical events that impacted the stock performance. While long-term stock prediction remained a challenge, this project demonstrated the potential of data science to provide valuable insights into the stock market. 

