# Sales-Dashboard

1. Project Title / Headline

**Sales Performance in 2023: Revenue, Customer, and Channel Analytics Dashboard**

A Power BI dashboard that tracks 2023 sales across regions, sales representatives, product categories, and payment methods, with filters for category, channel, sales rep, region, and payment.

2. Short Description / Purpose

The Sales Performance Dashboard shows how sales, quantity sold, and profit developed through 2023 and where they came from. It also compares new and returning customers month by month. It is intended for sales managers, regional leads, and business analysts who need to see which regions, reps, product categories, and payment methods drive revenue.

3. Tech Stack

The dashboard was built using the following tools and technologies:

- **Power BI Desktop:** Main data visualization platform used for report creation.
- **Power Query:** Data transformation and cleaning layer for reshaping and preparing the data.
- **DAX (Data Analysis Expressions):** Used for calculated measures such as total sales, quantity, profit, and customer counts.
- **Data Modeling:** Relationships among sales, customer, region, and product tables to enable cross-filtering and aggregation.
- **File Format:** `.pbix` for development and `.png` for dashboard previews.

4. Data Source

Sales transaction records for 2023, covering sales amount, quantity sold, profit, sales representative, region, product category, sales channel, payment method, and customer type (new or returning).

https://www.kaggle.com/datasets/vinothkannaece/sales-dataset

5. Features / Highlights

Business Problem

Sales teams need to know which months, regions, and representatives drive revenue, and whether growth comes from new or returning customers. Without a single view, these answers are spread across reports and take time to assemble.

Goal of the Dashboard

- Track total sales amount, quantity sold, and profit for 2023.
- Identify peak and slow sales months.
- Compare regional and sales rep performance.
- Understand the mix of new versus returning customers over time.
- See how revenue splits across product categories and payment methods.

Walkthrough of Key Visuals

- **KPI cards:** Total Sales Amount (5.02M), Total Quantity Sold (25K), and Total Profit (253.14K).
- **Sales Amount Trend:** Monthly area chart. January is the highest month at 0.50M, with further peaks in October and November (0.46M and 0.47M). February, May, July, and September are the lowest, at around 0.37M to 0.39M.
- **New vs Returning Customers by Month:** Dual-line chart comparing new and returning customer counts for each month.
- **Sales Amount by Region:** Bar chart showing North (1.4M) leading, followed by East (1.3M), and West and South (1.2M each).
- **Top 5 Sales Representatives:** Donut chart of the five highest-performing reps (David, Bob, Eve, Alice, and Charlie), with sales between roughly 0.86M and 1.14M.
- **Amount by Payment Method:** Donut chart showing Credit Card (1.76M, 35.02%), Bank Transfer (1.72M, 34.22%), and Cash (1.54M, 30.77%).
- **Total Sales by Product Category:** Pie chart with Clothing (1.31M, 26.17%), Furniture (1.26M, 25.11%), Electronics (1.24M, 24.77%), and Food (1.2M, 23.94%).
- **Slicers:** Category, Channel, Sales Rep, Region, and Payment, plus a Clear All button to reset filters.

Business Impact & Insights

- **Revenue is spread evenly:** Sales are split almost equally across the four product categories, so no single category carries the business.
- **Regional gap:** North leads region-wise, and the gap to South is about 0.2M. Focus on East, West, and South could lift overall sales.
- **Payment mix:** Credit card and bank transfer together account for about 69% of sales, which suggests they should stay prioritized at checkout.
- **Seasonality:** Sales start strong in January, dip in February, and build again toward the end of the year, with a strong close in October and November.
- **Rep performance:** Revenue is fairly balanced among the top five reps, so the team does not depend on one person.
- **Business value:** Supports decisions on regional targets, rep incentives, payment partnerships, and seasonal inventory planning.

Author

Praghala A S - praghalasenthilkumar@gmail.com
