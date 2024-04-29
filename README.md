# item-level-sales-prediction


## Overview

This project aims to predict item-level sales data at different store locations using machine learning models. The dataset includes information such as date, store ID, item ID, and sales. The objective is to forecast sales for the next three months.

## Model Evaluation

Based on the Mean Absolute Error (MAE) values obtained:

- **Random Forest Model:** MAE = 7.553321
- **CatBoost Model:** MAE = 6.810928

We can conclude that the CatBoost model performed better in terms of MAE, as it achieved a lower MAE compared to the Random Forest model. A lower MAE indicates that the predictions made by the CatBoost model were, on average, closer to the actual sales values compared to the Random Forest model.

Additionally, by visualizing the predictions of both models over time, we can observe any discrepancies and trends. If the predictions closely follow the actual sales data with minimal deviations, it further reinforces the superiority of the CatBoost model.

## Conclusion

In summary, based on both the MAE values and visual inspection of predictions, we can conclude that the CatBoost model outperformed the Random Forest model in predicting item-level sales data for the given task and dataset.

