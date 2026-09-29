# Feature Selection and Model Benchmarking for Probability of Default Prediction

A machine learning project that predicts the probability of default (PD) for credit scoring. It studies how feature selection affects predictive performance and benchmarks multiple models against each other to identify the most reliable approach for assessing credit risk.

## Repository Contents

| File | Description |
|------|-------------|
| `Credit_Score.ipynb` | Notebook covering data preparation, feature selection, model training, and benchmarking |

## Objectives

- Identify the most informative features for predicting loan default
- Compare the performance of multiple classification models on the same data
- Measure how feature selection changes accuracy and model quality
- Support more transparent and efficient credit risk assessment

## Project Workflow

1. **Data preparation:** load the credit dataset, clean it, and handle missing values.
2. **Feature engineering:** encode categorical variables and scale numerical ones.
3. **Feature selection:** rank and select the features that contribute most to default prediction.
4. **Model training:** train several classification models on the full and reduced feature sets.
5. **Benchmarking:** compare models using standard classification metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
6. **Analysis:** interpret which features and models perform best.

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/TimBroAhm/Feature-Selection-Model-Benchmarking-Probability-of-Default-Prediction.git
cd Feature-Selection-Model-Benchmarking-Probability-of-Default-Prediction
```

2. Open `Credit_Score.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
3. Run the cells in order. The required libraries are imported at the top of the notebook.

## Tech Stack

Python · Pandas · NumPy · Scikit-learn · Matplotlib · Jupyter

## Future Work

- Add explainability with SHAP to show how each feature affects individual predictions
- Test gradient boosting models such as XGBoost and LightGBM
- Address class imbalance with resampling techniques
- Calibrate predicted probabilities for more reliable risk estimates

## Author

**Tim** ([@TimBroAhm](https://github.com/TimBroAhm))
