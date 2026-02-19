# 🚢 Task 5: Exploratory Data Analysis (EDA) - Titanic Dataset

---

## 🎯 Objective
- Understand dataset structure and features
- Handle and analyze missing values
- Perform univariate, bivariate, and multivariate analysis
- Identify key survival factors
- Present findings through visualizations and summary insights

---

## 📂 Dataset Information
- **Source:** Kaggle - Titanic: Machine Learning from Disaster
- **File Used:** `titanic.csv`

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Analysis Performed

### 1️⃣ Dataset Overview
- Used `.info()` to inspect data types and missing values
- Used `.describe()` for statistical summary
- Used `.value_counts()` for categorical distributions

### 2️⃣ Univariate Analysis
- Histograms for numeric distributions
- Boxplots to detect outliers
- Distribution analysis for Age and Fare

### 3️⃣ Bivariate & Multivariate Analysis
- Survival by Gender (Countplot)
- Survival by Passenger Class
- Correlation Heatmap
- Age vs Fare Scatter Plot
- Grouped survival analysis using `groupby()`

---

## 🔍 Key Insights

- ✅ Females had significantly higher survival rates than males.
- ✅ First-class passengers had better survival probability.
- ✅ Higher fare passengers were more likely to survive.
- ✅ Children had better survival chances compared to seniors.
- ⚠ Missing values were observed in Age, Cabin, and Embarked columns.

---

## 📌 Conclusion

The exploratory analysis clearly indicates that gender, passenger class, and fare significantly influenced survival outcomes in the Titanic disaster. The project demonstrates practical EDA skills including statistical analysis, visualization techniques, and structured reporting.

---