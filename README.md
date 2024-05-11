# A.P. Moller Maersk Case Study 

## Dataset

The dataset consists of training and testing datasets stored in Excel files. It contains several features such as ProductType, Manufacturer, Area Code, Sourcing Channel, Product Size, Product Type, Month of Sourcing, and Sourcing Cost. We use this dataset to train and test our regression models.

## Files

- `Training Dataset.xlsx`: Excel file containing the training dataset.
- `Testing Dataset.xlsx`: Excel file containing the testing dataset.
- `A.P. Moller Maersk.ipynb`: Jupyter Notebook containing the code for data loading, preprocessing, model training, and evaluation.


### Performance Comparison of Models

In this project, we evaluated the performance of two regression models: Random Forest and Linear Regression. Below is a summary of the comparison based on key evaluation metrics:

#### Mean Absolute Error (MAE)

- **Random Forest**: Lower MAE (e.g., 20.34)
- **Linear Regression**: Higher MAE (e.g., 23.45)

A lower MAE indicates that the model's predictions are, on average, closer to the actual values. Therefore, the Random Forest model performed better in terms of absolute prediction accuracy.

#### Mean Squared Error (MSE)

- **Random Forest**: Lower MSE (e.g., 1215.38)
- **Linear Regression**: Higher MSE (e.g., 1402.01)

Similar to MAE, a lower MSE signifies better prediction accuracy. The Random Forest model had a lower MSE, indicating that it produced predictions closer to the actual values with less variance.

#### R-squared Score (R2 Score)

- **Random Forest**: Higher R-squared score (e.g., 0.552)
- **Linear Regression**: Lower R-squared score (e.g., 0.483)

The R-squared score measures the proportion of variance in the target variable explained by the model. A higher R2 score indicates a better fit to the data. Therefore, the Random Forest model provided a better fit to the data compared to the Linear Regression model.

### Conclusion

Based on the evaluation metrics, the Random Forest model outperformed the Linear Regression model in terms of prediction accuracy and model fit. However, it's important to consider other factors such as model interpretability and computational efficiency when choosing the appropriate model for a specific task.

