# Breast Cancer Prediction using SVM

## Project Overview

This project aims to develop a machine learning model to predict breast cancer based on features derived from digitized images of a fine needle aspirate (FNA) of a breast mass. I have used the Breast Cancer Wisconsin (Diagnostic) dataset, which contains characteristics of the cell nuclei present in the images. In this project i have used the Support Vector Machine (SVM), classifier , to distinguish between malignant and benign tumors.

## Dataset

The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) dataset, available in the UCI Machine Learning Repository. It consists of 569 instances, each with 30 numeric, predictive attributes, and a binary target variable indicating the diagnosis (M = malignant, B = benign).

## Methodology

The project follows these steps:

1. **Data Preprocessing**: The dataset is loaded, cleaned, and prepared for modeling. This includes handling missing values (if any) and mapping the diagnosis column to binary values.
2. **Exploratory Data Analysis (EDA)**: Conducted an initial analysis to understand the data's characteristics and distribution.
3. **Model Training with Default SVM**: A Support Vector Machine (SVM) classifier is initially trained with default parameters to establish a baseline performance.
4. **Model Evaluation**: The default SVM model's performance is evaluated using metrics such as accuracy, sensitivity (recall), and specificity.
5. **Hyperparameter Tuning**: GridSearchCV is employed to fine-tune the SVM hyperparameters (C, gamma, and kernel) to improve the model's performance.
6. **Final Model Evaluation**: The tuned SVM model is evaluated on the test set, and its performance is compared to the baseline model.

## Results

The project includes a detailed comparison of the default SVM model and the tuned SVM model, highlighting the improvement in prediction accuracy, sensitivity, and specificity achieved through hyperparameter tuning.

## How to Run

- Ensure Python 3.x is installed along with Jupyter Notebook.
- Install necessary libraries: pandas, sklearn, matplotlib, seaborn (optional for EDA).
- Clone the repository and navigate to the project directory.
- Open the Jupyter Notebook (`BreastCancer_Prediction_SVM.ipynb`) and run all cells.

## Dependencies

- Python 3.x
- pandas
- scikit-learn
- Jupyter Notebook

## Contributors

- Raja Muppidi
- Weihua Zhou

## Dataset Source
- Wolberg,William, Mangasarian,Olvi, Street,Nick, and Street,W.. (1995). Breast Cancer Wisconsin (Diagnostic). UCI Machine Learning Repository. https://doi.org/10.24432/C5DW2B.
