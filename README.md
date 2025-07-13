# 🛒 Supermarket Sales Analysis

A data-driven comparison of sales performance across three branches of a supermarket using Python and visualization tools.

---

### 🧠 Summary

This project analyzes a supermarket sales dataset to uncover patterns and performance differences across three different store branches. The goal was to determine which branch performed best, understand customer behaviors, and identify top-selling product lines.

---

### 📁 Dataset

- **Source:** [Supermarket Sales Dataset – Kaggle](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales) 
- **Shape:** 1,000 rows × 17 columns
- **Features:** Date, Time, Branch, Product line, Customer Type, Gender, Total, Rating, etc.

---

### 🎯 Objectives

- 📊 Compare total sales among Branches A, B, and C
- 🧍‍♂️ Analyze customer types (Member vs. Normal)
- 🍔 Identify the top-selling product line
- 🌟 Understand the distribution of customer ratings

---

### 🛠️ Tools & Technologies Used

- Python 3.x
- Google Colab (Jupyter Notebook)
- Libraries: `pandas`, `matplotlib`

---

### 📈 Key Insights

- **Top Branch:** Branch C achieved the highest total sales.
- **Customer Behavior:** Members spent slightly more on an average than Normal customers.
- **Top Product Line:** Food and beverages led in total revenue.
- **Ratings:** Customer satisfaction was varied, with a peak around 7–8 on the rating scale.

---

### 📊 Visual Examples

![Branch-wise Sales](images/branch_sales.png)
*Branch C outperforms the others in total sales.*

![Customer Type vs Purchase](images/customer_type_comparison.png)
*Members tend to spend slightly more than Normal customers.*

---

### 🧪 Results & Conclusion

The supermarket’s Branch C is its strongest performer and could be considered for expansion or investment. The product line insights help target high-performing inventory. Member programs show slight benefit in average purchase - worth exploring further.

---

### 📚 Learnings

- Real-world data cleaning & visualization
- Comparative performance analysis
- Enhanced Python + Pandas + Matplotlib skills
- Storytelling through data

---

### ▶️ How to Run

```bash
# Clone this repository
git clone https://github.com/Deep-15-hmm/supermarket-sales-analysis.git

# Open notebook in Google Colab
# OR run locally after installing requirements

pip install -r requirements.txt
jupyter notebook notebooks/supermarket_sales_analysis.ipynb
