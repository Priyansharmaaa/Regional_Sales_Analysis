# 📊 Regional Sales Analysis – README

This project analyzes regional sales performance across the United States using a combination of Python, Power BI, and Excel. It uncovers insights on revenue trends, product performance, customer behavior, and geographic opportunities—helping business stakeholders make data-driven decisions.

## 📌 Overview

The Regional Sales Analysis project aims to understand how product sales, customer segments, and regions contribute to overall business performance.

**The analysis provides:**

- Revenue & profit trends

- Top-performing products and channels

- Customer spending insights

- Regional performance breakdown

- Strategic revenue & profitability opportunities

**The dashboard is divided into three analytical modules:**

- Executive Overview & Trends

- Product & Channel Performance

- Geographic & Customer Insights

## 📂 Dataset

**The dataset contains sales data across multiple dimensions:**

- Order details: order value, unit price, quantity

- Product attributes: category, product ID

- Customer data: customer name, segment, revenue contribution

- Geographic data: state, region

- Channel data: wholesale, distributor, export

**File included:**

- Regional Sales Dataset.xlsx

- Regional_Sales_Analysis.ipynb (Python cleaning & preprocessing file)

## 🛠 Tools & Technologies

**Python (Pandas, NumPy, Matplotlib, Seaborn) –** data cleaning & exploratory analysis

**Power BI –** building interactive dashboards

**Excel –** initial data exploration

**DAX –** custom measures for KPIs

## 🔧 Steps Followed
**1️⃣ Data Cleaning (Python)**

- Removed duplicates & missing values

- Standardized column names

- Converted data types

- Generated calculated fields (profit, margin, revenue per order)

**2️⃣ Exploratory Data Analysis**

- Distribution analysis of order value

- Monthly trends

- Customer segmentation

- Product pricing and margin patterns

**3️⃣ Data Modeling in Power BI**

- Built star schema

- Created DAX measures:

--> *Total Revenue*

--> *Total Profit*

--> *Profit Margin %*

--> *Revenue per Order*

--> *Channel-level & Product-level KPIs*

**4️⃣ Dashboard Development**

- Designed three linked pages

- Added filters and drill-downs

- Used custom formatting for business storytelling

## 📊 Dashboard 
**1️⃣ Executive Overview & Trends**

**2️⃣ Product & Channel Performance**

**3️⃣ Geographic & Customer Insights**

## 📈 Key Results & Insights
**📌 Revenue & Trends**

- Total Revenue: $1.2B

- Total Profit: $461.8M

- Profit Margin: 37.36%

- Seasonal peaks observed in April, June, September

**📌 Product Insights**

- Product 26 is the highest revenue generator ($117M).

- Product 9 has the highest profit margin (40%).

- Strong correlation between pricing tiers & margin clusters.

**📌 Channel Insights**

- Wholesale generates the highest revenue share (54%).

- Export and distributor channels show balanced profitability.

**📌 Geographic Insights**

- California contributes 19.5% of total revenue.

- West region has the highest profit margin (37.5%).

- Midwest and South regions show consistent performance but lower margins.

## 💡 Recommendations (Data-Driven Business Actions)
**1️⃣ Increase Supply & Promotions in High-Performing States**

- California, Illinois, and Florida show strong revenue potential.

- Expand marketing budgets & inventory allocation in these states.

**2️⃣ Prioritize High-Margin Products for Upselling**

- Promote Product 9, Product 30, and Product 28 in marketing campaigns.

- Bundle high-margin SKUs with high-volume ones to increase profitability.

**3️⃣ Strengthen Underperforming Channels**

- Distributor channel shows moderate revenue but strong margins → increase channel support.

- Create better distributor incentive programs and training.

**4️⃣ Optimize Pricing Strategy**

Margin bands reveal pricing clusters—optimize prices for

- mid-tier products with lower margins

- high-tier products facing demand drops

**5️⃣ Focus on the West Region for Future Expansion**

- Highest profit margin (37.5%) indicates strong customer willingness-to-pay.

- Introduce region-specific offers and premium products.

**6️⃣ Improve Customer Retention for Bottom 5 Accounts**

- Bottom 5 customers show shallow revenue contribution.

- Implement loyalty programs or account-based engagement.

**7️⃣ Build State-Level Sales Forecasting Models**

- Use past seasonality patterns (April, June, September peaks) to plan inventory & supply.

## ▶️ How to Run the Project
**1. Clone the Repository**
git clone https://github.com/Priyansharmaaa/Regional_Sales_Analysis.git
cd Regional-Sales-Analysis

**2. Run the Python Notebook**
jupyter notebook Regional_Sales_Analysis.ipynb

**3. Open the Power BI Dashboard**

Open Regional_Sales_Dashboard.pbix in Microsoft Power BI Desktop.

**4. Explore the Dataset**

Raw dataset is available in Regional Sales Dataset.xlsx.

## 📥 Summary

This project showcases end-to-end analytical skills—from data cleaning to business-level insights, using Python & Power BI.
It is ideal for demonstrating capability in data analytics, visualization, and decision-making.
