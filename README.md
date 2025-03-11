# ML_INTERN
Overview

This repository contains a machine learning pipeline for analyzing hyperspectral data from corn samples. The goal is to predict DON concentration using spectral reflectance values. The project includes data preprocessing, dimensionality reduction, model training using XGBoost, and evaluation with regression metrics.

Installation

To run this project, ensure you have Python installed along with the required dependencies.

Install dependencies

pip install -r

Required Libraries

numpy

pandas

matplotlib

seaborn

scikit-learn

xgboost

Running the Code

Clone the repository:

Ensure all dependencies are installed.

Place your dataset file in the repository folder.

Run the Jupyter Notebook or execute the script:

python main.py

Repository Structure

├── ML Intern Aakarsh Dawar.ipynb/       # Jupyter Notebook Code
├── Short report/                        # Report about the code
├── README.md                            # Project documentation

Results

Data preprocessing includes missing value handling, normalization, and feature scaling.

PCA and t-SNE are used for dimensionality reduction and visualization.

XGBoost is trained with hyperparameter tuning via GridSearchCV.

Model evaluation includes MAE, RMSE, and R² Score.

Future Improvements

Experiment with deep learning models (CNNs, transformers) for better feature extraction.

Optimize feature selection techniques to retain relevant wavelengths.

Explore additional ensemble methods to refine predictions.
