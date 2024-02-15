
# Breast Cancer Prediction with SVM

## Project Overview
This project aims to predict breast cancer using the Support Vector Machine (SVM) algorithm on the breast cancer dataset. It includes data loading, model preparation, k-fold cross-validation without hyperparameter tuning, hyperparameter tuning using GridSearchCV with StratifiedKFold, and evaluation on the test dataset.

## Project Explanation
The project involves using the Support Vector Machine (SVM) algorithm to predict breast cancer based on the Wisconsin Diagnostic Breast Cancer (WDBC) dataset. The process includes several steps:
1. **Data Loading and Model Preparation**: The breast cancer dataset is loaded, and the data is prepared for modeling.
2. **k-fold Cross-Validation**: The model's performance is estimated without hyperparameter tuning using k-fold cross-validation to ensure the model's effectiveness across different subsets of the data.
3. **Hyperparameter Tuning**: Using GridSearchCV with StratifiedKFold, the model's hyperparameters are fine-tuned to improve performance.
4. **Evaluation on Test Dataset**: The tuned model is then evaluated on a separate test dataset to gauge its predictive capability.

## Results
The project achieved the following results:
- Mean cross-validation score (before hyperparameter tuning): `0.8969`
- Best cross-validation score (after hyperparameter tuning): `0.9497`
- Final evaluation on the test dataset showed:
  - Accuracy: `0.9649`
  - Sensitivity: `0.9630`
  - Specificity: `0.9683`

These results indicate a high level of model performance in predicting breast cancer occurrences.

## Installation

To set up this project, you'll need Python and the following libraries:
- Pandas
- NumPy
- Scikit-learn

You can install the dependencies with:

```bash
pip install pandas numpy scikit-learn
```

## Usage

To use this project, follow these steps:
1. Load the breast cancer dataset.
2. Prepare the data and split it into training and test sets.
3. Perform k-fold cross-validation to estimate the model's performance.
4. Tune the hyperparameters using GridSearchCV with StratifiedKFold.
5. Evaluate the model on the test dataset.

Refer to the Jupyter notebooks for detailed code and explanations.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Citation
The dataset used in this project is cited as follows:

Wolberg, William, Mangasarian, Olvi, Street, Nick, and Street, W. (1995). Breast Cancer Wisconsin (Diagnostic). UCI Machine Learning Repository. https://doi.org/10.24432/C5DW2B.
