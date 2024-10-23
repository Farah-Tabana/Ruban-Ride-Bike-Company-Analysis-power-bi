
# Urban Bike Company Data Visualisation



## Problem Statement

The company needs a deeper understanding of customer behavior and order patterns to make informed decisions about product offerings, customer engagement, and areas of improvement. This dashboard provides insights into customer demographics, order trends, and product popularity, allowing the company to identify top-performing products, customer segments, and potential areas for growth. By analyzing these insights, the company can address key challenges, such as declining order frequency or high product return rates, and implement strategies to improve customer satisfaction, boost revenue, and tailor offerings to customer preferences. 


### Steps followed 


#### 1. Define Objectives and Scope
- Step 1 : Clarify the Purpose: Understand what the dashboard should achieve (e.g., customer insights, product performance, order trends).
- Step 2 : Set Key Questions: Identify the business questions the analysis should answer (e.g., "Which customer segments drive the most revenue?" or "Which products are frequently returned?").
- Step 3 : Define Metrics: Determine (KPIs) and metrics (e.g., revenue, order volume, return rates, customer demographics).

#### 2. Collect and Prepare Data
- Step 1 : Identify Data Sources: Gather data from relevant sources, such as sales databases, CRM systems, or e-commerce platforms.
- Step 2 : Data Cleaning and Transformation: 
  - Clean up the data to remove duplicates or inconsistencies.
  - Normalize the data (e.g., date formats, customer names).
  - Transform the data into a structure suitable for analysis (e.g., create relationships between tables).
#### 3. Build the Data Model
- Step 1 : Create a Data Model: Design a data model in Power BI that includes relationships between tables.
- Step 2 : Add a Calendar Table: Create a calendar table to support time-based analysis (e.g., monthly trends).
- Step 3 : Set up Relationships: Connect tables (e.g., Sales Data table  to customers and products ,... , etc).

Relationships between tables ,

![Relationships](https://github.com/user-attachments/assets/a8da1a72-313e-4d19-91cd-595ee505e0b1)

- Step 4 : Create Measures Table: Use DAX to create calculated fields, such as total revenue, All Orders, or All returns.

![Measure Table](https://github.com/user-attachments/assets/44ae71fd-e234-4e3c-a39d-146da48fd6c2)

#### 4. Create Visualizations
Choose Visuals Based on Insights: Pick charts and visuals that best communicate the data:
- Add KPIs and Cards: Use KPIs and card visuals to display key metrics (e.g., total revenue, orders, return rate and profit).
![KPI's cards](https://github.com/user-attachments/assets/d2b96e40-2f26-490c-b396-0ad1a5624cef)
- Line charts for trends (e.g., revenue over time).
![Revenue trending](https://github.com/user-attachments/assets/4adbf77c-9130-45aa-ad49-6c4eac8da5e8)
- Bar charts or pie charts for comparing categories (e.g., customer income levels, product categories).
- Tables for detailed breakdowns (e.g., top 100 customers and top 10 products).
- Use Filters and Slicers: Allow users to drill down into specific data, such as by year, product category, or customer segment.

#### 5. Incorporate Advanced Features
- Conditional Formatting: Highlight important insights with color-coded visual indicators (e.g., red for high return rates).
![monthly returns](https://github.com/user-attachments/assets/193a6241-bb35-452c-b692-3dfac7adf2e6)

- Custom Tooltips: Provide more information when hovering over a visual (e.g., weekly orders with total revenue , profit and orders).
![tooltip](https://github.com/user-attachments/assets/3d10de02-85b1-4be4-a6c9-acb2fdb7a97c)
- Bookmarks and Navigation: Add bookmarks to create different views for users and make navigation between report pages intuitive.

#### 7. Create a Story with the Dashboard
- Organize Visuals Logically: Arrange visuals to tell a clear story. Start with high-level insights (e.g., total revenue), then drill down into more detailed metrics (e.g., product performance, Revenue trending).


# Snapshot of Dashboard (Power BI Service)

![dashboard](https://github.com/user-attachments/assets/9942827b-0325-4212-b2b7-fa5be8119fab)

 
 # Snapshot of map (Power BI Service)
 ![map2](https://github.com/user-attachments/assets/00592889-1594-49df-bf73-911137add340)

# Snapshot of Product Detail (Power BI Service)
![Product details](https://github.com/user-attachments/assets/47664a19-11cf-479a-9235-60d501e98748)


# Snapshot of Customer Detail (Power BI Service)
![customer details](https://github.com/user-attachments/assets/ca72861d-11e5-474f-93ce-d8b8ec642cc5)

# Insights


### Dashboard Insights:
1. Revenue & Profit Growth:
   - Total revenue is $24.9M, with a profit of $10.5M, and a steady upward trend in revenue since early 2020.
   - The profit margin is healthy, and the trendline indicates consistent revenue growth with minimal fluctuations.
   
2. Orders & Return Rate:
   - There are 25.2K total orders, with a low return rate of 2.2%. This suggests customer satisfaction or minimal product issues, which is a positive indicator for product quality.
   
3. Orders by Category:
   - The largest category by order volume is **Accessories (17K orders)**, followed by **Bikes (13.9K orders)** and **Clothing (7K orders)**. 
   
4. Top Products & Returns:
   - The top-selling product is a **Water Bottle** with nearly 4,000 units sold, followed by **Tire Tube** and **Hilmat**.
   - Most returned products are **Shorts **, which could indicate issues with sizing or quality in this product category, and it requiring attention.
   - The highest return rate product is **Sport-100 Helmet,Red **.

### Customer Detail Insights:
1. Customer Overview:
   - There are **17.4K unique customers**, each generating an average revenue of $1,431, indicating a strong customer base with relatively high spending power.
   
2. Income-Level Insights:
   - Most orders come from customers in the **average-income group** (11.6K orders), followed by **low-income group** (10.3K orders), indicating that products are accessible to a wider range of customer segments.
   
3. **Customer Occupation:**
   - Orders from **professional customers (7.9K)** are higher, followed by **skilled manual workers (6K)**. Understanding these customer segments can help target marketing and promotions.
   
4. **Top Customer Insights:**
   - The top customer by revenue is **Mr. Maurice Shan**, with 6 orders totaling $12.4K. Focusing on retaining such high-value customers could boost future revenue.

### **Product Detail Insights:**
1. **Profit vs. Target:**
   - The **Road Tire Tube** product's current monthly profit is slightly below target at $1,044 compared to $1,129. Although below target, profit is still healthy.
   
2. **Price Adjustments:**
   - The slider suggests a feature where small price adjustments (0.10% in this case) could be tested for impact on profitability and demand.

3. **Product Metric Selection:**
   - The data provides an overview of key metrics such as orders, revenue, profit, and returns. This insight can be useful for dynamic filtering of different KPIs based on product performance.

These dashboards collectively allow for strategic decision-making on product offerings, customer retention, and marketing campaigns.

### Map Insights:
1. **United States** has the largest bubble, indicating that the region with the highest sales.
2. **Canada**, and the **UK** show moderate activity,  they are key markets but not as dominant as the US.
3. **France** and **Germany** have smaller bubbles but are still important, likely contributing significantly to sales or customer bases in Europe.
