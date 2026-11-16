# 💼 Employee Salary Prediction Using Regression

## 📌 Project Overview

This project focuses on predicting employee salaries using Machine Learning regression techniques. The objective is to understand how employee-related factors influence salary and identify suitable regression models for making accurate salary predictions.

The project explores Simple Linear Regression, Multiple Linear Regression, and Polynomial Regression, comparing their performance and examining the impact of feature relationships and multicollinearity on model accuracy.

## 🎯 Project Objectives

- Analyze employee data to understand salary-related patterns.
- Perform Exploratory Data Analysis (EDA).
- Identify relationships between independent variables and salary.
- Apply different regression algorithms.
- Detect multicollinearity using Variance Inflation Factor (VIF).
- Improve model performance using Polynomial Regression.
- Evaluate and compare regression model performance.

## 📂 Dataset Information

- **Dataset:** Employee Performance Dataset
- **File:** `employee_performance(1).csv`
- **Target Variable:** Salary
- **Input Features:** 9 independent variables
- **Total Records:** 1,000

The dataset contains employee-related information used to analyze and predict salary.

*Note: Add the dataset file to your project folder before executing the notebooks. Check the dataset's license before redistributing it.*

## 🛠️ Technologies & Libraries Used

- **Programming Language:** Python
- **Environment:** Jupyter Notebook
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Statistical Analysis:** Statsmodels
- **Multicollinearity Analysis:** Variance Inflation Factor (VIF)

## 🔍 Project Workflow

### 1. Data Loading and Understanding
- Imported the employee dataset.
- Examined dataset dimensions and structure.
- Identified independent and dependent variables.
- Checked data types and basic statistical summaries.

### 2. Exploratory Data Analysis (EDA)
- Analyzed numerical features.
- Studied relationships between employee attributes and salary.
- Used visualizations to understand data patterns.
- Examined correlations between variables.

### 3. Simple Linear Regression
- Implemented Simple Linear Regression.
- Studied the relationship between an individual predictor and salary.
- Analyzed the regression fit and prediction results.

### 4. Multiple Linear Regression
- Implemented Multiple Linear Regression using multiple independent variables.
- Evaluated the relationship between multiple employee features and salary.
- Examined multicollinearity using Variance Inflation Factor (VIF).

### 5. Multicollinearity Analysis
Calculated VIF scores to identify highly correlated independent variables.

Initial VIF observations:

| Feature | VIF Score |
|---|---:|
| Age | 12.1073 |
| Experience_Years | 6.3947 |
| Performance_Score | 15.5050 |

After removing the three identified features for further analysis, the maximum VIF among the remaining features was approximately 6.2913.

### 6. Polynomial Regression
- Applied Polynomial Feature Transformation.
- Experimented with degree 3 polynomial features.
- Captured nonlinear relationships between input variables and salary.
- Evaluated training and testing performance.

## 📊 Model Performance

### Linear Regression

| Metric | R² Score |
|---|---:|
| Training R² | 0.2075 |
| Testing R² | 0.7512 |

### Polynomial Regression (Degree 3)

| Metric | R² Score |
|---|---:|
| Training R² | 0.8818 |
| Testing R² | 0.8801 |

**Key Observation:**

Polynomial Regression achieved a better balance between training and testing performance compared with the reported Linear Regression baseline.

The similar training and testing R² scores indicate that the degree 3 polynomial model captured useful patterns in the dataset while maintaining good generalization on the test set.

## 📁 Project Structure

```text
Employee_Salary_prediction/
│
├── Simple_linear_Regression.ipynb
├── Multi_linear_Regression.ipynb
├── Polynomial_Regression.ipynb
│
├── employee_performance(1).csv
│
└── README.md
```

## ▶️ How to Run the Project

**Step 1: Clone the repository**

```bash
git clone https://github.com/Akoju-Nandini/Employee_Salary_prediction.git
```

**Step 2: Navigate to the project directory**

```bash
cd Employee_Salary_prediction
```

**Step 3: Install the required libraries**

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels jupyter
```

**Step 4: Launch Jupyter Notebook**

```bash
jupyter notebook
```

**Step 5: Open and execute the notebooks**

Run the notebooks individually:

1. `Simple_linear_Regression.ipynb`
2. `Multi_linear_Regression.ipynb`
3. `Polynomial_Regression.ipynb`

Ensure the dataset is available at the file path specified in each notebook.

## 🚀 Key Learnings

- Understanding different regression techniques.
- Performing EDA and statistical analysis.
- Identifying multicollinearity using VIF.
- Understanding linear and nonlinear relationships.
- Applying polynomial feature transformation.
- Evaluating models using R² scores.
- Comparing training and testing performance.

## 🔮 Future Improvements

- Experiment with Ridge and Lasso Regression.
- Explore Elastic Net Regression.
- Perform cross-validation for more reliable model evaluation.
- Apply hyperparameter tuning.
- Develop an interactive salary prediction application using Streamlit.

## 👩‍💻 Author

**Akoju Nandini**

Computer Science Engineering Graduate | Aspiring Data Scientist

- GitHub: [Akoju-Nandini](https://github.com/Akoju-Nandini)
- Project Repository: [Employee Salary Prediction](https://github.com/Akoju-Nandini/Employee_Salary_prediction)

---

⭐ If you find this project useful, feel free to explore the notebooks and share your feedback!
