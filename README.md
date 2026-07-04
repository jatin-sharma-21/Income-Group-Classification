# 💼 Income Group Classification using Logistic Regression

A Machine Learning project that predicts whether an individual's annual income is **above or below $50K** using demographic, educational, and employment-related attributes. The project leverages **Logistic Regression**, comprehensive exploratory data analysis (EDA), feature engineering, statistical modeling, and threshold optimization to support data-driven policy decisions.

---

## 📌 Project Overview

Income classification plays a crucial role in identifying socio-economic groups and enabling governments and organizations to design targeted welfare policies.

This project builds a predictive classification model using demographic and employment data to classify individuals into two income groups:

- **<= $50K**
- **> $50K**

The project follows a complete end-to-end machine learning pipeline, including data preprocessing, exploratory analysis, feature engineering, model development, statistical validation, and performance optimization.

---

## 🎯 Business Objective

Develop a machine learning model that accurately classifies individuals into income groups, helping policymakers identify underprivileged populations and allocate resources more effectively.

---

## 📂 Dataset

The project uses the **Adult Income (Census Income)** dataset containing demographic, educational, and employment information.

### Key Features

- Age
- Workclass
- Education
- Education Number
- Marital Status
- Occupation
- Race
- Gender
- Hours Worked per Week
- Native Country
- Capital Gain
- Capital Loss
- Final Weight (fnlwgt)

### Target Variable

- **Salary**
  - `<=50K`
  - `>50K`

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

---

## 📊 Exploratory Data Analysis (EDA)

The project includes extensive exploratory analysis, including:

- Data quality assessment
- Missing value handling
- Duplicate record detection
- Distribution analysis
- Outlier detection
- Univariate Analysis
- Bivariate Analysis
- Correlation Analysis
- Feature relationship analysis
- Class distribution visualization

---

## ⚙️ Data Preprocessing

The following preprocessing techniques were applied:

- Standardized column names
- Missing value handling by replacing unknown values
- Grouped countries into geographic regions
- Simplified marital status categories
- Outlier treatment using the IQR method
- One-Hot Encoding of categorical variables
- Feature selection
- Train-Test Split (70:30)

---

## 🤖 Machine Learning Models

### Primary Model

- Logistic Regression (Scikit-learn)

### Statistical Model

- Logistic Regression (Statsmodels)

The Statsmodels implementation was used to evaluate:

- Statistical significance of predictors
- P-values
- Odds Ratios
- Confidence Intervals
- Feature importance

---

## 📈 Model Evaluation

The model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve
- ROC-AUC Score
- Precision-Recall Curve

The project also explores threshold optimization to improve classification performance while balancing precision and recall.

---

## 📊 Statistical Analysis

Additional statistical techniques include:

- Variance Inflation Factor (VIF) for multicollinearity detection
- Feature selection based on p-values
- Odds ratio interpretation
- Threshold optimization using ROC and Precision-Recall curves
- Logistic Regression coefficient analysis

---

## 📁 Project Structure

```
Income-Group-Classification/
│
├── income_group_classification.py
├── who_data.csv
├── README.md
└── requirements.txt
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Income-Group-Classification.git
```

Navigate to the project directory:

```bash
cd Income-Group-Classification
```

Install the required dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```

Run the project:

```bash
python income_group_classification.py
```

---

## 📌 Project Highlights

- Performed comprehensive data cleaning and preprocessing.
- Conducted detailed exploratory data analysis to identify income-related trends.
- Engineered features by grouping countries and simplifying categorical variables.
- Built Logistic Regression models using both Scikit-learn and Statsmodels.
- Evaluated statistical significance using p-values and Odds Ratios.
- Reduced multicollinearity using Variance Inflation Factor (VIF).
- Optimized classification thresholds using ROC and Precision-Recall analysis.
- Achieved an **F1 Score of approximately 0.89**, demonstrating strong model generalization on both training and testing datasets.

---

## 💡 Key Insights

- Higher education significantly increases the likelihood of earning above **$50K**.
- Married individuals generally have higher income levels than unmarried individuals.
- Working hours show a positive relationship with annual income.
- Employment type and occupation strongly influence income classification.
- Feature engineering and statistical validation improved model interpretability.

---

## 🚀 Future Improvements

- Compare Logistic Regression with Random Forest, XGBoost, and LightGBM.
- Perform hyperparameter tuning using GridSearchCV.
- Address class imbalance using SMOTE or class weighting.
- Deploy the model using Streamlit or Flask.
- Build an interactive dashboard for income prediction and policy analysis.


## 📜 License

This project is intended for educational and learning purposes.
