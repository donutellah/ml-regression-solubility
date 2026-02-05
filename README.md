# ML LogS Prediction

This project is my **first machine learning (ML) project** using Python.  
It focuses on predicting the **aqueous solubility (logS)** of molecules based on molecular descriptors.  

The workflow includes:  
1. **Data Loading** – Fetches the Delaney solubility dataset from a public CSV.  
2. **Data Preparation** – Splits the dataset into features (`MolLogP`, `MolWt`, `NumRotatableBonds`, `AromaticProportion`) and target (`logS`), and performs train-test splitting.  
3. **Model Building** – Implements and trains:
   - **Linear Regression**
   - **Random Forest Regression**
4. **Model Evaluation** – Calculates **MSE** and **R²** for both training and test datasets to compare model performance.  
5. **Data Visualization** – Plots predicted vs. experimental logS for model assessment.  

## Requirements
- Python 3.10+
- pandas, numpy, matplotlib, scikit-learn

## Usage
Run the notebook in **Google Colab** or **Jupyter**. The notebook automatically loads the dataset from a public URL.  

You can experiment with different regression models or hyperparameters to improve prediction accuracy.  

## Dataset
The Delaney solubility dataset contains **1,145 molecules** with features describing their molecular properties and experimental solubility values (`logS`).  

## Goal
The main goal of this project is to **practice ML workflow** including data preparation, model building, evaluation, and visualization, while gaining insights into molecular solubility prediction.

