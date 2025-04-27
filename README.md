# 📚 HELP International - Unsupervised Learning Project

## Project Overview

HELP International is dedicated to delivering humanitarian aid worldwide. This project uses **unsupervised machine learning** techniques to help HELP International **identify countries with the greatest need** based on socio-economic, health, and development indicators.

Our analysis aims to recommend where resources should be prioritized based on clustering techniques and exploratory data analysis (EDA).

---

## 🛠️ Project Workflow

1. **EDA (Exploratory Data Analysis)**  
   - Data cleaning and type conversion.
   - Identification of key variables influencing need (e.g., child mortality, GDP per capita, health expenditures).
   - Correlation analysis to find relationships between variables.

2. **Feature Engineering**  
   - Grouped variables into three main categories:
     - **Health** (child mortality, fertility rate, life expectancy)
     - **Commerce** (imports, exports)
     - **Economics** (income, inflation, GDP, health spending)
   - Created new standardized features for clustering.

3. **Model Training**  
   - Implemented and compared three clustering models:
     - **K-Means Clustering**
     - **DBSCAN Clustering**
     - **Hierarchical Clustering**
   
4. **Model Comparisons**  
   - Evaluated clustering performance using visualizations (2D and 3D plots, heatmaps).
   - Identified the most logical groupings for countries in need.

5. **Conclusions and Recommendations**  
   - **K-Means and Hierarchical Clustering** yielded the most meaningful results.
   - **Hierarchical Clustering** was more selective and would be recommended if resources are limited.
   - **K-Means** is recommended for broader resource allocation when more aid is available.
   - **DBSCAN** was less effective for this particular humanitarian need context.

---

## 📊 Key Results

- 43 countries were identified in the **highest need cluster** using K-Means.
- Hierarchical clustering provided an even **more focused** list for resource allocation.
- Examples of key countries: Haiti, Afghanistan, Chad, Sudan.

---

## 🧪 Technologies Used

- **Python**
- **Pandas**, **NumPy** for data manipulation
- **Matplotlib**, **Seaborn** for visualizations
- **Scikit-learn** for machine learning models
- **SciPy** for hierarchical clustering and statistical testing

---


