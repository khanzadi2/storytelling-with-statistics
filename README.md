# 🏡 Housing Prices — Storytelling with Statistics & Visualization

This project analyzes the [Housing Prices Dataset](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset/)  
using Python, Pandas, and Matplotlib/Seaborn to uncover patterns, trends, and key insights.  
It follows a **data storytelling approach** — turning numbers into a clear narrative.

---

## 📊 Dataset Overview
- **Source:** Kaggle — Housing Prices Dataset
- **Rows:** ~N (varies depending on cleaning)
- **Columns:** Price, Sqft, Bedrooms, Bathrooms, Year Built, Zipcode, etc.
- **Goal:** Explore factors affecting house prices and present insights visually.

---

## 🔍 Steps Performed
1. **Data Loading & Cleaning**
   - Removed duplicates
   - Handled missing values
   - Converted data types where needed

2. **Descriptive Statistics**
   - Mean, Median, Standard Deviation, IQR
   - Correlation analysis between price and key features

3. **Visualizations**
   - Price distribution (histogram)
   - Price vs. Sqft Living (scatter plot with regression line)
   - Median Price by Bedrooms (bar chart)
   - Top 12 Zipcodes by Median Price
   - Correlation Heatmap

---

## 📈 Key Findings
> _(Replace placeholders with your computed values from notebook)_

- **Median Price:** $`[median_price]`  
- **Mean Price:** $`[mean_price]` (distribution is [right-skewed/left-skewed])  
- **Strongest Correlation:** Sqft Living vs Price → `[corr_value]`  
- **Most Expensive Zipcode:** `[zipcode]` with median price ≈ $`[median_zip_price]`  
- **Bedrooms with Highest Median Price:** `[bedrooms]` bedrooms

---

## 🖼 Sample Visualizations

![Price Distribution](images/price_distribution.png)  
![Price vs Sqft Living](images/price_vs_sqft.png)  
![Median Price by Bedrooms](images/median_by_bedrooms.png)  
![Top Zipcodes by Price](images/top_zipcodes.png)  
![Correlation Heatmap](images/correlation_heatmap.png)  

---

## 📝 Storytelling Summary

> In this housing dataset, the median price is $`[median_price]` and the mean is $`[mean_price]`, showing a [right-skewed] distribution due to a few high-end properties.  
> House size (sqft living) has a correlation of `[corr_value]` with price, confirming larger homes tend to cost more.  
> The most expensive area is zipcode `[zipcode]` with a median price near $`[median_zip_price]`.  
> Properties with `[bedrooms]` bedrooms have the highest median price, suggesting an optimal size for premium buyers.  
> The interquartile range (IQR) of prices is $`[iqr_price]`, showing a significant gap between typical lower and upper-priced homes.

---

## 🛠 Tools Used
- **Python**
- **Pandas**
- **Matplotlib / Seaborn**
- **Scikit-learn** (for regression line)
- **Jupyter Notebook / Google Colab**

---

## 📂 Folder Structure
