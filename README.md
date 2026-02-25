# 📊 Marketing Data Analysis Project

## 📌 Project Overview
This project focuses on exploratory data analysis (EDA) and hypothesis testing to understand how marketing factors — product, price, place, and promotion — influence customer acquisition and behavior.

The analysis was performed using Python in Jupyter Notebook.

---

## 🎯 Objectives

- Perform data cleaning and preprocessing
- Engineer meaningful customer variables
- Conduct correlation analysis
- Perform hypothesis testing
- Generate business-driven visual insights
- Evaluate marketing effectiveness

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

---

## 📂 Dataset

**File Used:** `marketing_data.csv`

The dataset includes:
- Customer demographics
- Income information
- Education and marital status
- Product spending
- Campaign acceptance data
- Purchase behavior

---

## 🔎 Project Workflow

### 1️⃣ Data Import & Inspection
- Imported required libraries
- Loaded dataset into DataFrame
- Checked structure, data types, and missing values

### 2️⃣ Data Cleaning & Preparation
- Cleaned Income column and converted to float
- Converted Dt_Customer to datetime format
- Imputed missing values using grouped averages
- Cleaned categorical variables

### 3️⃣ Feature Engineering
- Calculated Age
- Derived Total Spending
- Computed Children Count
- Created Has_Children flag
- Calculated Total Purchases

### 4️⃣ Outlier Treatment
- Visualized distributions using boxplots and histograms
- Capped extreme outliers

### 5️⃣ Encoding
- Applied ordinal encoding for Education
- Applied one-hot encoding for Country and Marital Status

### 6️⃣ Correlation Analysis
- Computed correlation matrix
- Visualized relationships using heatmap

### 7️⃣ Hypothesis Testing
- Conducted t-tests to evaluate marketing impact
- Analyzed campaign effectiveness statistically

### 8️⃣ Visualization & Insights
- Product performance analysis
- Campaign acceptance trends
- Country-wise campaign success
- Income vs Spending relationship
- Customer demographic insights

---

## 📊 Business Impact

This analysis helps:

- Improve marketing strategy effectiveness
- Identify high-value customer segments
- Optimize campaign targeting
- Enhance customer engagement
- Support data-driven marketing decisions

---

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/sharmaprabudh/marketing-data-analysis.git
   ```

2. Navigate to the project directory:
   ```bash
   cd marketing-data-analysis
   ```

3. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Run all cells in the notebook.

---

## 👤 Author

Prabudh Sharma  
Data Analyst | Python | Data Visualization
