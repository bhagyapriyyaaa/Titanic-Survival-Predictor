# 🚢 Titanic Survival Predictor

This project predicts passenger survival on the Titanic using **machine learning models**. The main objective is to compare the performance of different classification algorithms and evaluate which one works best for this dataset.

---

## 📌 Project Overview
The Titanic dataset is a classic dataset for binary classification problems. It contains passenger information such as age, sex, class, and other features, with the target variable being **Survival** (0 = Did not survive, 1 = Survived).

In this project, I compared the following models:
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Random Forest Classifier**

---

## ⚙️ Workflow
1. **Data Preprocessing**
   - Filled missing values (Age, Embarked).
   - Encoded categorical variables (Sex, Embarked).
   - Normalized/Scaled numerical features where required.

2. **Exploratory Data Analysis (EDA)**
   - Analyzed feature distributions (Age, Fare, Pclass).
   - Checked correlations with survival.

3. **Model Training**
   - Split dataset into train and test sets.
   - Trained Logistic Regression, SVM, and Random Forest.

4. **Evaluation**
   - Compared models using Accuracy, Precision, Recall, and F1-score.
   - Plotted Confusion Matrices.

---

## 📊 Results
| Model                | Accuracy |
|----------------------|----------|
| Logistic Regression  | 79%      | 
| SVM                  | 75%      | 
| Random Forest        | 80%      |

> **Observation**: Random Forest usually achieves higher performance due to its ensemble learning approach, while Logistic Regression and SVM provide strong baseline models.

---

## 🛠️ Tech Stack
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/titanic-survival-predictor.git
   cd titanic-survival-predictor
