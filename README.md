# titanic-logistic-regression
"Logistic Regression for Survival Prediction"

This project implements and evaluates a **Logistic Regression model** for predicting passenger survival on the **Titanic dataset**.  
It was developed as part of my **Machine Learning internship** to gain hands-on experience in binary classification, performance evaluation, and model interpretation through visualizations.

# Project Goal

To train and evaluate a **Logistic Regression model** that predicts whether a passenger survived (1) or not (0), using a preprocessed and feature-engineered version of the Titanic dataset.

# Project Workflow

### 1. Dataset Utilization
- Used the **preprocessed Titanic dataset** (from **titanic-data-preprocessing** project ).  
- Ensured the target variable `Survived` is properly formatted as a binary label.

### 2. Model Implementation
- Trained a **Logistic Regression** model using Scikit-learn’s `LogisticRegression()` function.  
- Prepared the features (X) and target variable (y) for model training and testing.

### 3. Model Evaluation
Calculated and reported the following metrics on the test set:
- **Accuracy:** Overall correctness of predictions  
- **Precision:** True positives among predicted positives  
- **Recall:** True positives among actual positives  
- **F1-score:** Harmonic mean of precision and recall  

### 4. Model Diagnostics and Visualization
Generated the following plots to interpret model performance:
- **Confusion Matrix:** Visualizes TP, TN, FP, and FN counts  
- **ROC Curve:** Plots True Positive Rate vs False Positive Rate  
- **AUC (Area Under the Curve):** Quantifies model discrimination ability

# Tools and Libraries

- **Python 3.x**
- **NumPy** – numerical computations  
- **Pandas** – data handling and manipulation  
- **Scikit-learn** – model training, metrics, and visualization  
- **Matplotlib / Seaborn** – for enhanced data visualization

# Dataset Information

- Source: [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)  
- The dataset is **not uploaded** due to size constraints.  
- You can download it directly from Kaggle and place it in your working directory. 

# How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/titanic-logistic-regression.git
