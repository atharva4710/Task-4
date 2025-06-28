# Task-4
🧠 Task 4: Classification with Logistic Regression
✅ Objective
To build a binary classifier using Logistic Regression on a real-world dataset to predict whether a tumor is malignant (M) or benign (B).

🛠️ Tools & Libraries Used
Pandas: Data handling

Scikit-learn: Model training, scaling, evaluation

Matplotlib / Seaborn: Data visualization

Logistic Regression: For binary classification

📂 Dataset Used
Breast Cancer Wisconsin Diagnostic Dataset

Binary target: diagnosis

Malignant → 1

Benign → 0

🔍 Steps Performed
Import Dataset

Data Cleaning

Dropped irrelevant columns (id, Unnamed: 32)

Converted diagnosis to numeric values (0/1)

Train-Test Split (80%-20%)

Feature Scaling using StandardScaler

Model Training using LogisticRegression

Model Evaluation

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

ROC Curve and AUC

Threshold Tuning & Sigmoid Function

Visualized the sigmoid function used in logistic regression

📊 Output Highlights
ROC-AUC Score: Measures the classifier's ability to distinguish classes.

Confusion Matrix: Displays true vs predicted values.

Sigmoid Function Plot: Shows how raw outputs are converted to probabilities.

📁 Files Included
Logistic_Regression_Classification.ipynb: Complete notebook

data.csv: Breast cancer dataset (input file)
