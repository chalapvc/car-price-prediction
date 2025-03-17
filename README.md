# Car Price Prediction

This project is about predicting the prices of used cars using a dataset from Kaggle. It explores different machine learning techniques to understand what factors affect car prices. The goal is to build a model that helps used car dealerships set accurate prices for their inventory.

## Project Overview

This project aims to analyze a dataset of used cars and develop a machine learning model to predict their prices. It follows the CRISP-DM process, including data exploration, preparation, modeling, evaluation, and deployment.

## Dataset

This project utilizes a dataset of 426K used cars, featuring key attributes such as:
- Year of manufacture
- Manufacturer
- Model
- Condition
- Fuel type
- Odometer reading
- Transmission type
- Drive type
- Vehicle type
- Paint color
-  State and Region of sale.

## Files in the Repository

- `pricepredictor.ipynb`: The Jupyter Notebook containing the complete analysis, data preparation, modeling, and evaluation process.
- `vehicles.csv`: The dataset used for training and testing the machine learning models.

## Steps and Methodology

### 1. Data Understanding

- **Descriptive Statistics**: Calculated summary statistics for each numerical feature.
- **Distribution Analysis**: Visualized distributions of key variables using histograms and box plots.
- **Correlation Analysis**: Computed correlation coefficients and visualized them using heatmaps and pair plots.
- **Missing Values Analysis**: Identified and visualized patterns of missing data.

### 2. Data Preparation

- **Handling Missing Values**: Applied techniques like mean imputation and Iterative Imputer for missing data.
- **Encoding Categorical Variables**: Converted categorical variables to numerical using label encoding and one-hot encoding.
- **Feature Engineering**: Created new features and reduced cardinality for high-cardinality categorical variables.

### 3. Modeling

- **Model Selection**: Evaluated different models including Linear Regression, Decision Tree, and Random Forest.
- **Hyperparameter Tuning**: Used GridSearchCV for hyperparameter tuning of the Random Forest model.

### 4. Evaluation

- **Performance Metrics**: Evaluated models using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²).
- **Feature Importance**: Analyzed feature importances from the Random Forest model to understand the most influential features.

### 5. Deployment

- **Model Saving**: Saved the trained model using joblib for future use.
- **Results Interpretation**: Interpreted and visualized the model's predictions and feature importances.

## Results

- The Random Forest model with the best parameters achieved an MAE of approximately 8268, an MSE of approximately 186040113, and an R² of approximately 0.359.
- The most influential features in predicting car prices were odometer reading, year of manufacture, car condition, fuel type, vehicle type, and location of sale.

## Conclusion
This project offers a thorough analysis of the factors affecting used car prices and develops a predictive model to help dealerships price their inventory accurately. Insights from the feature importance analysis provide valuable guidance on what consumers prioritize when purchasing a used car.

## License
This project is licensed under the MIT License.

## Acknowledgements
The dataset used in this project is sourced from Kaggle.
