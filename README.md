# California Housing Price Prediction 🏠

This project aims to predict median house prices in California districts using various Machine Learning regression techniques. The model is trained on geographical, demographic, and economic features.

## 📋 Project Overview
The project follows a standard Data Science pipeline:
- **Data Exploration (EDA):** Visualizing distributions, correlations, and geographical data.
- **Preprocessing:** Handling missing values, feature scaling, and encoding categorical variables.
- **Model Training:** Implementing multiple regression algorithms.
- **Evaluation:** Comparing models using RMSE and R2 Score metrics.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** - `Pandas` & `NumPy` (Data Manipulation)
  - `Matplotlib` & `Seaborn` (Data Visualization)
  - `Scikit-Learn` (Machine Learning Models & Evaluation)

## 📊 Dataset Features
The dataset includes several features for California housing districts:
- **Location:** Longitude and Latitude.
- **Housing Info:** Total rooms, total bedrooms, and median house age.
- **Demographics:** Population and households.
- **Economic Info:** Median income.
- **Target Variable:** Median house value.

## 🚀 Models & Performance
Based on the experiments in the notebook, here are the results:

1. **Linear Regression (LR):**
   - **RMSE:** 66,813.34
   - **R2 Score:** 0.663

2. **Random Forest Regressor:**
   - **RMSE:** 48,225.60
   - **Result:** This model performed significantly better, capturing non-linear relationships in the data more effectively.

## 📂 Project Structure
- `housing.ipynb`: The main Jupyter Notebook containing all calculations and models.
- `datasets/housing.csv`: The raw dataset used for training.

