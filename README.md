# 🌍 Global Mental Health Analytics Dashboard (1990–2020)
An end-to-end Power BI project analyzing global mental health trends, combining prevalence and DALYs to uncover patterns, compare severity, and support data-driven public health insights.

## 📊 Project Overview

This project analyzes the global prevalence and disease burden of major mental health disorders across 214 countries over a 30-year period (1990–2020).

The goal is to uncover patterns, compare disorder impact, and provide insights to support data-driven decision-making in public health.

---

## 🎯 Objectives

* Analyze global trends in mental health prevalence
* Compare disease burden using DALYs (Disability-Adjusted Life Years)
* Identify the most affected and most critical countries
* Evaluate the relationship between prevalence and severity

---

## 📁 Dataset

Source: Kaggle (Global Mental Health Dataset)

The dataset includes:

* Country (Entity)
* Year (1990–2020)
* Disorder types:

  * Anxiety disorders
  * Depressive disorders
  * Bipolar disorders
  * Schizophrenia
  * Eating disorders
* Metrics:

  * Prevalence (% of population)
  * DALYs (disease burden)

---

## 🧠 Data Model

A star schema was implemented:

* **Fact Tables**

  * Fact_Prevalence
  * Fact_DALYs

* **Dimension Tables**

  * Dim_Country
  * Dim_Year
  * Dim_Disorder

Data was transformed using Power Query, including unpivoting for analysis efficiency.

---

## 📈 Key Metrics

* Average Prevalence Rate
* Maximum Prevalence Rate
* Average DALYs Rate
* Disease Burden Ratio (DALYs / Prevalence)
* Most Critical Country

---

## 📊 Dashboard Pages

### 1. Prevalence Analysis

* Global trends over time
* Distribution by disorder
* Top 10 countries by prevalence

### 2. DALYs Analysis

* Disease burden trends
* Most burdened countries
* Disorder impact comparison

### 3. Comparative Analysis

* Scatter plot (Prevalence vs DALYs)
* Dual trend analysis
* Burden ratio insights

---

## 🔍 Key Insights

* Anxiety disorders are the most prevalent globally
* Depressive disorders contribute the highest disease burden
* Some disorders are less common but highly severe
* Significant variation exists across countries

---

## 🛠 Tools & Technologies

* Power BI (Data modeling & visualization)
* DAX (Measures & calculations)
* Power Query (Data transformation)

---

## 📷 Dashboard Preview

### Prevalence Page

![Prevalence](images/prevalence_page.png)

### DALYs Page

![DALYs](images/dalys_page.png)

### Comparative Page

![Comparison](images/comparison_page.png)

---

## 🚀 How to Use

1. Download the `.pbix` file from the `dashboard` folder
2. Open in Power BI Desktop
3. Interact using filters (Country, Year, Disorder)

---

## 📌 Author

**Bright Twumasi Marfo**
Data Analytics | Compliance | Business Intelligence

---

## 💡 Future Improvements

* Add regional analysis
* Integrate real-time health datasets
* Build predictive models for trend forecasting

---

