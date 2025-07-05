# Retail Nutrition EDA 🛒🥗

This project presents an end-to-end **Exploratory Data Analysis (EDA)** of a retail menu dataset comprising **260 food items** across **24 nutritional parameters**. The goal is to uncover nutritional patterns, category-level trends, and provide actionable health-oriented insights.

## 📂 Dataset Overview

- **Total Items:** 260
- **Nutritional Features:** 24 (e.g., Calories, Total Fat, Sugars, Protein, Sodium, etc.)
- **Categories Covered:**  
  - Beef & Pork  
  - Beverages  
  - Breakfast  
  - Chicken & Fish  
  - Coffee & Tea  
  - Desserts  
  - Salads  
  - Smoothies & Shakes  
  - Snacks & Sides  

> _Note: Dataset source is assumed to be proprietary or simulated; not publicly linked here._

---

## 🧪 Key Steps in the Analysis

### 1. Data Cleaning & Preprocessing
- Removed missing/null values.
- Verified data types and column formats.
- Removed invalid (-1) values.

### 2. Descriptive Statistics
- Summary stats: mean, median, mode, standard deviation.
- Univariate analysis (box plots + histograms) to detect outliers and skewness.

### 3. Multivariate & Correlation Analysis
- Correlation heatmap of numeric nutrient features.
- Grouped averages by food category for comparative analysis.

### 4. Category-wise Nutritional Profiling
- Average nutrient values computed per category.
- Nutrient trade-offs identified (e.g., high protein vs high sodium).

---

## 📊 Visualizations

- 📈 **Stacked Bar Plot**: Nutrient contribution comparison across categories.
- 🕸️ **Radar Chart**: Normalized nutrient profile of each category.
- 🔥 **Heatmaps**:
  - Raw average nutrient levels per category.
  - Normalized values for intuitive comparison.

---

## ✅ Key Insights

| Category          | High In                        | Low In                          |
|-------------------|-------------------------------|----------------------------------|
| Chicken & Fish    | Protein, Cholesterol, Sodium  | Sugars, Fiber                   |
| Smoothies & Shakes| Sugars, Carbs, Sodium         | Fiber, Protein                  |
| Salads            | Fiber, Low Calories, Low Sugar| Cholesterol, Sodium             |
| Breakfast         | Calories, Cholesterol, Fat    | Fiber, Sugars                   |
| Beverages         | Sugars, Carbs (moderate)      | Protein, Fat, Sodium            |

---

## 🎯 Actionable Recommendations

- **For Health-Conscious Customers:** Opt for **Salads** and **Coffee & Tea** – low in sugar, cholesterol, and calories.
- **For Athletes/Protein Seekers:** Choose **Chicken & Fish** and **Beef & Pork** – rich in protein but monitor sodium intake.
- **Limit I**ntake Of:** **Smoothies & Shakes** due to high sugar and sodium levels despite their “healthy” image.
- **Balanced Choices:** **Snacks & Sides** show a moderate nutritional profile across most parameters.

- 📌 Tools Used

- Python (Pandas, Matplotlib, Seaborn, NumPy)
- Jupyter Notebook

---

## 📁 Project Structure

Retail-Nutrition-EDA/
├── Retail Sales Data-EDA.ipynb # Main EDA notebook
├──  # Visualizations and plots
├── README.md # Project documentation


---

## 🙌 Acknowledgments

This project is part of a **Data Analytics internship project** aimed at strengthening EDA, storytelling, and visualization skills using real-world-style datasets.

---




