# CIBIL Score Prediction

## Overview
This project explores multiple regression models to predict a person's CIBIL score based on various financial and personal factors. The objective is to determine which regression model provides the best results for accurate CIBIL score prediction.

## Dataset
The dataset used contains multiple features that influence an individual's CIBIL score. These features may include income, credit history, loan details, and other financial indicators.

## Models Implemented
The following regression models were trained and evaluated:
- **Linear Regression**
- **Decision Tree Regression**
- **Random Forest Regression**
- **Support Vector Regression (SVR)**
- **K-Nearest Neighbors (KNN) Regression**
- **Gradient Boosting Regression**
- **XG BOOST**
- **ADA BOOST**
- **CAT BOOST**
- **BROWN BOOST**
- **LIGHTGBM BOOST**
  
## Performance Evaluation
Each model was evaluated using:
- **Mean Squared Error (MSE)**
- **R-squared Score (R²)**
- **Mean Absolute Error (MAE)**

The model with the lowest error and highest R² score is considered the best for predicting CIBIL scores.

## Results
- The performance of each model is compared, and the best-performing model is identified as **Gradient Boosting** based on the evaluation metrics.

## Usage
To run the notebook:
1. Install the required dependencies:
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn
   ```
2. Open `CIBIL_pred.ipynb` in Jupyter Notebook or Google Colab.
3. Run all the cells to train models and evaluate their performance.

## Conclusion
This project provides insights into different regression models for CIBIL score prediction and helps determine the most suitable model for the task.



