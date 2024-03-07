# Titanic Survival Prediction Competition

This repository contains code for participating in the Titanic Survival Prediction competition on Kaggle. The goal of this competition is to predict which passengers survived the Titanic shipwreck based on various features such as age, gender, ticket class, etc.

## Overview
- **`Titanic_Competition.ipynb`**: This Jupyter Notebook contains the code for data preprocessing, feature engineering, model training, and evaluation.
- **`titanic.csv`**: Submission file containing the predicted survival outcomes for the test dataset.

## Dataset
- The dataset used for this competition consists of two files:
  - **`train.csv`**: Contains training data with features and labels.
  - **`test.csv`**: Contains test data with features (without labels).

## Steps Applied
1. **Setup**: Ensured that the necessary libraries are installed, including `pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`, and `lightgbm`.
2. **Data Loading**: Loaded the training dataset (`train.csv`) using `pandas`.
3. **Data Preprocessing**: Performed data cleaning, handled missing values, and created new features such as family size, title, age category, etc.
4. **Exploratory Data Analysis (EDA)**: Analyzed the distribution of features, visualized relationships, and identified patterns in the data.
5. **Feature Engineering**: Extracted relevant features and transformed categorical variables using label encoding and one-hot encoding.
6. **Model Selection**: Chose appropriate machine learning models for classification, such as K-Nearest Neighbors (KNN) and Random Forest Classifier.
7. **Model Training**: Trained the selected models using the training dataset and evaluated their performance using cross-validation.
8. **Hyperparameter Tuning**: Optimized model hyperparameters using techniques like `GridSearchCV`.
9. **Model Evaluation**: Assessed model performance using evaluation metrics like accuracy, F1 score, and ROC AUC.
10. **Predictions**: Generated predictions for the test dataset using the trained models.
11. **Submission**: Prepared the submission file (`titanic.csv`) containing the passenger IDs and predicted survival outcomes.

## Dependencies
- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- lightgbm

## Results
- **Random Forest Classifier Model Accuracy**: 83.21%

## Author
- Eray Yuztyurk

## License
This project is licensed under the [MIT License](LICENSE).
