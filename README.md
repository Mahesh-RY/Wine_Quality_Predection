Breast Cancer Prediction
📌 Overview

This project focuses on predicting breast cancer using machine learning techniques. The dataset is loaded from Scikit-learn’s breast cancer dataset, and various preprocessing and modeling steps are performed to classify whether a tumor is malignant or benign.

📂 Project Structure

Import Necessary Libraries – Libraries like NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn are used.

Dataset Loading – Breast cancer dataset from sklearn is used.

Data Preprocessing – Conversion to DataFrame, exploration, and standardization of features.

Exploratory Data Analysis (EDA) – Insights using descriptive statistics and visualization.

Model Training – Different machine learning models are applied, such as Logistic Regression, KNN, SVM, Decision Trees, and Random Forest.

Model Evaluation – Models are evaluated using accuracy score, confusion matrix, and classification report.

⚙️ Requirements

Make sure you have the following installed:

pip install numpy pandas matplotlib seaborn scikit-learn

🚀 Usage

Clone this repository or download the notebook.

Open the Jupyter Notebook:

jupyter notebook "Breast cancer prediction.ipynb"


Run the cells step by step to:

Load and preprocess the dataset

Train ML models

Evaluate their performance

📊 Results

The project compares different classification algorithms to find the most accurate model for breast cancer prediction. Standardization and proper evaluation ensure better reliability of the results.

📝 Notes

The dataset is directly available via sklearn.datasets.load_breast_cancer().

You can further tune hyperparameters for better accuracy.

Visualization helps in understanding feature distribution and class balance.