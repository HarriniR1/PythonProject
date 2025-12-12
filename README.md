# PythonProject
Data Analysis using python to determine factors most associated with stroke risk 
Stroke Risk Factors Analysis

Project Overview
This project investigates the research question:

Which factors are most strongly associated with stroke occurrence?

Using the publicly available "Healthcare Stroke Dataset," I performed data cleaning, exploratory data analysis (EDA), visualizations, and a machine-learning–based feature importance study. The goal is not to produce perfect scientific conclusions, but to demonstrate the use of Python for data analysis as required by the assignment.

All code was executed in a Jupyter Notebook and organized as a reproducible project.

Dataset
File: healthcare-dataset-stroke-data.csv Size: 5,110 records Target variable: stroke (0 = no stroke, 1 = stroke)

Key features examined:
Age
Hypertension
Heart disease
Average glucose level
BMI
Smoking status
Marital status
Residence type
Work type
Gender

Analysis Steps 
A. Data Cleaning
Filled missing BMI values with the median

Encoded categorical variables using LabelEncoder

Created glucose-level categories

Created age-group bins for visualization

B. Exploratory Visualizations
The following charts were generated:

Stroke Rate by Age Group (%)

Stroke Rate by Hypertension Status (%)

Stroke Rate by Heart Disease Status (%)

Stroke Rate by Glucose Level Group (%)

Random Forest Feature Importance (%)

C. Machine Learning Analysis
A Random Forest classifier was trained to identify which input features are most predictive of stroke.

Importance scores (%) were extracted and plotted to show the strongest contributing factors.

Key Findings (Summary)
Although this project focuses on Python usage rather than medical conclusions, the exploratory analysis suggests:

Age is a strong predictor of stroke.

Hypertension and heart disease significantly increase stroke rates.

Higher glucose levels show elevated stroke risk.

BMI and smoking status show moderate importance.

These align with typical clinical expectations and validate the dataset’s behavior.

File Structure 
Pythonfinalproject_harrini.ipynb # Main notebook 
figures # All generated visualizations 
processed_data.csv # Cleaned dataset used for modeling
healtthcare-dataset-stroke-data.csv # original dataset
README.md # Project documentation

How to Run the Notebook Requirements

Install the following Python packages:

pip install pandas numpy matplotlib scikit-learn

Steps

Open the notebook using Jupyter Lab/Notebook

Run all cells in order

Visualizations will automatically save to outputs/figures/

Research Question Restated
Which factors cause the highest stroke occurrence? This project answers the question using EDA and feature-importance modeling.

Notes for Submission
All output figures and processed data files are included in the outputs/figures

Notebook outputs are preserved
