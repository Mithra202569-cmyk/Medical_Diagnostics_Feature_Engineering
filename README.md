# 🏥 Medical Diagnostics – Feature Engineering & Machine Learning Classification

## 📌 Project Overview

This project focuses on medical diagnostics using the **UCI Mammographic Mass Dataset**. It involves data preprocessing, feature engineering, supervised machine learning, hyperparameter tuning, and model evaluation to predict the severity of mammographic masses.

The project is completed as part of the Rabtech Academy Internship.

## 🎯 Project Objectives

- Clean and preprocess the dataset.
- Handle missing values.
- Perform feature encoding and scaling.
- Identify important features.
- Train multiple supervised classification models.
- Perform hyperparameter tuning and cross-validation.
- Evaluate and compare model performance.
- Select and save the best-performing model.

## 📂 Dataset

**Dataset:** UCI Mammographic Mass Dataset

**Target Variable:** Severity

**Features used:**
- Age
- Shape
- Margin
- Density

The target variable represents the severity classification.

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- LightGBM
- Joblib

## 📊 Task 3 – Data Preprocessing & Feature Engineering

The following preprocessing and feature engineering techniques were performed:

1. Dataset loading and exploration.
2. Missing value handling.
3. Numerical feature scaling.
4. Categorical feature encoding.
5. Train-test splitting.
6. Mutual Information feature selection.
7. Correlation heatmap visualization.
8. Feature importance analysis.

## 🤖 Task 4 – Supervised Classification Modeling & Hyperparameter Tuning

Four supervised classification algorithms were implemented:

1. Logistic Regression
2. Random Forest Classifier
3. XGBoost Classifier
4. LightGBM Classifier

### Hyperparameter Tuning

GridSearchCV was used to identify suitable hyperparameters for each classification model.

### Cross-Validation

Stratified 5-Fold Cross-Validation was used to evaluate model performance while maintaining class distribution across folds.

### Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

Additional visualizations:
- Confusion Matrix
- ROC Curve

## 🏆 Champion Model

**Selected Model:** Logistic Regression

**Cross-Validation ROC-AUC:** 0.8622

Logistic Regression achieved the highest cross-validation ROC-AUC among the four evaluated models and was selected as the champion model.

## 💾 Model Serialization

The selected champion model was saved using Joblib.

**Saved file:** `champion_model.joblib`

The model comparison report was exported as:

`model_comparison.csv`

## 📁 Project Structure

```text
Medical_Diagnostics_Feature_Engineering/
│
├── Medical_Diagnostics_Task3_Task4.ipynb
├── champion_model.joblib
├── model_comparison.csv
├── README.md
```

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Open the Jupyter Notebook.
3. Install the required Python libraries.
4. Run the notebook cells sequentially.
5. View the model evaluation results and comparison report.

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost lightgbm joblib
```

## 📌 Conclusion

This project demonstrates the application of data preprocessing, feature engineering, and supervised machine learning techniques in medical diagnostics.

Four classification models were trained and evaluated. Logistic Regression achieved the highest cross-validation ROC-AUC score of 0.8622 and was selected as the champion model.

## 👩‍💻 Internship

**Organization:** Rabtech Academy

**Project Domain:** Machine Learning / Data Science

**Tasks Completed:** Task 3 – Feature Engineering; Task 4 – Supervised Classification Modeling & Tuning

---

*This project is developed for educational and internship purposes. Model predictions are not intended to replace professional medical diagnosis.*
