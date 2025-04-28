# Social Network Ads Purchase Prediction - Model Comparison

## Short Description

This project predicts whether a user will purchase a product based on their age, estimated salary, and gender, using data from `Social_Network_Ads.csv`. It trains and compares the performance of several common classification algorithms: XGBoost, Decision Tree, Random Forest, and Logistic Regression.

## Project Overview

The notebook `day6/Social_Network_Ads.ipynb` performs the following:

1.  **Load Data:** Loads the social network ads dataset.
2.  **Feature Selection:** Selects 'Gender', 'Age', and 'EstimatedSalary' as features.
3.  **Preprocessing:** Applies Label Encoding to the 'Gender' column.
4.  **Train-Test Split:** Splits the data into training and testing sets.
5.  **Model Training & Evaluation:**
    *   Trains an **XGBoost** classifier and evaluates its accuracy and confusion matrix.
    *   Trains a **Decision Tree** classifier (with 'entropy' criterion) and evaluates its accuracy. Includes plotting the tree structure.
    *   Trains a **Random Forest** classifier and evaluates its accuracy.
    *   Trains a **Logistic Regression** classifier and evaluates its accuracy.

## Dataset

*   **Social_Network_Ads.csv:** Contains user ID, gender, age, estimated salary, and whether the user purchased the product (Purchased = 1).

## Models Compared

*   XGBoost (`XGBClassifier`)
*   Decision Tree (`DecisionTreeClassifier`)
*   Random Forest (`RandomForestClassifier`)
*   Logistic Regression (`LogisticRegression`)

## Requirements

*   Python 3
*   NumPy
*   Pandas
*   Scikit-learn
*   XGBoost
*   Matplotlib

## How to Run

1.  Ensure you have the required libraries installed (`pip install numpy pandas scikit-learn xgboost matplotlib`).
2.  Make sure the `Social_Network_Ads.csv` file is in the correct path relative to the notebook.
3.  Run the Jupyter Notebook `day6/Social_Network_Ads.ipynb`.
