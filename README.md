# 🚀 Intrusion Detection System Using Machine Learning  

## 📌 Project Overview  
This project implements an **Intrusion Detection System (IDS)** using **machine learning** to classify network traffic as benign or malicious. The system enhances cybersecurity by detecting evolving attack patterns, leveraging the **UNSW-NB15 dataset** and multiple ML models, with **Gradient Boosting achieving 98% accuracy**.  

## 🛠️ Technologies & Tools  
- **Programming Language:** Python  
- **Libraries:** Scikit-learn, XGBoost, Pandas, NumPy, Matplotlib, Seaborn  
- **Tools:** Jupyter Notebook, StandardScaler, One-Hot Encoding, Grid Search, Randomized Search  
- **Dataset:** UNSW-NB15 (Cybersecurity Intrusion Dataset)  

## 📊 Features & Methodology  
✔ **Data Preprocessing:**  
   - Handled missing values, feature scaling (StandardScaler), and one-hot encoding for categorical data.  
   - Feature selection based on correlation matrix and statistical analysis.  

✔ **Exploratory Data Analysis (EDA):**  
   - Visualized attack distributions using **histograms, count plots, and correlation heatmaps**.  
   - Identified feature importance for improved model performance.  

✔ **Machine Learning Models Implemented:**  
   - **Gradient Boosting Classifier (98% Accuracy) ✅**  
   - Random Forest Classifier  
   - Logistic Regression  
   - Decision Tree  
   - Gaussian Naïve Bayes  

✔ **Model Evaluation & Optimization:**  
   - **Cross-validation, confusion matrix, precision-recall metrics, and F1-score analysis**.  
   - **Hyperparameter tuning** (Grid Search & Randomized Search) to optimize accuracy.  

## 📂 Dataset Access  
The **UNSW-NB15 dataset** can be accessed online at the official UNSW research website:  

🔗 **[UNSW-NB15 Dataset Official Page](https://research.unsw.edu.au/projects/unsw-nb15-dataset)**  

Once on the page, follow these steps to find the dataset:  
1. Click on the **OneDrive link** provided.  
2. Navigate to:  Nour Moustafa > UNSW-NB15 dataset > CSV Files
3. Download the required CSV files for training and testing.  

Ensure you have the **correct file paths** in your code to load the dataset after downloading.  
