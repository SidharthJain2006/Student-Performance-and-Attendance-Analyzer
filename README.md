# 📊 Customer Spending Analysis and Segmentation

## 📌 Project Overview
This project analyzes customer demographics and spending behavior using the Mall Customers dataset. The objective is to identify patterns in customer spending, understand the influence of factors such as age, income, and gender, and generate business recommendations through statistical analysis and data visualization.

The project includes exploratory data analysis (EDA), inferential statistics, confidence interval estimation, and customer segmentation insights.

---

## 📅 Dataset Information
The dataset contains customer information collected by a shopping mall.

### Features
| Column | Description |
| :--- | :--- |
| **CustomerID** | Unique customer identifier |
| **Gender** | Male or Female |
| **Age** | Customer age |
| **Annual Income (k\$)** | Annual income in thousands of dollars |
| **Spending Score (1-100)** | Spending behavior score assigned by the mall |

---

## 🎯 Project Objectives
* Analyze customer demographics.
* Understand spending behavior patterns.
* Examine relationships between income, age, and spending score.
* Determine whether spending differs by gender.
* Calculate confidence intervals for spending scores.
* Generate actionable business recommendations.

---

## 🛠️ Technologies Used
* Python 3
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Google Colab / Jupyter Notebook

---

## 🔄 Project Workflow

### 1. Data Loading and Inspection
* Load dataset using Pandas.
* Check dataset shape and data types (`df.shape`, `df.dtypes`).
* Identify missing values (`df.isnull().sum()`).
* Generate descriptive statistics (`df.describe()`).

### 2. Data Cleaning
* Verify data quality.
* Check for null values.
* Ensure correct data types.

### 3. Exploratory Data Analysis (EDA)
**Performed:**
* Gender distribution analysis
* Age distribution analysis
* Annual income distribution
* Spending score distribution

**Visualizations Used:**
* Histograms
* Count plots
* Scatter plots
* Correlation analysis

### 4. Relationship Analysis
* **Annual Income vs Spending Score**
  * *Observation:* No strong positive relationship exists. High-income customers do not necessarily spend more.
* **Age vs Spending Score**
  * *Observation:* Younger customers tend to have higher spending scores. Spending generally decreases as age increases.

---

## 📊 Inferential Statistics

### Problem Statement
Do male and female customers spend differently?

### Hypotheses
* **Null Hypothesis ($H_0$):** There is no significant difference in spending scores between male and female customers.
* **Alternative Hypothesis ($H_1$):** There is a significant difference in spending scores between male and female customers.

### Statistical Test
* Independent Two-Sample T-Test

### Results
* **T-statistic:** `-0.8190`
* **P-value:** `0.4137`

### Conclusion
Since the p-value is greater than 0.05, we **fail to reject the null hypothesis**. There is no statistically significant difference between male and female spending scores.

---

## 📈 Confidence Interval Analysis

### Objective
Calculate a 95% Confidence Interval for Spending Score.

### Results
* **Mean Spending Score:** `50.2`
* **95% Confidence Interval:** `(46.62, 53.78)`

### Interpretation
We are 95% confident that the true population mean spending score lies between 46.62 and 53.78.

---

## 🔑 Key Findings
* Income alone is not a strong predictor of spending behavior.
* Younger customers generally spend more than older customers.
* Spending patterns do not differ significantly by gender.
* Customer behavior should be the primary basis for marketing decisions.
* High-spending customer groups offer the greatest business value.

---

## 💡 Business Recommendations

* **Target High-Spending Customers:** Focus promotional campaigns and loyalty programs on customers with high spending scores.
* **Behavioral Segmentation:** Segment customers based on spending behavior rather than demographic attributes alone.
* **Personalized Marketing:** Develop customized offers using customer spending patterns.
* **Age-Based Campaigns:** Since younger customers tend to spend more, create campaigns tailored to younger demographics.
* **Gender-Neutral Marketing:** Avoid gender-specific marketing strategies, as spending behavior does not significantly differ by gender.

---

## 📁 Project Structure
```text
Customer-Spending-Analysis/
│
├── Mini Project - 2.ipynb
├── Mall_Customers.csv
├── README.md
└── outputs/
    ├── visualizations/
    └── analysis_results/


---

## <b>🚀 Future Improvements</b>
* **Apply K-Means clustering** for automated customer behavioral segmentation.
* **Build predictive machine learning models** (such as Linear Regression or Random Forests) to forecast spending behavior based on demographic factors.
* **Develop interactive business intelligence dashboards** using Power BI or Tableau for real-time customer data exploration.
* **Perform advanced statistical analysis** (such as ANOVA or Chi-Square tests) on multi-group demographic factors.

---

## <b>✍️ Author</b>
**Sidharth Jain** *Data Analysis Mini Project*
