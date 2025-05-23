#  Bank Marketing Campaign — Decision Tree Classifier

##  Task 03 | SkillCraft Internship Project

Build a **Decision Tree Classifier** to predict whether a customer will subscribe to a term deposit based on their **demographic** and **behavioral** attributes using the **Bank Marketing Dataset** from the UCI Machine Learning Repository.

---

##  Objective

- Perform data cleaning and preprocessing.
- Explore the dataset and derive meaningful insights (EDA).
- Build and train a Decision Tree Classifier.
- Evaluate the model using relevant classification metrics.
- Interpret results to improve future marketing strategies.

---

##  Table of Contents

1. [Introduction](#-introduction)
2. [Dataset Overview](#-dataset-overview)
3. [Data Cleaning & Preprocessing](#-data-cleaning--preprocessing)
4. [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
5. [Model Building: Decision Tree](#-model-building-decision-tree)
6. [Model Evaluation](#-model-evaluation)
7. [Key Insights](#-key-insights)
8. [Conclusion](#-conclusion)

---

##  Introduction

This project leverages a real-world **marketing dataset** provided by a Portuguese banking institution. The goal is to **predict customer behavior**, specifically if they’ll subscribe to a **term deposit** based on features like age, job, marital status, contact type, and campaign interactions.

---

##  Dataset Overview

-  **Source**: UCI Machine Learning Repository
-  **Rows**: ~45,000
-  **Features**: 17 (independent) + 1 (target `y`)
-  **Target Variable**: `y` (Yes/No) - Whether the customer subscribed to a term deposit

---

##  Data Cleaning & Preprocessing

- Handled missing and unknown values.
- Converted categorical columns using Label Encoding or One-Hot Encoding.
- Checked for class imbalance and explored resampling options.
- Scaled/standardized numerical columns where needed.

---

##  Exploratory Data Analysis (EDA)

- Visualized distributions, class imbalances, and correlations.
- Explored relationships between features like age, education, previous outcomes, and call durations.
- Key patterns identified to inform feature importance and campaign strategies.

---

##  Model Building: Decision Tree

- Trained a **Decision Tree Classifier** using `sklearn`.
- Used train-test split for validation.
- Fine-tuned hyperparameters (criterion, depth, etc.)

---

##  Model Evaluation

- Evaluated using:
  - Accuracy
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-Score)
- Discussed model strengths & limitations.

---

##  Key Insights

- Clients with successful past campaign results are more likely to subscribe again.
- Contact method (cellular > telephone) impacts success rate.
- Duration of call strongly correlates with conversions.
- Demographics like age, job type, and marital status play key roles in decision-making.

---

##  Conclusion

The Decision Tree Classifier provides valuable insights for predicting customer behavior and tailoring marketing strategies. With further tuning and ensemble methods, the model’s performance can be significantly enhanced for real-world applications.

---

##  Tools & Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `sklearn` (DecisionTreeClassifier, metrics)
- Jupyter Notebook

---
