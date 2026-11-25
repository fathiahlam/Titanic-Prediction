# 🚢 Titanic Survival Analysis & Prediction

<div align="center">

  <a href="https://www.linkedin.com/in/ahlam-fathi-308549393">
    <img src="https://img.shields.io/badge/LinkedIn-536B58?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:ahlamfathi03@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-AE8060?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
  <a href="https://github.com/fathiahlam">
    <img src="https://img.shields.io/badge/GitHub-344C3D?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>

</div>

## 📌 Project Overview

This project explores the Titanic passenger dataset to identify the main factors influencing survival and develop a Machine Learning classification model to predict passenger survival.

It combines data preprocessing, exploratory analysis, statistical visualization, and predictive modeling to extract meaningful insights from historical passenger data.

## 🎯 Objectives

- Clean and prepare the Titanic dataset.
- Handle missing values and encode categorical variables.
- Analyze survival rates based on gender, age, and passenger class.
- Explore relationships between variables through statistical visualizations.
- Build a Random Forest classification model to predict survival.

## 🛠️ Technologies & Libraries

- **Python** – Core programming language.
- **Pandas** – Data manipulation and cleaning.
- **NumPy** – Numerical computing.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical visualization.
- **Scikit-learn** – Machine Learning and model evaluation.
- **Jupyter Notebook** – Interactive development environment.

## 📊 Project Workflow

### 1. Data Cleaning & Preprocessing

- Identification and treatment of missing values.
- Age imputation using the median according to passenger class (Pclass).
- Missing Embarked values replaced with the most frequent category.
- Encoding of categorical variables (Sex and Embarked).
- Removal of the Cabin column due to missing values.
- Documentation of modifications using a cleaning log.

### 2. Exploratory Data Analysis (EDA)

- Analysis of survival rates by gender.
- Comparison between children and adults.
- Analysis of survival rates across passenger classes.
- Investigation of the hypothesis: **"Women and children first".**
- Creation of a summary table of survival rates by category.

### 3. Machine Learning – Random Forest

- Selection of predictive features: Age, Pclass, Sex, Embarked, and Fare.
- Dataset splitting: 80% training and 20% testing.
- Model training using `RandomForestClassifier`.
- Survival prediction using the trained model.
- Model evaluation through a confusion matrix.

### 4. Data Visualization

- **Violin Plot:** Comparison of age distributions between survivors and non-survivors.
- **Correlation Heatmaps:** Exploration of relationships between numerical variables and survival.

## 📈 Key Findings

The analysis highlights the influence of gender, age, and passenger class on survival rates, revealing important patterns in passenger survival.

The Random Forest model achieved the following result on the test set:

| Evaluation Metric | Result |
|:---|:---:|
| Correct Predictions | 143 / 179 |
| Accuracy | **79.9%** |

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

## 👩‍💻 About This Project

This project reflects my interest in transforming real-world datasets into meaningful insights and predictive solutions. It was an opportunity to strengthen my skills in data analysis, statistical reasoning, and Machine Learning.

## 👩‍💻 Author

**Ahlam Fathi**  
Master's Student in Digital Engineering & AI (INIA)  
Interested in Data Science, Artificial Intelligence, and Machine Learning.

- **GitHub:** [Ahlam Fathi](https://github.com/fathiahlam)
- **LinkedIn:** [Ahlam Fathi](https://www.linkedin.com/in/ahlam-fathi-308549393)

---

<div align="center">

  *Turning data into insights, and insights into intelligent solutions.*

</div>
