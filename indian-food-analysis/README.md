# 🍛 Indian Food Dataset Analysis

This project explores a dataset of traditional Indian dishes to uncover patterns in cooking times, dietary preferences, flavor profiles, and regional cuisine.

---

### 📊 What I Did:
- Cleaned missing and invalid data (`-1`, `NaN`, `Unknown`)
- Replaced invalid region, state, and flavor values
- Filled missing prep and cook times using median
- Engineered a new `total_time` column
- Categorized dishes by total cooking time (Quick, Moderate, Long)
- Filtered data based on diet, flavor, and time

---

### 📈 Visualizations:
- Bar plot: Dish count per course category
- Histogram: Total cooking time distribution
- Boxplot: Cook time by diet type
- Heatmap: Correlation between prep time, cook time, and total time
- Bar chart: Spicy dishes by region

---

### 🛠️ Tools Used:
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

### 📁 Dataset:
Indian Food 101 dataset from [Kaggle](https://www.kaggle.com/datasets/nehaprabhavalkar/indian-food-101)

---

### 💡 Key Insights:
- Most dishes are vegetarian and spicy
- North India contributes the highest variety of dishes
- Total cooking time varies significantly by course and region
- Spicy dishes are heavily concentrated in specific regions

### 🔍 Total Dishes Per Categories
![Dishes Count Barplot](dishes_per_cat.png)

### ⏱️ Spicy Dishes Per Region
![Spicy dishes Barplot](spicy_dishes_per_region.png)

### ⏱️ Cook Time for Veg vs Non-Veg
![Coom Time Boxplot](time_veg_vs_non_veg.png)

---

### ✅ How to Run
Open `indian_food.ipynb` in Jupyter Notebook or Colab and run all cells to explore the analysis and visual insights.

