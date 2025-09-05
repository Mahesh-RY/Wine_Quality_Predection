
🍷 Red Wine Quality Prediction
📌 Overview

This project predicts the quality of red wine based on physicochemical features. The dataset is sourced from the UCI Machine Learning Repository and is publicly available on Kaggle. Using machine learning models, the project classifies wine quality into different score levels to aid in quality assessment.

📂 Dataset

Source: Red Wine Quality Dataset – Kaggle

This dataset relates to red variants of the Portuguese Vinho Verde wine.

Input Variables (Physicochemical Tests):

Fixed acidity

Volatile acidity

Citric acid

Residual sugar

Chlorides

Free sulfur dioxide

Total sulfur dioxide

Density

pH

Sulphates

Alcohol

Output Variable (Sensory Data):

Quality (score between 0 and 10)

📊 Project Workflow

Import Necessary Libraries – NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn.

Data Import & Overview – Load dataset, inspect features, check for null values.

Exploratory Data Analysis (EDA) – Visualize distributions, correlations, and feature importance.

Data Preprocessing – Scaling, handling imbalanced classes.

Model Training – Machine learning models (Logistic Regression, Decision Tree, Random Forest, AdaBoost, etc.).

Model Evaluation – Accuracy, precision, recall, F1-score, confusion matrix.

⚙️ Requirements

Install the required dependencies:

pip install numpy pandas matplotlib seaborn scikit-learn

🚀 Usage

Clone this repository or download the notebook.

Open the notebook:

jupyter notebook "red wine quality prediction.ipynb"


Run the notebook step by step:

Load and preprocess dataset

Train ML models

Evaluate model performance

📈 Results

The project compares multiple ML algorithms for wine quality prediction.

Accuracy and evaluation metrics are used to identify the best-performing model.

Random Forest / AdaBoost typically achieve strong performance.

📝 Notes

The dataset contains only physicochemical and sensory data (no info on grape type, brand, or price).

Class imbalance (most wines have quality between 5–7) can affect accuracy.

Hyperparameter tuning can further improve performance.
