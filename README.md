# 📊 Pakistani Market Data Analysis

A data-driven exploration of product sales, pricing, inventory, and supplier performance. This project uses Python for EDA and interactive visualizations to uncover trends and actionable insights in retail product data.

---

## 🔍 Objectives

- Analyze sales patterns across products, categories, and suppliers.
- Compare pricing behavior across product grades and types.
- Evaluate inventory distribution and stock strategy.
- Identify premium vs. high-volume product segments.

---

## 📁 Dataset Overview

The dataset includes:

- **Product Name**
- **Category** (e.g., Groceries, Electronics, Dairy)
- **Sub-Category** (e.g., Grade 1/2)
- **Supplier**
- **Unit Price (PKR)**
- **Stock Available**

---

## 📈 Key Insights

### 🧊 1. Correlation Heatmap
- Most features are independent — low multicollinearity.
- Weak negative correlation between price and category/sub-category.
- Product Name & Supplier show slight correlation.

### 📦 2. Categorical Distribution
- **Groceries** are the most common category.
- **Grade 1** items dominate, suggesting demand for premium products.

### 🛍️ 3. Sales Insights
- **Top-Selling Products**: Basmati Rice, Olive Oil
- **Dominant Categories**: Groceries > Spices > Electronics
- **Top Suppliers**: Faisalabad, Multan, Lahore

### 💸 4. Pricing Analysis
- **High-Priced**: Component A/B (PKR 1100–1300)
- **Mid-Range**: Olive Oil, Green Tea
- **Low-Cost Staples**: Sugar, Flour

### 📊 5. Grade-Based Pricing
- Grade 1 consistently priced 53% higher than Grade 2.
- Component products maintain top-tier pricing in both grades.
- Staples like Sugar/Flour remain low-priced across grades.

### 🌐 6. Product Hierarchy (Sunburst View)
- **Electronics**: Largest price contributor (46%)
- **Groceries**: Key volume driver
- **Supplier Trends**:
  - Islamabad & Multan → Component A
  - Karachi & Lahore → Component B
- **Dairy & Beverages**: Limited variety (Milk Powder & Green Tea only)

### 📉 7. Stock vs. Price Scatter
- No strong relationship between price and stock.
- Stock is well-distributed across products and price levels.

### 📦 8. Stock by Category
- **Groceries** have over 2× the stock of any other category.
- **Dairy & Beverages** have low stock — likely due to perishability.

---

## ✅ Business Recommendations

1. **Double down on groceries** for volume and maintain strong inventory.
2. **Promote high-margin items** like Component A/B strategically.
3. **Leverage Grade pricing** for customer segmentation (premium vs. value shoppers).
4. **Optimize stock** for perishable items to reduce waste.
5. **Monitor supplier trends** to diversify sourcing and performance.
