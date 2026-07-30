# Student Performance Exploratory Data Analysis (EDA)

An exploratory data analysis (EDA) project examining student academic performance across demographic factors, parental education levels, and test preparation completion using **Pandas**, **NumPy**, and **Matplotlib**.

---

##  Project Overview

This project explores the `Students Performance.csv` dataset to understand how various socioeconomic and academic factors influence student test scores in **Math**, **Reading**, and **Writing**. The analysis covers basic data exploration, conditional filtering, group aggregations, and statistical visual distributions.

---

##  Tech Stack & Tools

* **Language:** Python 3.x
* **Environment:** Jupyter Notebook / VS Code
* **Libraries:**
  * `pandas` — Data cleaning, filtering, and `groupby` aggregations
  * `numpy` — Numerical operations
  * `matplotlib` — Data visualization (histograms & grouped bar charts)

---

##  Key Steps & Analysis

### 1. Basic Data Exploration
* Analyzed overall dataset structure, data types, and shape ($1000 \text{ rows} \times 8 \text{ columns}$).
* Validated data integrity by checking for missing values.
* Computed summary statistics across numerical scores using `.describe()`.

### 2. Filtering & Conditional Selection
* Filtered students scoring above 70 in math and identified top-performing female students ($\ge 65$ across all three subjects).
* Calculated total student counts enrolled in free/reduced lunch programs.

### 3. GroupBy Aggregation & Findings
* Evaluated average performance trends categorized by gender, parental level of education, and test preparation course status.

### 4. Data Visualizations
* **Histograms:** Plotted score distributions across Math, Reading, and Writing to analyze performance variance.
* **Bar Plot:** Visualized mean subject performance by gender, annotating exact averages above each bar.

---

##  Key Takeaways

1. **Impact of Test Preparation:** Completing the test preparation course provided a noticeable boost across all subjects, yielding the highest performance increase in **Writing** (~10-point improvement).
2. **Subject Performance by Gender:** Female students achieved higher average scores in Reading and Writing, whereas male students showed slightly higher average performance in Math.
3. **Parental Education:** Students whose parents held higher education degrees consistently achieved higher overall mean scores across all three subjects.

---

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/macpedems1/exploratory-data-analysis-students-performance.git](https://github.com/macpedems1/exploratory-data-analysis-students-performance.git)
   cd exploratory-data-analysis-students-performance
