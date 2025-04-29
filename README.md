 Logistic Regression - Breast Cancer Detection

This project is part of my AI & ML Internship Task 4. The goal is to build a **binary classification model** using **logistic regression** to detect whether a tumor is **malignant** or **benign** using the Breast Cancer Wisconsin Dataset.


📁 Dataset

- **Name**: Breast Cancer Wisconsin (Diagnostic) Data Set  
- **Source**: [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)  
- **Target Column**: `diagnosis` (M = malignant, B = benign → encoded to 1 and 0)


✅ Task Objectives

- Preprocess and clean data
- Split dataset and standardize features
- Train a logistic regression model
- Evaluate performance using:
  - Confusion Matrix
  - Precision & Recall
  - ROC-AUC Score
  - ROC Curve Plot
- Tune threshold for decision-making
- Explain and visualize the sigmoid function


🧪 Model Results

| Metric              | Value     |
|---------------------|-----------|
| Accuracy            | 97%       |
| Precision           | 0.976     |
| Recall              | 0.953     |
| ROC-AUC Score       | 0.997     |
| Tuned Threshold     | 0.4       |
| New Precision/Recall| ~0.977    |


 📈 Sigmoid Function

The **sigmoid function** maps any real value to a range between 0 and 1:

\[
\sigma(z) = \frac{1}{1 + e^{-z}}
\]

It is used in logistic regression to produce probabilities for binary classification.


 🛠 Tools Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

 📂 How to Run

1. Clone the repository
2. Open `task4.ipynb` in Jupyter Notebook
3. Run all cells
4. Review output and plots


📎 Screenshots 
[image](https://github.com/user-attachments/assets/dfcac944-6cde-41d7-8524-8a5862aa38bb)
[image](https://github.com/user-attachments/assets/32772a9e-36f4-4bc6-aa66-5e2f5c671d09)

