# Heart Disease Prediction Using Machine Learning Classification Models

## Problem Statement
Heart disease remains one of the leading causes of death worldwide. Early and accurate prediction can significantly improve patient outcomes and reduce mortality. This project explores multiple machine learning models to accurately classify whether a patient is likely to have heart disease based on medical parameters such as age, sex, chest pain type, cholesterol levels, etc.

## Objective
- Develop a supervised classification model to predict heart disease (target: 0 or 1).
- Compare the performance of:
    - Logistic Regression
    - Decision Tree
    - Random Forest
    - Neural Network (Simple Feedforward)
- Evaluate models using: Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

## ML Pipeline
1. **Data Cleaning**: Handle missing values and scale numeric features.
2. **EDA**: Visualize distributions and correlations.
3. **Model Building**: Train/test split and training of classification models.
4. **Model Evaluation**: Compare models using standard classification metrics.

## Dataset
The dataset used in this project is the UCI Heart Disease dataset (Cleveland database).

## How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Open `Heart_Disease_Prediction.ipynb` in Jupyter Notebook or VS Code.
3. Run all cells to see the analysis and results.
