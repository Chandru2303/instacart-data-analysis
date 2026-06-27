# Instacart Market Basket Analysis - Exploratory Data Analysis (EDA)

## Project Overview
This project explores the **Instacart Online Grocery Dataset** to uncover customer shopping behavior, order patterns, and product demand trends. The dataset consists of multiple CSV files containing order details, product information, and customer purchase history.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Objectives
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Customer Purchase Analysis
- Product Trends
- Department Analysis

## Key Insights
- Most frequently ordered products
- Peak ordering hours
- Customer reorder behavior
- Top-selling departments
- Product popularity analysis

## Skills Demonstrated
- Data Cleaning
- Data Wrangling
- Data Visualization
- Business Insights


## 📂 Dataset Information
The dataset includes the following files:
- **orders.csv** - Information about customer orders
- **order_products__prior.csv** - Products from past orders
- **order_products__train.csv** - Products from training set orders
- **products.csv** - Product details
- **aisles.csv** - Aisle details
- **departments.csv** - Department details

## 🔍 Exploratory Data Analysis (EDA)

### ✅ Data Cleaning & Preprocessing
- Checked for missing values and handled them appropriately.
- Verified data types and ensured consistency across datasets.
- Removed duplicate records where necessary.

### 📊 Key Insights & Visualizations
#### 1️⃣ Order Distribution by Hour of Day
- Most orders are placed between **8 AM and 5 PM**, peaking at **10 AM**.
- <img width="879" height="473" alt="Order Distribution by Hour of Day" src="https://github.com/user-attachments/assets/19f418ab-e181-4156-b989-299f90f34af8" />


#### 2️⃣ Order Distribution by Day of Week
- The highest number of orders occur on **Sundays and Monday**, suggesting higher weekend grocery shopping activity.
- <img width="879" height="473" alt="Order Distribution by Day of Week" src="https://github.com/user-attachments/assets/1fcb001e-2396-4037-84bd-822ea405a588" />


#### 3️⃣ Customer Order Frequency
- Many customers reorder every **8th and 30th day**, indicating bi-weekly and monthly shopping patterns.
- <img width="879" height="473" alt="Customer Order Frequency" src="https://github.com/user-attachments/assets/aa6f3cdd-cf9a-4e10-ac94-4aa2e1c417a4" />


#### 4️⃣ Most Frequently Ordered Products
- The top 10 most purchased products include **fresh produce, dairy, and staple groceries**.
- <img width="995" height="473" alt="Most Frequently Ordered Products" src="https://github.com/user-attachments/assets/b5cfe05b-0a77-47f1-a36e-412a384d9315" />


#### 5️⃣ Reorder Rate
- A high percentage of items(60%) are reordered, suggesting strong customer loyalty and repeat purchases.
- <img width="1092" height="550" alt="Most Ordered Departments" src="https://github.com/user-attachments/assets/6312cc46-1501-464a-9433-f318154096b1" />

#### Basket Size Distribution
- <img width="888" height="473" alt="Basket Size Distribution" src="https://github.com/user-attachments/assets/ddaef407-0bc7-4274-8ef7-8ab7eaded622" />

## 📓 Jupyter Notebook

Click below to view the complete analysis:

[🔗 EDA_Instacart.ipynb](EDA_Instacart.ipynb)

## 🚀 Next Steps
- Perform **customer segmentation** to identify different shopping behaviors.
- Implement **basket analysis** to find frequently bought-together items.
- Develop a **recommendation system** for personalized shopping experiences.
- Conduct **time-series analysis** to forecast demand trends.

---
### 📂 Repository Structure
```
📁 Instacart-Analysis
│── data/                 # Raw dataset files
│── EDA_Instacart.ipynb    # Jupyter Notebook with EDA
│── README.md             # Project summary and insights
```

## 📢 About the Author
This project was conducted as part of **Data Analysis** practice to enhance exploratory skills and gain insights from real-world datasets.

📌 **Want to contribute?** Feel free to fork this repository and add your insights!

