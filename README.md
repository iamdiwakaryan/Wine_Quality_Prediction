# Wine_Quality_Prediction

This project aims to predict the quality of wine using machine learning techniques, specifically Support Vector Regression (SVR) and Random Forest Regression. The dataset used for this project contains various physicochemical properties of wines, such as acidity, sugar content, and alcohol content.

**Data Preprocessing**

Data Loading: The dataset is loaded into a suitable format (e.g., Pandas DataFrame).
Data Cleaning: Any missing values or inconsistencies in the data are handled appropriately.
Outlier Detection and Removal: **Z-score normalization** is employed to identify and remove outliers from the dataset.
Feature Scaling: Features are scaled to a common range to improve model performance.

**Model Development**

Model Selection: Two regression models are implemented:
**Support Vector Regression (SVR)**: A powerful machine learning algorithm that uses kernel functions to map data to a higher-dimensional space, enabling nonlinear relationships to be captured.
**Random Forest Regression:** An ensemble learning method that combines multiple decision trees to make predictions.
Model Training: Both models are trained on the preprocessed dataset.
Hyperparameter Tuning: Optimal hyperparameters for each model are determined using techniques like grid search or randomized search.
Cross-Validation: K-fold cross-validation is employed to assess the model's performance on different subsets of the data.
Model Evaluation

**Performance Metrics**: The following metrics are used to evaluate the models:

Mean Absolute Error (MAE): Measures the average magnitude of errors.
Mean Absolute Scaled Error (MASE): Compares the model's forecast accuracy to a naive forecast.
Model Comparison: The performance of the two models is compared to identify the best-performing one
