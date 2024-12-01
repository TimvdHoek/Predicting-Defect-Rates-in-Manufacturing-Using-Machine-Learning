# Predicting-Defect-Rates-in-Manufacturing-Using-Machine-Learning

## Overview
This repository contains Jupyter notebooks used in the thesis project for predicting defect rates in synthetic manufacturing data. The main goal of the thesis is to explore how feature engineering, feature selection, and model tuning impact the predictive performance of regression models for defect rates. The repository also includes the original dataset used in the analysis.

## Repository Structure

manufacturing_defect_dataset.csv: The original dataset sourced from Kaggle, created by Mr. Rabie El Kharoua.

notebooks/: Contains Jupyter notebooks documenting various stages of the analysis process:

01_eda.ipynb: Exploratory Data Analysis (EDA) to understand the dataset and initial insights.

02_feature_engineering.ipynb: Feature engineering to create additional features for improving model performance.

03_splitting_data.ipynb: Splitting data into training and testing datasets.

04_rq2_feature_engineering_impact.ipynb: Analysis to address Research Question 2 about how the inclusion of additional engineered features affects predictive performance.

05_modeling_pipeline.ipynb: Feature selection, model training, hyperparameter tuning, feature importance analysis, evaluation, and error analysis.

## Data Source
The dataset (manufacturing_defect_dataset.csv) used in this repository is sourced from Kaggle and was created by Mr. Rabie El Kharoua. Please visit the Kaggle dataset page for more information (https://www.kaggle.com/datasets/rabieelkharoua/predicting-manufacturing-defects-dataset/data). 

## Dependencies
To run the Jupyter notebooks, the following Python packages are required:

pandas

numpy

scikit-learn

matplotlib

seaborn

lightgbm

## Acknowledgments

Dataset created by Mr. Rabie El Kharoua, hosted on Kaggle.

Parts of the code were generated with the assistance of OpenAI's ChatGPT.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

