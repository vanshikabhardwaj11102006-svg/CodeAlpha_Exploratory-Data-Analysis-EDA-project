# Exploratory Data Analysis (EDA) - Titanic Dataset

This repository contains a comprehensive **Exploratory Data Analysis (EDA)** project conducted inside a Google Colab notebook. Using the historical Titanic passenger dataset, this project walks through the essential phases of data data preparation, cleaning, statistical analysis, and data visualization to uncover the underlying patterns behind passenger survival rates.

## 🚀 Project Overview

The goal of this project is to understand what factors made a passenger more likely to survive the Titanic disaster. We explore demographics (age, gender), socio-economic status (ticket class, fare), and family sizes to extract meaningful insights.

### Key Steps Addressed:
1. **Data Ingestion:** Loading data directly via URL using Pandas.
2. **Data Inspection & Quality Check:** Identifying missing values, evaluating data shapes, and verifying data types.
3. **Data Cleaning:** Handling missing data appropriately through median/mode imputation and removing irrelevant columns with high missing ratios.
4. **Univariate Analysis:** Analyzing individual distributions of target and key predictor variables using histograms and count plots.
5. **Bivariate/Multivariate Analysis:** Exploring structural interactions between variables (e.g., how gender and class jointly impacted survival).
6. **Correlation Analysis:** Mapping a feature correlation matrix using a Seaborn heatmap.

---

## 📊 Key Insights Uncovered

* **The "Women and Children First" Rule:** Gender was the strongest predictor of survival. Approximately 74% of female passengers survived, compared to only ~18% of male passengers.
* **Socio-Economic Class Privilege:** Passengers in 1st Class (`Pclass = 1`) had a significantly higher survival rate than those in 2nd and 3rd Class.
* **Demographic Tragedies:** The age distribution peaks around 20–30 years old, representing the largest demographic group lost.

---

## 🛠️ Tech Stack & Libraries

* **Environment:** Google Colab / Jupyter Notebooks
* **Language:** Python 3.x
* **Libraries Used:**
  * **Pandas:** For data manipulation and structural analysis.
  * **NumPy:** For mathematical calculations.
  * **Matplotlib:** For underlying plot configurations.
  * **Seaborn:** For advanced statistical data visualizations (Heatmaps, Countplots, Histograms, Barplots).

---

## 💻 How to Run This Project

You can run this project effortlessly without setting up a local environment:

1. Copy the code provided in the project files.
2. Navigate to [Google Colab](https://colab.research.google.com/).
3. Click on **New Notebook**.
4. Paste the code into sequential cells and press `Shift + Enter` to run them.
