# SWYNEX Task 3 - Modeling and Evaluation

## Project Overview
This project was completed as part of the SWYNEX Technologies internship, Task 3: Modeling and Evaluation.

The objective is to build and evaluate a baseline machine-learning model that predicts passenger survival using the Titanic dataset.

## Dataset
- Titanic Passenger Dataset
- File: `titanic_cleaned.csv`
- Target variable: `Survived`

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Methodology
1. Loaded the cleaned Titanic dataset.
2. Selected input features and the target variable.
3. Split the data into training and testing sets.
4. Applied preprocessing to missing values and categorical features.
5. Trained a Logistic Regression baseline classifier.
6. Evaluated the model on the test dataset.

## Evaluation Metrics
The notebook reports:
- Accuracy
- Precision
- Recall
- F1 score
- Classification report
- Confusion matrix

Refer to the notebook for the actual evaluation results.

## Model Limitations
- Logistic Regression may not capture complex nonlinear relationships.
- Performance depends on the selected features and dataset quality.
- Results may vary with different train-test splits.
- Further model comparisons and validation could improve the evaluation.

## Files Included
- `SWYNEX_Task3_Modeling_and_Evaluation.ipynb` — Model training and evaluation notebook.
- `titanic_cleaned.csv` — Prepared dataset.
- `SWYNEX_Task3_Screenshots.pdf` — Screenshots of the work, if uploaded.

## Conclusion
A baseline Logistic Regression model was developed to predict passenger survival. Its performance was assessed using classification metrics and a confusion matrix. The results provide a starting point for further model comparison and improvement.

## Author
Shaik Sadiq Vaheeb
