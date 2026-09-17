# 🏥 Healthcare Analytics for Doctor Visits

## 📌 Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** of healthcare data to understand patterns in doctor visits. The analysis explores how factors such as **gender, age, illness score, and other health-related variables** are associated with the number of doctor visits.

The project uses Python-based data analysis and visualization techniques to transform the raw healthcare dataset into meaningful insights.

---

## 🎯 Objectives

* Analyze the distribution of doctor visits.
* Explore doctor visit patterns across different genders.
* Study the relationship between illness score and doctor visits.
* Examine the relationship between age and doctor visits.
* Identify meaningful patterns and trends within the healthcare dataset.
* Present findings using statistical analysis and visualizations.

---

## 📊 Dataset

The dataset contains **5,190 patient records and 13 variables**.

The variables include information related to:

* Doctor visits
* Gender
* Age
* Income
* Illness score
* Health status
* Reduced activity
* Private healthcare coverage
* Chronic health conditions
* Other patient-related factors

The notebook also performs data inspection and missing-value analysis before conducting the exploratory analysis.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** for data manipulation and analysis
* **NumPy** for numerical operations
* **Matplotlib** for data visualization
* **Seaborn** for statistical visualizations
* **Jupyter Notebook / Google Colab**

---

## 🔍 Analysis Performed

### 1. Data Understanding

* Loaded the healthcare dataset.
* Examined the dataset structure and dimensions.
* Checked column names and data types.
* Generated descriptive statistics.
* Checked for missing values.

### 2. Doctor Visit Analysis

The distribution of doctor visits was analyzed to understand the overall healthcare utilization pattern.

### 3. Gender Analysis

Doctor visits were compared across male and female patients.

The analysis found:

| Gender | Average Doctor Visits |
| ------ | --------------------: |
| Female |                 0.362 |
| Male   |                 0.236 |

### 4. Illness Score Analysis

The relationship between illness score and average doctor visits was examined.

| Illness Score | Average Doctor Visits |
| ------------: | --------------------: |
|             0 |                 0.079 |
|             1 |                 0.295 |
|             2 |                 0.404 |
|             3 |                 0.421 |
|             4 |                 0.577 |
|             5 |                 0.814 |

The analysis shows that the average number of recorded doctor visits increases with the illness score in this dataset.

### 5. Age and Doctor Visits

Age was analyzed in relation to doctor visits using visualization techniques to identify possible patterns between patient age and healthcare utilization.

---

## 📈 Key Insights

* The dataset contains **5,190 records across 13 variables**.
* No missing values were identified during the data-quality check.
* Female patients have a higher average number of recorded doctor visits than male patients in this dataset.
* Average doctor visits increase as the illness score increases.
* Patients with an illness score of **5** have the highest average number of recorded doctor visits.
* Visualizations help identify relationships between demographic and health-related variables and doctor visits.

---

## 📂 Project Structure

```text
Healthcare-Analytics-for-Doctor-Visits/
│
├── healthcare_analytics.ipynb
├── healthcare_dataset.csv
└── README.md
```

> File names may vary depending on the files uploaded to the repository.

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone <your-repository-link>
```

### 2. Open the notebook

Open:

```text
healthcare_analytics.ipynb
```

using **Jupyter Notebook** or **Google Colab**.

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### 4. Run the notebook

Execute the cells sequentially to reproduce the data analysis and visualizations.

---

## 💡 Conclusion

This project demonstrates how **Exploratory Data Analysis can be used to understand healthcare utilization patterns**. By examining doctor visits alongside demographic and health-related variables, the analysis provides a clearer view of the patterns present in the dataset.

> **“From doctor visits to data-driven insights, every pattern tells a story.”**

---

## 👩‍💻 Author

**Trina Dasgupta**
B.Sc. Information Technology (Data Science)
Maulana Abul Kalam Azad University of Technology (MAKAUT)
