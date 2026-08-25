## 🦠 COVID-19 Data Analysis

## 📌 Project Overview

This project presents a comprehensive **Data Science analysis of COVID-19 cases and deaths** across the United States.

The analysis focuses on county- and state-level COVID-19 data and integrates multiple enrichment datasets to investigate how **population, demographic, socioeconomic, employment, and other factors** relate to COVID-19 cases and deaths.

The project covers the complete data science workflow, including:

* Data collection and understanding
* Data cleaning and preprocessing
* Dataset integration
* Exploratory Data Analysis (EDA)
* Statistical analysis
* Data visualization
* Distribution modeling
* Correlation analysis
* Hypothesis testing
* Machine Learning

---

## 👥 Project 
* **Ravya Vangaveti**
---

## 📄 Project Report

The complete analysis, methodology, visualizations, statistical results, and machine-learning experiments are available in the project report.

📖 **[View Full COVID-19 Data Analysis Report](./COVID-19-Data-Analysis.pdf)**

---

# 🎯 Project Objective

The primary objective of this project is to analyze **COVID-19 cases and deaths at the county level in the United States**.

COVID-19 data was combined with population and enrichment datasets to investigate patterns in the spread and impact of the pandemic.

The project attempts to answer questions related to:

* How COVID-19 cases and deaths changed over time
* Differences between states and counties
* The relationship between population and COVID-19 outcomes
* Demographic influences on cases and deaths
* Employment and socioeconomic factors
* Statistical relationships between enrichment variables and COVID-19 outcomes
* Prediction of COVID-19 cases and deaths using Machine Learning

---

# 📊 Datasets

## 🦠 COVID-19 Data

The primary COVID-19 analysis uses three major datasets:

### 1. County Population Dataset

Contains population information for U.S. counties.

Important variables include:

* County FIPS Code
* County Name
* State
* Population

### 2. Confirmed Cases Dataset

Contains daily confirmed COVID-19 cases at the county level.

Important variables include:

* FIPS Code
* County
* State
* Date
* Confirmed Cases

### 3. COVID-19 Deaths Dataset

Contains daily COVID-19 deaths at the county level.

Important variables include:

* FIPS Code
* County
* State
* Date
* Deaths

---

# 🔗 Data Integration

The COVID-19 datasets were cleaned and integrated using common identifiers such as **county FIPS codes**.

The resulting dataset contains information such as:

```text
County FIPS Code
County Name
State
Population
Daily Confirmed Cases
Daily Deaths
```

This integrated dataset serves as the foundation for the subsequent statistical and Machine Learning analysis.

---

# 🌎 Enrichment Data

Additional datasets were incorporated to explore factors that may be associated with COVID-19 cases and deaths.

### 👥 Census Demographic Data

American Community Survey (ACS) demographic information was incorporated to analyze factors such as:

* Population
* Age distribution
* Sex
* Race and ethnicity
* Household characteristics

### 🏠 ACS Social, Economic & Housing Data

Social, economic, housing, and demographic information was incorporated to investigate relationships between socioeconomic conditions and COVID-19 outcomes.

### 💼 Employment Data

Employment and wage datasets were integrated with COVID-19 data.

The employment analysis included:

* County employment estimates
* State employment estimates
* Employment and wages
* Establishments
* Average weekly wages

The analysis explored questions such as:

> Does higher employment affect the number of COVID-19 cases?

> Does a higher average weekly wage relate to higher COVID-19 case numbers?

> Do regions with more establishments experience different COVID-19 case patterns?

### 🗳️ Presidential Election Results

2020 U.S. Presidential Election data was also used as an enrichment dataset for examining relationships between county-level variables and COVID-19 outcomes.

---

# 🧹 Stage I — Data Understanding & Preparation

The first stage focused on preparing the datasets for analysis.

Major steps included:

1. Reading COVID-19 datasets
2. Understanding variables and data types
3. Cleaning missing and inconsistent values
4. Standardizing FIPS codes
5. Merging COVID-19 datasets
6. Integrating enrichment datasets
7. Creating a consolidated COVID-19 dataframe
8. Exploring initial trends
9. Developing initial hypothesis questions

---

# 📈 Stage II — Data Modeling & Trend Analysis

The second stage focused on statistical summaries and COVID-19 trends.

Weekly statistics were calculated for COVID-19 cases and deaths, including:

* **Mean**
* **Median**
* **Mode**

The analysis also compared COVID-19 patterns across different U.S. states and international datasets.

### Population Normalization

Cases and deaths were normalized by population to enable more meaningful comparisons between regions of different sizes.

A commonly used measure was:

```text
Cases per 100,000 population
Deaths per 100,000 population
```

### County-Level Analysis

Counties with high numbers of cases and deaths were identified and analyzed.

Both:

```text
Raw Values
vs.
Log-Normalized Values
```

were examined to better understand growth patterns and differences between counties.

---

# 📊 Stage III — Statistical Distributions & Hypothesis Testing

The third stage focused on statistical modeling of COVID-19 data.

## Distribution Analysis

COVID-19 cases and deaths were examined using statistical distributions.

The analysis included:

* Distribution fitting
* Mean
* Median
* Variance
* Skewness
* Kurtosis

### Poisson Distribution

Poisson distributions were modeled for COVID-19 cases and deaths, including population-normalized measures.

### Negative Binomial Analysis

Negative Binomial distributions were also examined where the observed variance exceeded the mean.

---

# 🔬 Correlation Analysis

Correlation analysis was performed between COVID-19 outcomes and enrichment variables.

Examples included relationships involving:

```text
Employment
Average Weekly Wages
Population
Demographics
Establishments
COVID-19 Cases
COVID-19 Deaths
```

Correlation heatmaps and scatter plots were used to visualize relationships between variables.

---

# 🧪 Hypothesis Testing

Several hypotheses were investigated throughout the project.

Examples include:

### Employment

**Question:** Does higher employment affect the number of COVID-19 cases?

### Wages

**Question:** Does a higher average weekly wage relate to higher COVID-19 case numbers?

### Population

**H₀:** There is no significant relationship between population size and COVID-19 cases.

**H₁:** There is a significant relationship between population size and COVID-19 cases.

### Demographics

The project also investigated potential relationships between COVID-19 outcomes and:

* Age groups
* Younger populations
* Sex distribution
* Population density
* Household income
* Educational attainment

---

# 🤖 Stage IV — Machine Learning

The project extends the statistical analysis into **Machine Learning**.

Machine-learning models were developed to analyze and predict COVID-19 cases and deaths.

One of the major tasks involved developing **Linear Regression and Polynomial Regression models** for predicting cases and deaths in the United States.

The modeling workflow included:

```text
COVID-19 Dataset
       ↓
Data Filtering
       ↓
Feature Preparation
       ↓
Train/Test Data
       ↓
Machine Learning Model
       ↓
Prediction
       ↓
Model Evaluation
```

---

# 📊 Data Visualization

The project contains extensive visual analysis, including:

* COVID-19 case trends
* COVID-19 death trends
* Weekly statistics
* State comparisons
* County comparisons
* Histograms
* Distribution plots
* Correlation heatmaps
* Scatter plots
* Raw vs. normalized comparisons
* Machine-learning predictions

These visualizations help identify patterns, peaks, correlations, and differences between geographic regions.

---

# 🛠️ Technologies & Concepts

### Programming & Data Analysis

`Python` • `Pandas` • `NumPy`

### Visualization

`Matplotlib` • `Plotly` • `Data Visualization`

### Machine Learning

`Scikit-learn` • `Linear Regression` • `Polynomial Regression`

### Statistics

`Poisson Distribution` • `Negative Binomial Distribution` • `Mean` • `Median` • `Variance` • `Skewness` • `Kurtosis`

### Data Engineering

`Data Cleaning` • `Data Integration` • `Data Transformation` • `Feature Engineering` • `FIPS-based Merging`

### Analysis

`EDA` • `Correlation Analysis` • `Hypothesis Testing` • `Time-Series Analysis`

---

# 📂 Suggested Repository Structure

```text
COVID-19-Data-Analysis/
│
├── README.md
│
├── COVID-19-Data-Analysis.pdf
│
├── notebooks/
│   └── covid_analysis.ipynb
│
├── data/
│   └── README.md
│
└── images/
    └── visualizations/
```

---

# 🚀 Key Takeaways

This project demonstrates an end-to-end Data Science workflow by combining **COVID-19 data with demographic, socioeconomic, employment, and other enrichment datasets**.

The analysis demonstrates experience with:

* Working with large datasets
* Cleaning and merging multiple data sources
* Exploratory Data Analysis
* Statistical modeling
* Distribution analysis
* Population normalization
* Correlation analysis
* Hypothesis testing
* Data visualization
* Machine Learning
* Predictive modeling

---

## 📄 Full Project Documentation

For detailed methodology, analysis, graphs, statistical results, and Machine Learning experiments:

### 👉 [View the Complete COVID-19 Data Analysis Report](./COVID-19-Data-Analysis.pdf)

---

<div align="center">

### 🦠 COVID-19 Data Analysis

**Data Science • Statistics • Machine Learning • Data Visualization**

⭐ If you find this project interesting, feel free to explore the repository.

</div>

