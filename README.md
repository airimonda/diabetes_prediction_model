# Diabetes Risk Prediction

Classic ML classifier predicting diabetes risk from clinical data, with statistical testing to justify feature choices before modeling.

## Data

[100,000 Diabetes Clinical Dataset](https://www.kaggle.com/datasets) (Kaggle) — clinical and demographic features, binary diabetes outcome.

## Approach

- Statistical testing (Shapiro-Wilk, Mann-Whitney U, chi-squared) to check feature-target relationships before feature selection.
- Preprocessing: label encoding for categoricals, standard scaling for numeric features.
- Models compared: Logistic Regression, Decision Tree, Random Forest.
- Evaluation: accuracy and classification report (precision/recall/F1) per class.

## Files

- `diabetes_risk_prediction.ipynb` — full pipeline: EDA, statistical tests, preprocessing, model training, evaluation.

## Run

Open in Jupyter or Google Colab. Requires `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `scikit-learn`.
