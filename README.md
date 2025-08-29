# Titanic Predictor 🚢

A machine learning project that predicts passenger survival on the Titanic dataset.

## Features
- Data preprocessing (handling missing values, feature engineering)
- Models: Logistic Regression, Decision Tree, Random Forest, XGBoost
- Hyperparameter tuning with GridSearchCV
- Visualizations (matplotlib)
- Confusion matrix evaluation

## Project Structure
- `notebooks/Titanic.ipynb` → Main notebook
- `data/` → Training & test CSVs (from Kaggle Titanic dataset)
- `requirements.txt` → Dependencies

## How to Run
1. Clone this repo
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3.  Open the notebook:
    ```bash
    jupyter notebook notebooks/Titanic.ipynb
    ```

## Results

* Achieved ~80% accuracy with Logistic Regression
* Tree-based models (Random Forest, XGBoost) achieve up to ~83%
* Feature engineering improves performance (FamilySize, Cabin info, etc.)

---