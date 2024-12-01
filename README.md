
# Project B Overview

This repository contains all the files and scripts necessary for the development of machine learning models and analysis based on the provided retail data. 

The goal of this project is to replicate a real-world scenario by studying consumer data from e-commerce platforms to create predictive models and extract valuable insights. The primary objectives include:
- Identifying trends in consumer behavior.
- Maximizing marketing initiatives.
- Guiding corporate strategies to improve client retention, boost revenue, and customize marketing efforts.

---

## Files and Descriptions:

### Notebooks:
1. **`1 - Data Pre-Processing & Exploration.ipynb`**
   - Contains data cleaning, exploratory data analysis (EDA), and preparation steps for the machine learning pipeline. This is where raw data is transformed into the cleaned dataset.
   
2. **`2 - Clustering (K-Means).ipynb`**
   - Implements the K-Means clustering algorithm for segmenting customers based on purchasing behavior. 
   
3. **`2 - Clustering (DBSCAN).ipynb`**
   - Implements the DBSCAN clustering algorithm to identify customer segments in the dataset.
   
4. **`3 - Classification (Random Forest).ipynb`**
   - Contains a Random Forest classifier to predict customer behavior based on labeled features.

---

## Instructions:
1. **Dataset Usage:**
   - Always use the `cleaned_online_retail_data.csv` for training and evaluating machine learning models.
   - The raw dataset `online_retail_II.xlsx` is provided only for reference and preprocessing.

2. **Notebooks Execution Order:**
   - Start with `1 - Data Pre-Processing & Exploration.ipynb` to understand the cleaning process.
   - Follow up with the clustering and classification notebooks (`2 - Clustering`, `3 - Classification`) to implement machine learning models.

3. **Analysis Insights:**
   - `cart_abandoners_analysis.csv` and `customer_segments.csv` are used to analyze specific customer behaviors and segments if needed in the future.
