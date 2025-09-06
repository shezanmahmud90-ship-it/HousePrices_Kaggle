# House Prices Prediction

Predict **house sale prices** using Python and machine learning.  
Includes data cleaning, feature engineering, regression models, ensemble techniques, and submission generation for Kaggle.

---

## What’s Included
- **Data Preprocessing:** handle missing values, encode categorical features, transform skewed features  
- **Models:** Linear Regression, Random Forest, XGBoost  
- **Ensemble Techniques:** simple averaging, weighted stacking, meta-model stacking  
- **Evaluation:** cross-validation RMSE, feature importance visualization  

---

## Results
- **Linear Regression RMSE:** ~0.176  
- **Random Forest RMSE:** ~0.144  
- **XGBoost RMSE:** ~0.126  
- **Weighted Stacking RMSE:** best performance on validation  

---

## Libraries Used
- **Python**, **Pandas**, **NumPy**  
- **Scikit-learn**  
- **XGBoost**, **LightGBM**  
- **Matplotlib**, **Seaborn**  
- **Joblib** (for saving/loading models)  

---

## Dataset
- [**House Prices: Advanced Regression Techniques**](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) from Kaggle  
  - `train.csv` and `test.csv` (not included due to size and licensing)  

---

## Notebook
- [house_prices_kaggle_full_workflow.ipynb](notebooks/house_prices_kaggle_full_workflow.ipynb)  

---

## Usage
1. Download the Kaggle dataset and place `train.csv` and `test.csv` locally.  
2. Open the notebook in **Google Colab** or **Jupyter**.  
3. Run cells step by step:  
   - load data → preprocess → train models → evaluate → generate submissions  

---

Created by **Shezan Mahmud**
