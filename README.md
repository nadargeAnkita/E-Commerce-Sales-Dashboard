# E-commerce Sales Dashboard



## Problem Statement

The **E-commerce Sales Dashboard** provides a comprehensive analysis of sales performance, customer trends, and product insights. The dashboard helps businesses understand their revenue streams, identify top-selling products, analyze customer purchasing behavior, and optimize marketing strategies. 

With this dashboard, businesses can:
- Monitor key sales metrics such as total revenue, total profit, Total Quantity Sold, and Shipping cost.
- Identify which country is on lead.
- Analyze sales trends over time to understand seasonal demand.
- Gain insights into customer demographics and purchasing habits.
- Improve inventory management by identifying stock-out and overstock situations.

## Steps Followed

### Data Preparation
- Step 1: Loaded sales data (CSV file) into **Power BI Desktop**.
- Step 2: Opened **Power Query Editor** and enabled **column profiling, column distribution, and column quality** for data validation.
- Step 3: Cleaned and transformed data by handling missing values, correcting data types, and removing duplicates.

### Report Design
- Step 5: Selected a theme and customized the dashboard layout.
- Step 6: Added **KPI cards** to display:
  - Total sales 
  - Total Profit
  - Quantity Sold
  - Ship Cost
- Step 7: Created **Pie Chart, Treemap, and Bar Chart** to visualize:
  - Top 7 Sales by Country
  - Sum of Sales by Market
  - Top 5 Sales by State
  - Sum of Sales by Category
  - Sum of Sales by Ship Mode
- Step 8: Added **slicers (filters)** for:
  - Category
  - Market

- Step 9: Used **DAX expressions** to create measures for Top 7 Sales by Country, Top 5 Sales by State, Sum of Sales by Market, Sum of Sales by Category, Sum of Sales by Ship Mode.
- Step 10: Implemented drill-through and tooltips for detailed insights into specific products and customer segments.

### Deployment
- Step 12: Published the **E-commerce Sales Dashboard** to **Power BI Service**.
- Step 13: Enabled data refresh scheduling for real-time updates.
- Step 14: Shared the dashboard with stakeholders for business decision-making.

##  Key Insights

###  Regional Highlights:
- **United States** leads with **34.69%** of total sales, with strong contributions from **Australia (13.97%)** and **France (12.97%)**.
- **APAC region** accounts for **28.36%** of total revenue, followed by **the EU at 23.42%**, indicating strong revenue diversity across regions.

### Category Performance:
- **Technology** emerges as the top-performing category, generating over **$4M** in sales.
- **Furniture** and **Office Supplies** follow closely, showcasing the growing demand for tech-related products.

###  State-Level Analysis:
- **England** leads in state-level sales with **$485.17K**, followed closely by **California at $457.69K**.
- These insights highlight key areas for **targeted marketing and strategic expansion**.

###  Shipping Insights:
- **Standard Class** shipping dominates, generating **$7.58M**, significantly outperforming **Second Class shipping** at **$2.57M**.

###  Revenue & Profit Overview:
- **Total Sales**: $12.64M
- **Total Profit**: $1.47M (**11.6% profit margin**)
- **Total Quantity Sold**: 178K units
- **Total Shipping Cost**: $1.35M

##  Tech Stack
- **Data Processing**: Python 
- **Data Visualization**: Power BI 
- **Database**: MySQL
- **Dashboard Development**: Power BI 

##  Features
- **Interactive Visualizations**: Filter data by region, category, and shipping method.
- **Sales & Profit Analysis**: Identify trends and high-performing regions.
- **Shipping Cost & Class Breakdown**: Optimize logistics strategies.


## Conclusion
The **E-commerce Sales Dashboard** provides businesses with valuable insights into sales performance, customer behavior, and inventory trends. By leveraging this dashboard, decision-makers can optimize pricing strategies, improve customer engagement, and enhance overall profitability.

---

### Next Steps:
- Automate data refresh for real-time monitoring.
- Integrate external data sources for enhanced analytics.
- Implement AI-driven recommendations for personalized marketing.

---

#### **Developed by:** Ankita Nadarge
#### **Technologies Used:** Power BI, DAX, SQL, Data Visualization
#### **GitHub Repository:** [https://github.com/nadargeAnkita/E-Commerce-Sales-Dashboard.git]
