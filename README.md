House Price Prediction - 

This repository contains my solution to the **"House Prices: Advanced Regression Techniques"** . The goal is to predict the final prices of homes in Ames, Iowa based on a rich set of features.

##  Contents

- `HousePrediction.ipynb`: Jupyter notebook with preprocessing, model training, and predictions using XGBoost.
- `train.csv` / `test.csv`: Dataset used from the competition *(not included here — available on Kaggle)*.


##  Model Details

- **Algorithm**: XGBoost Regressor
- **Preprocessing**:
  - Imputation for missing values
  - Label encoding for categorical variables
  - Feature engineering (e.g., house age, total bathrooms)
- **Validation**:
  - Train/validation split
  - Evaluation metric: Mean Absolute Error (MAE)
- **Best Validation MAE**: **17,417.65**

##  Libraries Used

- Python 3
- Pandas
- NumPy
- scikit-learn
- XGBoost



##  How to Run

```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn
```

Run the notebook `HousePrediction.ipynb` in Jupyter or Google Colab.
