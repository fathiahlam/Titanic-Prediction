# 🚢 Titanic Survival Analysis & Prediction

## 📌 Project Overview

This project explores the Titanic passenger dataset to identify the main factors influencing survival and develop a Machine Learning classification model to predict passenger survival.

## 🎯 Objectives

- Clean and prepare the Titanic dataset.
- Handle missing values and encode categorical variables.
- Analyze survival rates based on gender, age, and passenger class.
- Explore relationships between variables through statistical visualizations.
- Build a Random Forest classification model to predict survival.

## 🛠️ Technologies & Libraries

- **Python**
- **Pandas** – Data manipulation and cleaning.
- **NumPy** – Numerical computing.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical visualization.
- **Scikit-learn** – Machine Learning and model evaluation.
- **Jupyter Notebook** – Development environment.

## 📊 Project Workflow

### 1. Data Cleaning & Preprocessing
- Identification and treatment of missing values.
- Age imputation using the median according to passenger class (Pclass).
- Missing Embarked values replaced with the most frequent category.
- Encoding of categorical variables (Sex and Embarked).
- Removal of the Cabin column due to missing values.
- Documentation of modifications using a cleaning log.

### 2. Sociological Data Analysis
- Analysis of survival rates by gender.
- Comparison between children and adults.
- Analysis of survival rates across passenger classes.
- Investigation of the hypothesis: "Women and children first".
- Creation of a summary table of survival rates by category.

### 3. Machine Learning – Random Forest
- Selection of predictive features: Age, Pclass, Sex, Embarked and Fare.
- Dataset splitting: 80% training and 20% testing.
- Model training using RandomForestClassifier.
- Survival prediction using the trained model.
- Model evaluation through a confusion matrix.

### 4. Data Visualization
- Violin Plot: Comparison of age distributions between survivors and non-survivors.
- Correlation Heatmaps: Exploration of relationships between numerical variables and survival.

## 📈 Key Findings

The analysis highlights the influence of gender, age, and passenger class on survival rates.

The project conclusion reports 143 correct predictions out of 179 test observations, representing approximately 79.9% accuracy.

## 📁 Repository Structure

```text
Titanic-Prediction/
│
├── Projet_Titanic.ipynb
├── Titanic-Dataset.csv
├── README.md
└── .gitignore
```

## 🎓 Skills Developed

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Data Visualization
- Machine Learning
- Classification with Random Forest
- Model Evaluation

## 👩‍💻 Project

Developed as part of my learning journey in Data Science and Machine Learning.
---

## 👩‍💻 Author

**Ahlam Fathi**  
AI & Data Science Master's Student

- **GitHub:** [Ahlam Fathi](https://github.com/fathiahlam)
- **LinkedIn:** [Ahlam Fathi](www.linkedin.com/in/ahlam-fathi-308549393)

---
