House Price Prediction using Linear Regression

1. Introduction
This project focuses on building a machine learning model to predict house prices using the California Housing dataset. The goal is to understand the complete ML workflow, including data preprocessing, model training, evaluation, and visualization.

2. Objective
The objective of this project is to:
Build a Linear Regression model
Predict house prices based on given features
Evaluate model performance using standard metrics

4. Dataset Description
The dataset used is the California Housing dataset from Scikit-learn.
Features include:

Median Income
House Age
Average Rooms
Average Bedrooms
Population
Average Occupancy
Latitude
Longitude
Target Variable:
Median House Value

4. Methodology
   
4.1 Data Loading & Exploration
Dataset loaded using Scikit-learn
Converted into a Pandas DataFrame
Checked structure and sample data

4.2 Data Preprocessing
No major missing values found
Features separated from target variable

4.3 Train-Test Split
Training data: 80%
Testing data: 20%

4.4 Model Training
Model used: Linear Regression
Trained using training dataset

6. Model Evaluation
The model was evaluated using:
MAE (Mean Absolute Error)
RMSE (Root Mean Squared Error)
R² Score (Coefficient of Determination)

MAE: 0.533;
RMSE: 0.746;
R² Score: 0.576;

6. Results & Visualization
A scatter plot of Actual vs Predicted values was created
The model shows a clear linear relationship
Some deviations are observed at higher price values
Overall, the model performs reasonably well

8. Conclusion
Linear Regression works as a good baseline model
The predictions follow the general trend of actual values
However, accuracy can be improved

10. Future Improvements
Apply Ridge and Lasso Regression
Use advanced models like Random Forest
Perform feature engineering
Normalize/standardize features

12. Tools & Technologies
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Jupyter Notebook
