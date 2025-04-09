# Principal-Component-Analysis-on-Raisins-Segregation-using-Machine-Learning
## Summary
This project aims to classify two types of raisins (Besni and Kecimen) using data science and machine learning techniques. The goal is to build a model that can accurately predict the raisin type based on physical measurements, by applying visualization, Principal Component Analysis (PCA) for dimensionality reduction, and various machine learning algorithms for classification. Additionally, model interpretability techniques like SHAP are used to understand the reasoning behind each prediction.
 
🧭 Project Steps: 

### 📌 Dataset Overview
The dataset contains various physical measurements of raisins (like length, width, eccentricity, etc.) and a label indicating the raisin type.

### 🔍 Data Cleaning & Visualization
Checked for duplicates and missing values.
Used box plots, pair plots, and correlation heatmaps to understand the distribution and relationships between features.

### 🧠 Principal Component Analysis (PCA)
PCA was applied to reduce the number of features while preserving the most important information.
Plotted the data in a new space (principal components) to see if raisins could be separated visually.
Scree plots showed how much data each principal component captures.

### 🤖 Machine Learning with PyCaret
Used the PyCaret library to automatically train and evaluate multiple classification models (e.g., Logistic Regression, Ridge, LDA).
Models were trained with the original features and PCA-reduced features (to test if dimensionality reduction improves performance)

### 🧠 Model Interpretation with SHAP
Used SHAP (SHapley Additive exPlanations) to understand why the model made certain predictions.
Helps identify which features are most important in deciding raisin type.



