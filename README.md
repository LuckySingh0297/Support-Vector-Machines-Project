# Support Vector Machines (SVM) Project

## 📌 Project Overview
This project demonstrates the implementation of **Support Vector Machine (SVM)** for classification using demographic and income-related data. The objective is to analyze income patterns and determine whether a suburban area is suitable for real-estate investment based on residents' earning potential.

---

## 🎯 Business Problem
A construction firm wants to develop infrastructure in a suburban locality but wants to minimize investment risk. By analyzing population demographics and income levels, the company can understand the purchasing power of residents and make better investment decisions.

---

## 🧠 Objective
Build an SVM classification model to predict whether an individual's salary is:

- `<=50K`
- `>50K`

This helps estimate:
- Economic stability
- Purchasing capability
- Real-estate investment viability

---

## 📂 Dataset
The dataset contains:
- Age
- Education
- Occupation
- Workclass
- Marital Status
- Hours per Week
- Capital Gain/Loss
- Income Category

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Project Workflow

### 1️⃣ Business Understanding
- Understanding investment-related business objectives
- Identifying target variable and constraints

### 2️⃣ Data Preprocessing
- Handling categorical features
- Label Encoding
- Feature Scaling using `StandardScaler`

### 3️⃣ Exploratory Data Analysis (EDA)
Performed:
- Income Distribution Analysis
- Age Distribution
- Education Analysis
- Occupation Analysis
- Correlation Heatmap
- Relationship between Age and Income

---

# 📊 Visualizations

## Income Distribution
![Income Distribution](Images/Target%20Variable%20Distribution.png)

## Age Distribution
![Age Distribution](Images/Age%20Distribution.png)

## Education Analysis
![Education Analysis](Images/Education%20Analysis.png)

## Occupation Analysis
![Occupation Analysis](Images/Occupation%20Analysis.png)

## Correlation Heatmap
![Correlation Heatmap](Images/Correlation%20Heatmap.png)

---

## 🤖 Model Building

Implemented multiple SVM kernels:
- Linear Kernel
- RBF Kernel
- Polynomial Kernel

Performed:
- Hyperparameter Tuning using `GridSearchCV`
- Cross Validation
- Model Evaluation

---

## 📈 Model Evaluation

Evaluation Metrics Used:
- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 🏆 Results

| Model | Accuracy |
|---|---|
| Linear SVM | Good |
| RBF SVM | Best Performance |
| Polynomial SVM | Moderate |

The tuned RBF kernel provided the best classification performance.

---

## 💡 Business Insights

- Highly educated individuals tend to earn higher salaries.
- Middle-aged professionals show stronger purchasing power.
- Managerial and executive occupations indicate stable economic conditions.
- The suburban locality shows promising investment potential based on income analysis.

---

## 🚀 Key Learnings

- Understanding Support Vector Machines
- Importance of Feature Scaling in SVM
- Hyperparameter Tuning
- EDA and Business Insights
- Model Evaluation Techniques

---

## 📁 Project Structure

```bash
Support-Vector-Machines-Project/
│
├── Images/
├── Svm.ipynb
├── SalaryData_Train.csv
├── SalaryData_Test.csv
└── README.md
```

---

## 🛠️ Future Improvements

- Use PCA for dimensionality reduction
- Deploy model using Flask/Streamlit
- Compare SVM with Random Forest and XGBoost
- Perform advanced feature engineering

---

## 👨‍💻 Author

### Lucky Singh

Aspiring Data Scientist passionate about:
- Machine Learning
- Data Analytics
- AI Projects
- Real-world Business Problem Solving

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub!
