
# Project Files Overview

This repository contains all the files and scripts necessary for the development of machine learning models and analysis based on the provided retail data. Below is a description of each file and some important instructions for usage.

---

## Files and Descriptions:

### Notebooks:
1. **`1 - Data Pre-Processing & Exploration.ipynb`**
   - Contains data cleaning, exploratory data analysis (EDA), and preparation steps for the machine learning pipeline. This is where raw data is transformed into the cleaned dataset.
   
2. **`2 - Clustering (DBSCAN).ipynb`**
   - Implements the DBSCAN clustering algorithm to identify customer segments in the dataset.
   
3. **`2 - Clustering (K-Means).ipynb`**
   - Implements the K-Means clustering algorithm for segmenting customers based on purchasing behavior.
   
4. **`3 - Classification (Random Forest).ipynb`**
   - Contains a Random Forest classifier to predict customer behavior based on labeled features.

---

### Data Files:
1. **`cleaned_online_retail_data.csv`** *(Recommended for Use)*
   - This cleaned dataset is the result of preprocessing the original data. It is ready for use in developing machine learning models and other analyses.
   - **Important Note:** Use this dataset for all ML model development instead of the raw Excel file (`online_retail_II.xlsx`), as it has been preprocessed for optimal performance.
   
2. **`online_retail_II.xlsx`**
   - The original raw dataset in Excel format. This should only be used as a reference or for replication of preprocessing steps in `1 - Data Pre-Processing & Exploration.ipynb`.

3. **`cart_abandoners_analysis.csv`**
   - Summary analysis focusing on customers who abandoned their carts.

4. **`cart_abandoners_with_incentives.csv`**
   - Data related to cart abandoners and the impact of offering incentives to recover abandoned carts.

5. **`customer_segments.csv`**
   - Output data identifying customer segments generated from clustering models.

---

### Documentation:
- **`Final_Project_B.pdf`**
   - Contains the final report summarizing the project objectives, methodologies, results, and conclusions.

---

## Instructions:
1. **Dataset Usage:**
   - Always use the `cleaned_online_retail_data.csv` for training and evaluating machine learning models.
   - The raw dataset `online_retail_II.xlsx` is provided only for reference and preprocessing steps.

2. **Notebooks Execution Order:**
   - Start with `1 - Data Pre-Processing & Exploration.ipynb` to understand the cleaning process.
   - Follow up with the clustering and classification notebooks (`2 - Clustering`, `3 - Classification`) to implement machine learning models.

3. **Analysis Insights:**
   - Use `cart_abandoners_analysis.csv` and `customer_segments.csv` to analyze specific customer behaviors and segments.

---

Feel free to reach out with any questions or suggestions regarding the files and their usage.
