# Amazon-sales-DS-project

# Amazon Sales Data Analysis & Insights

A comprehensive data analysis project focused on understanding sales dynamics on Amazon. The goal is to explore product-level data, identify key sales drivers, and derive actionable insights using data science techniques.

---

# Project Overview

This project analyzes structured Amazon product data to evaluate pricing strategies, customer ratings, and product categories. It includes detailed data preprocessing, exploratory data analysis (EDA), and lays the foundation for future predictive modeling and dashboard development.

---

# Objectives

- Perform data cleaning and wrangling to prepare for analysis.
- Explore patterns in product categories, pricing, discounts, and user ratings.
- Derive insights on consumer behavior and pricing effectiveness.
- Visualize data-driven findings for business decision-making.

---

# Dataset Summary

- **Source:** CSV file containing Amazon product data
- **Total Rows:** ~1,200
- **Features Include:**
  - `product_name`: Name of the product
  - `discount_price`, `actual_price`, `discount_percentage`: Pricing details
  - `rating`, `rating_count`: Customer feedback
  - `about_product`, `user_review`: Textual descriptions
  - `product_category_tree`: Hierarchical category data
  - `availability`, `product_link`: Meta attributes

---

# Technologies Used

| Category         | Tools & Libraries                        |
|------------------|------------------------------------------|
| Language         | Python                                   |
| Environment      | Jupyter Notebook                         |
| Data Handling    | pandas, NumPy                            |
| Visualization    | Matplotlib, Seaborn                      |
| Future Scope     | Scikit-learn, Streamlit, NLP (spaCy)     |

---

# Exploratory Data Analysis (EDA)

# Data Preprocessing
- Inspected column types and null values
- Removed or transformed inconsistent entries
- Explored unique values in `category_tree`, `availability`, etc.

# Statistical Summary
- Descriptive statistics on numeric fields
- Analyzed central tendency and variability
- Investigated distribution of discounts and ratings

# Key Explorations
- Frequency of products by category
- Relationship between price and discount
- Rating patterns across different price segments
- Preview of most common product names and themes

---

# Sample Insights

- High discount percentages do **not always correlate** with high ratings.
- Majority of top-selling products fall under **electronics and accessories**.
- Certain product categories showed **significantly higher rating counts**, suggesting strong brand engagement.
- Data sparsity in reviews and product descriptions requires text cleaning and imputation for modeling.

---

#  Future Enhancements

- 📌 **Machine Learning Models**: Predict sales or customer ratings using regression/classification.
- 📌 **Text Analytics**: Clean and analyze `user_review` and `about_product` using NLP.
- 📌 **Dashboard**: Develop a Streamlit-powered interactive dashboard for real-time insights.
- 📌 **Web Scraping Automation**: Enhance data ingestion pipeline using Python (Selenium or Scrapy).

---

#  How to Run This Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/lalavansh/Amazon-sales-DS-project.git
   cd Amazon-sales-DS-project
