# Breast Cancer Prediction using SVM Classifier

## Project Overview

This project is about making a computer program that can guess if breast cancer is the harmful kind (malignant) or the not-so-harmful kind (benign). We used a special method called Support Vector Machine (SVM) to do this. The information we used to help the computer learn comes from pictures of breast cells.

## Dataset

We got our data from a place called the UCI Machine Learning Repository. It's called the Breast Cancer Wisconsin (Diagnostic) dataset. It has info from 569 different cases, each with 30 details about the cells, and a note saying if the cancer is malignant or benign.

## How We Did It

Here's what we did step by step:

1. **Getting the Data Ready**: We made sure the data was clean and ready for the computer to learn from. This meant checking for any missing info and setting up the cancer labels as either 0 (benign) or 1 (malignant).
2. **Looking at the Data**: We first looked at the data to see what it's like and how the details of the cells might help us predict cancer.
3. **First Try with SVM**: We started with a basic version of SVM to see how well it could predict cancer without making any adjustments.
4. **Checking How Good It Is**: We checked how accurate our first try was in predicting cancer, looking at how often it was right, and how good it was at finding both benign and malignant cases.
5. **Making It Better**: We used something called GridSearchCV to adjust the SVM settings to make our predictions better.
6. **Final Check**: We checked our improved SVM on a separate set of data to see how much better it got.

## Results

We compared our first SVM try with the improved version and saw that the changes really helped. Our program got better at predicting cancer correctly.

## How to Use This

- You need to have Python and a tool called Jupyter Notebook on your computer.
- You'll also need a few extra tools you can add to Python, like pandas (for working with data) and sklearn (for machine learning).
- You can get everything set up by copying our project from GitHub, going to the project folder, and opening the `BreastCancer_Prediction_SVM.ipynb` file in Jupyter Notebook. Just run everything in there, and you'll see how it works.

## What You Need

- Python
- pandas (a Python tool)
- scikit-learn (another Python tool)
- Jupyter Notebook

## Thanks to

- Raja Muppidi
- Weihua Zhou

## Where the Data Came From
The data was first put together by people named Wolberg, Mangasarian, and Street in 1995. You can find it in the UCI Machine Learning Repository.
- Wolberg,William, Mangasarian,Olvi, Street,Nick, and Street,W.. (1995). Breast Cancer Wisconsin (Diagnostic). UCI Machine Learning Repository. https://doi.org/10.24432/C5DW2B.
