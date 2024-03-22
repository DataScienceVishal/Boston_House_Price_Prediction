# Boston House Price Prediction using XGBoost Regressor

This project focuses on predicting house prices in Boston using the XGBoost regressor model. The dataset used for this project is obtained from the `sklearn.datasets` module, specifically the `load_boston` function.

## Problem Statement
The objective of this project is to predict house prices in Boston based on various features such as crime rate, average number of rooms per dwelling, accessibility to highways, etc. The aim is to develop a regression model that accurately predicts house prices, thereby assisting stakeholders in making informed decisions regarding real estate investments.

## Dataset Overview
- **Source**: The dataset is obtained from the `load_boston` function in the `sklearn.datasets` module.
- **Features**: The dataset comprises various features describing each house in Boston, such as crime rate, average number of rooms per dwelling, etc.
- **Target Variable**: The target variable is the median value of owner-occupied homes in $1000s.

## Libraries Used
- **NumPy**: For numerical computations.
- **Pandas**: For data manipulation and analysis.
- **XGBoost**: For implementing the XGBoost regressor model.
- **Sklearn**: For data preprocessing, model evaluation, and hyperparameter tuning.
- **Matplotlib and Seaborn**: For data visualization.

## Approach
1. **Data Loading**: Loading the Boston housing dataset using the `load_boston` function.
2. **Exploratory Data Analysis (EDA)**: Understanding the distribution of features, identifying correlations, and visualizing relationships between variables.
3. **Data Preprocessing**: Handling missing values, encoding categorical variables (if any), and scaling features if required.
4. **Model Building**: Implementing the XGBoost regressor model for house price prediction.
5. **Hyperparameter Tuning**: Fine-tuning model parameters using techniques like GridSearchCV to optimize model performance.
6. **Model Evaluation**: Assessing model performance using metrics such as R-squared score, mean squared error (MSE), and mean absolute error (MAE).

## Findings
After conducting EDA and hyperparameter tuning with GridSearchCV, the XGBoost regressor model achieved an R-squared score of 76% on the test data. This indicates that the model can explain 76% of the variance in house prices based on the selected features. Further analysis can be done to interpret feature importance and understand the factors influencing house prices in Boston.

## Conclusion
The XGBoost regressor model developed in this project demonstrates promising results in predicting house prices in Boston. Stakeholders in the real estate industry can leverage this model to estimate property values accurately, aiding in decision-making processes related to buying, selling, or investing in real estate properties.

For detailed implementation and code, refer to the Jupyter notebook provided in this repository.

Feel free to explore further and contribute to the enhancement of the project!
