# 🎓 Student Performance Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict a student's final academic performance (**G3**) using various demographic, academic, family, and lifestyle-related factors. Multiple machine learning regression algorithms are trained and evaluated to identify the best-performing model.

---

# 🎯 Problem Statement

Educational institutions often need to identify students who are at risk of poor academic performance before final examinations. Predicting student performance using machine learning can help educators provide early intervention and personalized support.

---

# 🎯 Objectives

* Understand the dataset and perform exploratory data analysis (EDA).
* Identify factors affecting student performance.
* Preprocess and prepare the data for machine learning.
* Train multiple regression models.
* Compare model performance using evaluation metrics.
* Select the best-performing model.
* Save the trained model for future predictions.

---

# 📊 Dataset Information

* **Dataset Name:** Student Performance Dataset
* **Number of Records:** 395
* **Number of Features:** 33
* **Target Variable:** G3 (Final Grade)

---

# 📖 Data Dictionary

| Feature    | Description                       | Type        |
| ---------- | --------------------------------- | ----------- |
| school     | Student's school                  | Categorical |
| sex        | Student's gender                  | Categorical |
| age        | Student's age                     | Numerical   |
| address    | Urban or Rural address            | Categorical |
| famsize    | Family size                       | Categorical |
| Pstatus    | Parent's cohabitation status      | Categorical |
| Medu       | Mother's education level          | Numerical   |
| Fedu       | Father's education level          | Numerical   |
| Mjob       | Mother's occupation               | Categorical |
| Fjob       | Father's occupation               | Categorical |
| reason     | Reason for choosing the school    | Categorical |
| guardian   | Student's guardian                | Categorical |
| traveltime | Travel time to school             | Numerical   |
| studytime  | Weekly study time                 | Numerical   |
| failures   | Number of previous failures       | Numerical   |
| schoolsup  | Extra educational support         | Categorical |
| famsup     | Family educational support        | Categorical |
| paid       | Extra paid classes                | Categorical |
| activities | Extracurricular activities        | Categorical |
| nursery    | Attended nursery school           | Categorical |
| higher     | Wants higher education            | Categorical |
| internet   | Internet access at home           | Categorical |
| romantic   | Romantic relationship             | Categorical |
| famrel     | Family relationship quality       | Numerical   |
| freetime   | Free time after school            | Numerical   |
| goout      | Going out with friends            | Numerical   |
| Dalc       | Workday alcohol consumption       | Numerical   |
| Walc       | Weekend alcohol consumption       | Numerical   |
| health     | Health status                     | Numerical   |
| absences   | Number of absences                | Numerical   |
| G1         | First period grade                | Numerical   |
| G2         | Second period grade               | Numerical   |
| G3         | **Final Grade (Target Variable)** | Numerical   |

---

# 📁 Project Structure

```text
student-performance-prediction/

├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_preprocessing.ipynb
│   ├── 04_model_training.ipynb
│   └── 05_model_evaluation.ipynb
│
├── src/
├── models/
├── images/
├── reports/
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* Git & GitHub

---

# 🔄 Project Workflow

```text
Problem Understanding
        ↓
Data Understanding
        ↓
Exploratory Data Analysis (EDA)
        ↓
Data Preprocessing
        ↓
Feature Engineering
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Hyperparameter Tuning
        ↓
Save Best Model
        ↓
Prediction
```

---

# 📈 Results

> This section will be updated after model training.

Example:

* Best Model:
* R² Score:
* MAE:
* RMSE:

---

# 🚀 Future Improvements

* Build a FastAPI backend.
* Develop a React frontend.
* Deploy the application.
* Add authentication.
* Track prediction history.
* Implement MLOps for model monitoring.

---

# ▶️ How to Run

```bash
git clone https://github.com/swarajpawarsj5/student-performance-prediction.git

cd student-performance-prediction

pip install -r requirements.txt

jupyter notebook
```

---

# 👨‍💻 Author

**Swaraj Pawar**

GitHub: https://github.com/swarajpawarsj5

LinkedIn: https://www.linkedin.com/in/swarajpawar5
