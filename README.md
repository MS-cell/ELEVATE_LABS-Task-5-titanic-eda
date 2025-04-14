# ELEVATE_LABS-Task-5-titanic-eda
Exploratory Data Analysis on Titanic dataset (EDA)


# 🚢 Titanic EDA – Exploratory Data Analysis | Task 5

<h1 align="center">Titanic - Exploratory Data Analysis</h1>

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fd/RMS_Titanic_3.jpg" alt="Titanic Banner" width="80%">
</p>


## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset using Python libraries such as **Pandas**, **Seaborn**, and **Matplotlib**. The goal is to uncover trends, detect anomalies, and extract meaningful insights from the data.

---

## 🧠 Objective

- Clean and preprocess the Titanic dataset
- Perform univariate, bivariate, and multivariate analysis
- Visualize relationships between features (like Age, Gender, Pclass, Fare, Survival)
- Summarize insights and patterns using visual storytelling

---

## 🧰 Tools & Technologies Used

| Tool         | Purpose                      |
|--------------|-------------------------------|
| Python       | Data analysis & processing    |
| Pandas       | Data manipulation             |
| Matplotlib   | Visualization                 |
| Seaborn      | Advanced plotting             |
| Jupyter Notebook | Coding & documentation   |

---

## 📂 Files in This Repository

| File Name             | Description                                      |
|----------------------|--------------------------------------------------|
| `titanic_eda.ipynb`  | Jupyter Notebook with full EDA                   |
| `titanic_eda.pdf`    | PDF version of the notebook                      |
| `train.csv`          | Training dataset with target column `Survived`   |
| `test.csv`           | Test dataset without labels                      |
| `gender_submission.csv` | Sample predictions (from Kaggle)             |
| `README.md`          | Project overview, summary, interview Q&A         |
| `screenshots/`       | Screenshots from EDA (plots and outputs)         |

---

## 📊 Key Findings (Summary)

- 👩‍🦰 **Gender:** Females had a significantly higher survival rate.
- 🏷️ **Class:** First-class passengers had the highest survival chance.
- 👶 **Age:** Children had relatively higher survival rates than adults.
- 💸 **Fare:** Passengers who paid higher fares tended to survive more.
- 🌍 **Embarked Port:** Passengers from Cherbourg had higher survival.

---

## 📈 Sample Visualizations

<img src="screenshots/age_distribution.png" width="400"/> <img src="screenshots/survival_by_class.png" width="400"/>
<img src="screenshots/heatmap.png" width="400"/> <img src="screenshots/pairplot.png" width="400"/>

> All charts are included in the notebook and PDF report

---

## 🧪 Process Followed

1. **Data Cleaning** – Handled missing values in `Age`, `Fare`, and removed `Cabin`.
2. **Univariate Analysis** – Explored individual features (Age, Sex, Fare, etc.)
3. **Bivariate Analysis** – Visualized survival by Sex, Pclass, Age.
4. **Multivariate Analysis** – Used heatmaps and pairplots to explore relationships.
5. **Observations** – Documented insights from each visualization.

---

## 🧩 Interview Questions & Answers

### 1️⃣ What is EDA and why is it important?
EDA (Exploratory Data Analysis) is the process of analyzing datasets to summarize their main characteristics using statistics and visualization. It helps in discovering patterns, spotting anomalies, testing hypotheses, and choosing the right model or preprocessing technique.

---

### 2️⃣ Which plots do you use to check correlation?
- `heatmap` (shows correlation matrix)
- `pairplot` (scatter plots for variable pairs)
- `scatterplot` (for two numerical variables)

---

### 3️⃣ How do you handle skewed data?
- Log transformation
- Square root transformation
- Box-Cox transformation
- Use of robust scaling or binning

---

### 4️⃣ How to detect multicollinearity?
- **Correlation matrix** (high correlation between independent variables)
- **Variance Inflation Factor (VIF)**

---

### 5️⃣ What are univariate, bivariate, and multivariate analyses?
- **Univariate**: Analysis of a single variable (e.g., histogram of Age)
- **Bivariate**: Analysis of two variables (e.g., survival by gender)
- **Multivariate**: Analysis of three or more variables (e.g., heatmap or pairplot)

---

### 6️⃣ Difference between heatmap and pairplot?
- **Heatmap**: Shows correlations as a matrix using color gradients
- **Pairplot**: Visualizes scatter plots and distributions between every pair of variables

---

### 7️⃣ How do you summarize your insights?
By combining visual observations and statistical summaries to highlight:
- Key trends
- Correlations
- Anomalies
- Possible feature importance

---

## ✅ Task Completed For:
**Data Analyst Internship – Task 5: EDA on Titanic Dataset**

---

## 📬 Connect
Feel free to connect on LinkedIn or GitHub if you’d like to collaborate or ask questions!

## Author

[Mihir Sonar](https://www.linkedin.com/in/mihir-sonar-2287041bb)

[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mihir-sonar-2287041bb)



---

