# Intruder Detection through Webpage Session Tracking

## Overview
This notebook implements a baseline model for detecting intruders by analyzing user webpage session sequences. Using session data, it builds a Logistic Regression classifier to predict whether a session belongs to the user Alice or another user. The notebook includes exploratory data analysis (EDA), data preprocessing, feature engineering, and model evaluation using the ROC AUC metric.

## Features
- Exploratory Data Analysis of user sessions and website visits
- Data preprocessing including handling missing values and type conversions
- Feature engineering with timestamp and session duration metrics
- Logistic Regression classification model training and evaluation
- Use of sparse matrices for efficient data manipulation

## Tech Stack
- Python
- Jupyter Notebook / Google Colab
- Libraries: numpy, pandas, seaborn, matplotlib, scipy, scikit-learn

## How to Use
1. Clone or download the repository.
2. Open the notebook in Jupyter Notebook or Google Colab.
3. Follow cells sequentially: mount Google Drive, unzip and load data, perform analysis.
4. Run all cells to reproduce the analysis and model training.
5. Modify code or add features to improve model performance.

## Status
This notebook is organized and cleaned for presentation on GitHub, ready for further development or sharing.