# Zepto_python_project


## 📋 Project Overview

The goal of this project is to implement a complete data science pipeline—from data ingestion and cleaning to exploratory data analysis (EDA) and visualization.

**Key Objectives:**

* Handle missing values and duplicate records in large datasets.


* Perform data aggregation to identify top-performing products and cities.


* Analyze delivery efficiency across different geographic locations.


* Visualize sales trends and category distributions using Matplotlib and Seaborn.



---

## 📊 Dataset Description

The analysis is based on two primary datasets:

1. 
**`zepto_sales.csv`**: Contains transactional data including `order_id`, `order_date`, `city`, `delivery_status`, `delivery_time_mins`, and `total_amount`.


2. 
**`zepto_products.csv`**: Contains the product catalog with `product_id`, `product_name`, `category`, and `base_price`.



---

## 🛠️ Tech Stack

* **Language:** Python
* 
**Libraries:** * **Pandas:** Data manipulation and cleaning.


* 
**Matplotlib:** Fundamental data visualization.


* 
**Seaborn:** Advanced statistical visualizations and aesthetics.





---

## ⚙️ Workflow & Features

### 1. Data Cleaning

* 
**Missing Values:** Removed records with null values in `city` and `delivery_status`.


* 
**Imputation:** Filled missing values in `delivery_time_mins` using the column mean to maintain data integrity.


* 
**Deduplication:** Identified and removed duplicate entries.


* 
**Type Conversion:** Converted `order_date` to datetime objects for time-series analysis.



### 2. Exploratory Data Analysis (EDA)

* Calculated key metrics: Minimum, Maximum, and Average order amounts.


* Identified the **Top 5 Products** by total sales volume by merging sales and product dataframes.


* Aggregated total revenue by city and product category.


* Analyzed average delivery times per city to gauge logistics efficiency.



### 3. Data Visualization

The project includes five key visualizations to communicate findings:

* 
**Top 5 Products:** Bar chart showing the highest revenue-generating items.


* 
**City-wise Sales:** Comparison of revenue across different urban centers.


* 
**Monthly Sales Trend:** Line graph illustrating revenue fluctuations over time.


* 
**Category Distribution:** Pie chart showing the market share of different product categories.


* 
**Delivery Time Distribution:** Histogram with KDE to visualize delivery speed patterns.



---

## 🚀 How to Run

1. Clone this repository:
```bash
git clone https://github.com/yourusername/zepto-sales-analysis.git

```


2. Install the required dependencies:
```bash
pip install pandas matplotlib seaborn

```


3. Ensure `zepto_sales.csv` and `zepto_products.csv` are in the project directory.
4. Run the Python script or Jupyter Notebook:
```bash
python zepto_analysis.py

```



---

## 💡 Key Insights (Examples)

* Identified which cities are driving the bulk of the revenue.


* Discovered the most efficient cities in terms of delivery speed.


* Visualized seasonal or monthly growth patterns in sales.


## 🔗 Connect with Me
[LinkedIn Profile](www.linkedin.com/in/samyank-jain-b475b81aa)


