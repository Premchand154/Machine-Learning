# Titanic Survival Prediction

## Project Overview
This project focuses on analyzing the Titanic dataset and building machine learning models
to predict passenger survival based on demographic and travel-related features.

## Objectives
- Perform Exploratory Data Analysis (EDA)
- Preprocess data (missing values, encoding, scaling)
- Train multiple classification models
- Compare model performance using evaluation metrics

## Models Used
- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

## How to Run
1. Clone the repository
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ````

2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook

   ```bash
   jupyter notebook notebooks/Project_1_Titanic_EDA.ipynb
   ```

## Results Summary

Logistic Regression achieved the best performance with ~85% accuracy,
outperforming Random Forest and XGBoost on this dataset.

## Future Improvements

* Hyperparameter tuning with cross-validation
* Feature engineering
* Threshold optimization
* Handling class imbalance more effectively

## requirements.txt (IMPORTANT)

Create a `requirements.txt` file:

```txt
numpy
pandas
matplotlib
seaborn
scikit-learn
xgboost
jupyter
````


## .gitignore

```txt
__pycache__/
.ipynb_checkpoints/
.env
data/raw/*.csv
```

## How to Push Everything to GitHub

From your project folder:

```bash
git init
git add .
git commit -m "Initial commit: Titanic ML project"
git branch -M main
git remote add origin https://github.com/your-username/your-repo-name.git
git push -u origin main
```




