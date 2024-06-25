# California Housing Prediction

## Introduction

This project focuses on developing a machine learning model to predict housing prices accurately across different regions of California based on relevant features such as location, demographic characteristics, and the number of rooms. The model's performance will be assessed using Mean Absolute Error (MAE), with a target MAE of less than $50,000. The primary stakeholders for this project are real estate agents who require reliable price estimates for property transactions in California.

## Model Development

Housing data from various regions in California will be gathered and utilized to train the model. Features such as geographic location, number of bedrooms, number of bathrooms, and demographic characteristics like population size will be incorporated into the model to predict housing prices.

## Model Performance Evaluation

Once developed, the model's performance will be evaluated using the Mean Absolute Error (MAE) metric. MAE measures the average absolute difference between predicted values and actual values. By setting a target MAE of less than $50,000, the goal is to ensure the model provides accurate price estimates with an acceptable margin of error.

## Benefits

The main benefit of this model is to provide real estate agents with reliable price estimates for properties they list or consider purchasing. By doing so, the model aims to enhance efficiency in property transactions across California by offering price estimates with a high degree of confidence.

## Result

The prediction modeling results using the California housing dataset demonstrate strong performance of the selected XGBoost model. Among 11 models evaluated, the XGBoost model was chosen based on metrics such as R2, MAE, and RMSE. With hyperparameters tuned to colsample_bytree of 0.6, learning_rate of 0.1, max_depth of 7, n_estimators of 500, and subsample of 0.8, the model achieved notable accuracy in predicting housing prices.

On the test dataset, the model exhibited an R2 score of 0.847, indicating that approximately 84.68% of the variability in house prices can be explained by the independent variables (features) included in the model. This high R2 score underscores a strong relationship between predictors and housing prices, affirming the model’s robustness and reliability for price prediction tasks.

Furthermore, the model achieved a Mean Absolute Error (MAE) of 28,586, suggesting that, on average, predictions deviated by approximately $28,586 from actual house prices—a relatively low error rate considering the complexity and variability of housing prices in California. The Root Mean Squared Error (RMSE) of 43,163 indicates minimal dispersion around actual prices, further highlighting the model’s ability to provide accurate estimations.

The goal of achieving a deviation of $50,000 or less from actual house prices has been met, demonstrating the model's effectiveness in capturing and predicting price trends accurately. In conclusion, the XGBoost model demonstrates excellent performance in predicting housing prices in California, as evidenced by its high R2 score and low MAE and RMSE values. These findings underscore its practical utility in real estate valuation and decision-making processes.
