# **Adult Workforce Analysis**
### A Comprehensive Data Cleaning and Statistical Analysis Project

## **Overview**
This project explores a dataset through **data cleaning, preprocessing, and statistical analysis** using **pandas**, **seaborn**, and **Matplotlib**.

## **Objectives**
- Handle missing and duplicate values.
- Perform **univariate** and **bivariate** analysis.
- Optimize memory usage.
- Generate insights through data visualization.

## **Dataset Information**
- **Number of Records:** 📊 48842 rows 
- **Number of Features:** 📑 15 columns  
- **Key Columns:**  
  - `age`: Age of individuals  
  - `workclass`: Type of employer (Private, Public, Self-employed, etc.)  
  - `education`: Educational background  
  - `occupation`: Field of work  
  - `hours-per-week`: Weekly working hours  
  - `salary`: Income category (`<=50K` or `>50K`)  

## **Dataset Preprocessing**
- **Replace Missing Values** (`? → NaN`)
- **Remove Duplicates**
- **Convert Data Types for Optimization**

## **Key Features**
- Fetch random samples
- Check null values
- Drop irrelevant columns
- Data distribution analysis
- Convert categorical columns to optimized types

## **Analysis and Results**
### 🔍 **Top Insights from Univariate and Bivariate Analysis**
- The **majority of individuals** are employed in the **private sector**.
- Individuals with **higher education levels (Bachelors/Masters)** have a **higher likelihood** of earning more than **50K**.
- **Males** have a higher proportion of earnings **above 50K** compared to females.
- **Self-employed individuals** exhibit more **variability** in income distribution.

### 🛠 **Memory Reduction through Datatype Conversion**
- Converted categorical columns (e.g., `workclass`, `education`) into **category** datatype.
- Reduced memory usage from **XX MB to YY MB** by optimizing numeric columns.

### 📈 **Predictive Factors Affecting Salary Distribution**
- **Education Level:** Higher education correlates with higher income.
- **Workclass:** Private sector employees form the majority, but government employees have a stable income distribution.
- **Occupation:** Certain professions, such as executive roles, show a significantly higher income level.
- **Hours Worked Per Week:** People working **more than 40 hours** tend to have higher salaries.

---

## **Installation**
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/data-analysis-project.git
  
2. Install required dependencies:
```
  pip install pandas numpy seaborn matplotlib
```

## 🤝 Contributing

We welcome contributions! 🚀  

To contribute, follow these steps:  

1. **Fork** this repository  
2. **Create** a new branch (`feature-branch`)  
3. **Commit** your changes  
4. **Submit** a **Pull Request**  

Let's build a better analysis together! 


##📜 License
This project is licensed under the MIT License.
