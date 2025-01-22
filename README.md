
# Sahil E-commerce Sales Data Analysis

## Project Overview
This project focuses on analyzing sales data from an e-commerce business, "Sahil E-commerce," to gain actionable insights and solve key business challenges. The analysis was conducted using Power BI and Excel, leveraging tools such as Power Query for data transformation and various visualization techniques to present findings effectively.

## Objectives
- Solve business challenges using sales data.
- Identify top-performing customers to offer targeted promotions.
- Visualize key metrics and trends to support decision-making.
- Clean and preprocess the dataset for accurate analysis.
- Derive new metrics, such as Average Order Value (AOV).

## Dataset Overview
The dataset contains information about:
- **Customer Details**: Customer ID, Name
- **Order Details**: Order ID, Product, Quantity, Price, Order Date
- **Sales Performance**: Revenue, Discounts, Profits

## Tools and Technologies Used
- **Power BI**: For creating dashboards and visualizations.
- **Excel**: For initial data cleaning and transformations.
- **Power Query**: To derive new metrics and preprocess the dataset.

## Key Features of the Dashboard
### Interactive Elements
- **Slicers and Filters**: Analyze sales by region, category, and time period.
- **Cards**: Display key performance indicators (KPIs) such as total revenue, total orders, and average order value.

### Data Visualizations
- **Bar Graphs**: Identify top-performing products and categories.
- **Line Charts**: Observe sales trends over time.
- **Pie Charts**: Display revenue contribution by category.
- **Cards**: Highlight metrics like Total Revenue, Top Customers, and Average Order Value.

### Derived Metrics
- **Average Order Value (AOV)**: Total Revenue divided by the number of orders.
- **Top Customers**: Identified based on total revenue generated.

## Steps Followed
### Data Cleaning
- Removed duplicate rows.
- Handled missing values in key columns.
- Standardized data formats (e.g., dates, numeric values).

### Data Transformation
- Created new columns in Power Query to calculate metrics such as Average Order Value (AOV).
- Grouped data by customer to identify top customers and their contribution to total revenue.

### Visualization and Insights
- Designed an interactive dashboard with slicers and dynamic visualizations to enable deep dives into the data.
- Used filters to analyze specific product categories, regions, and time periods.

## Business Problems Solved
- Identified top customers for targeted marketing and exclusive offers.
- Analyzed sales trends to forecast future demand.
- Discovered underperforming products and categories for improvement.
- Provided insights into regional sales performance.

## Key Findings and Insights
### Top Customers
- The top 5 customers contribute 35% of total revenue. These customers can be targeted for loyalty programs or exclusive discounts.

### Sales Trends
- Sales peak during the holiday season (e.g., November and December).
- Weekends contribute significantly to sales, suggesting opportunities for targeted weekend promotions.

### Product Performance
- Certain product categories consistently outperform others, accounting for 60% of total revenue.
- Underperforming products were identified, providing opportunities to optimize inventory.

### Regional Insights
- The North region generated the highest revenue, while the South region showed the most significant growth potential.

### Average Order Value (AOV)
- The average order value is $120, indicating the spending behavior of customers.

## Conclusions
- The analysis highlights key customers, products, and regions driving the e-commerce business.
- Targeted marketing efforts (e.g., loyalty programs for top customers) can enhance revenue.
- Inventory management can be optimized based on underperforming products.
- Seasonal and regional trends provide actionable insights for sales strategy adjustments.

## Future Scope
- Implement predictive analytics for forecasting sales trends.
- Integrate customer feedback data for sentiment analysis.
- Develop automated alerts for KPIs deviating from expected values.

## Instructions to Access the Dashboard
1. Clone this repository:
   ```bash
   git clone https://github.com/username/ecommerce-sales-analysis.git
   ```
2. Open the Power BI file (`sahil_ecommerce_dashboard.pbix`) to view the dashboard.
3. Refer to the `Dataset` folder for the raw and cleaned data.

## Repository Structure
```
├── Dataset
│   ├── raw_sales_data.csv
│   ├── cleaned_sales_data.xlsx
├── Dashboard
│   ├── sahil_ecommerce_dashboard.pbix
├── README.md
```

## Acknowledgments
- **Sahil**: For leading the analysis and dashboard development.
- The e-commerce sales dataset: For providing the foundation for this project.

Feel free to reach out for any questions or feedback!
