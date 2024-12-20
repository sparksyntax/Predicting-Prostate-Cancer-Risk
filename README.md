# Predicting-Prostate-Cancer-Risk
This repository focuses on predicting prostate cancer using machine learning. It includes data preprocessing, feature engineering, and models like Linear Regression, Random Forest, and a Neural Network with Attention. The models provide real-time predictions for diagnosis and risk assessment.


This repository contains a machine learning project focused on predicting prostate cancer using a dataset. The project explores various data processing and modeling techniques, including feature classification, correlation analysis, regression, classification, and neural network modeling.

Table of Contents
Overview
Dataset
Installation
Usage
Model Training & Evaluation
Visualization
Acknowledgements
Overview
This project aims to build predictive models for prostate cancer diagnosis using machine learning. The dataset includes various features such as age, weight, gland volume, and tumor characteristics. Different models are used to predict prostate-specific antigen (PSA) levels and classify prostate cancer risk.

Dataset
The dataset used in this project is prostrate_cancer_new.csv, which contains information about prostate cancer patients. It includes both categorical and numerical features.

Features:
age
lcavol (log cancer volume)
lweight (log prostate weight)
lbph (log benign prostatic hyperplasia)
lcp (log capsular penetration)
pgg45 (gleason score)
gleason (gleason score)
svi (seminal vesicle invasion)
lpsa (log prostate-specific antigen)

Installation
To run this project locally, follow these steps:

Clone the repository:

git clone https://github.com/yourusername/prostate-cancer-prediction.git
cd prostate-cancer-prediction

Create a virtual environment (optional):

python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

Install dependencies:

pip install -r requirements.txt

Usage
After installation, you can explore the notebook or script to understand the different steps involved in data preprocessing, model training, evaluation, and visualization.

Model Training & Evaluation: 
Linear Regression and Random Forest Classifier are used for regression and classification tasks.
A Neural Network with an Attention Layer is implemented to enhance prediction accuracy.
Visualization
The repository includes various visualizations such as:

Distribution plots for categorical and numerical features.
Correlation heatmaps for continuous variables.
Training and validation loss plots for neural networks.

Acknowledgements
Special thanks to the dataset contributors and machine learning libraries used in this project (e.g., pandas, numpy, scikit-learn, tensorflow, seaborn).
