# Father–Son Height Prediction using Linear Regression
This project builds a regression model to predict a son’s height based on his father’s height. The goal is to study the linear relationship between parent and child heights and show how simple/multiple linear regression can model this relationship.​

Project Overview
Objective: Predict son’s height from father’s height.​
Problem type: Supervised learning – Regression (continuous target: height).​
Approach: Simple Linear Regression (optionally extendable to multiple regression with mother’s height, gender, etc.).​

Dataset:
father_height: Height of the father (e.g., in cm or inches).
son_height: Height of the son (same unit as father).
Number of records: N rows of paired father–son heights.
If you used a known dataset (like Pearson’s father–son height data or Galton family data), briefly mention or link it.​

Tech Stack
Python
NumPy, Pandas
Matplotlib / Seaborn
scikit-learn

Methodology
Load and explore the data (shape, summary statistics, missing values).​
Visualize the relationship between father and son heights using a scatter plot.​
Split the data into training and test sets.​
Train a Linear Regression model (and optionally other regression models) to predict son_height from father_height.​
Evaluate the model using metrics such as R², Mean Squared Error (MSE), and Mean Absolute Error (MAE).​
Plot the regression line over the scatter plot to visualize the fit.​



Project Structure
data/father_son_height.csv – Dataset
height_prediction.py – Main training and evaluation script
notebooks/ – EDA and experiments
requirements.txt – Python dependencies
README.md – Project documentation



Project_web_server : https://ml-slr-height-prediction.onrender.com/predict
