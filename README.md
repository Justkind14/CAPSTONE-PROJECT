#### CAPSTONE-PROJECT-(QUEENS SUPERMARKET SALES PERFORMANCE ANALYSIS)


Introduction:

Welcome to the Queens Supermarket Performance Analysis project! As a retail store, understanding sales trends and patterns is crucial for informed decision-making. This project aims to uncover key insights from Queen supermarket sales data, providing a comprehensive view of the business's performance.

### Project Overview
This project leverages sales data to identify trends, strengths, and areas for improvement. By analyzing key performance indicators (KPIs), we aim to empower sales teams with actionable insights and tools for sustainable growth.


### Methodology

1. Data Cleaning and Preparation:
    - Removed duplicates and standardized date formats
    - Created pivot tables for sales analysis by product, region, and period
2. Data Analysis:
    - Applied Excel functions (SUMIF, AVERAGE) for data aggregation and insights extraction
    - Utilized Structured Query Language (SQL) for querying and data manipulation
3. Data Visualization:
    - Created charts to visualize key trends and patterns (e.g., most popular product)
    - Used Microsoft Power BI for interactive and dynamic visualizations

### Tools Used:

- Microsoft Excel (data cleaning, analysis) [Download Here](https://www.microsoft.com)
- Structured Query Language (SQL) (data querying) [Download Here](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16&redirectedfrom=MSDN)
- Microsoft Power BI (data visualization) [Download Here](https://www.bing.com/search?pglt=43&q=powerbi.microsoft.com+download&cvid=0fae1f6dca6b4926aa1707cb15244dd6&gs_lcrp=EgRlZGdlKgYIAxAAGEAyBggAEEUYOTIGCAEQABhAMgYIAhAAGEAyBggDEAAYQDIGCAQQABhAMgYIBRAAGEAyBggGEAAYQDIGCAcQABhAMgYICBAAGEDSAQkxNDMzOGowajGoAgCwAgA&FORM=ANNTA1&DAF0=1&PC=U531)
- Github (portfolio building)[Download Here](https://github.com/apps/desktop)

### Key Deliverables:

1. Sales Performance Report: A comprehensive analysis of Queen's Supermarket's sales trends, strengths, and areas for improvement.
2. Data Visualization Dashboard: An interactive Power BI dashboard showcasing key sales metrics and trends.
3. Insight-Driven Recommendations: Actionable suggestions for optimizing sales strategies, improving customer engagement, and resource allocation.

   



#### Sales Overview/ Visuals

![Sales charts dashboard](https://github.com/user-attachments/assets/0241f1b8-64ca-4779-931a-190129ba2b9c)


- Total sales: 2,101,090.00
- Average sales per product: 1,255.90
- Total revenue by region:
    - North: 387,000 
    - South: 927,820 
    - East: 485,925
    - West: 300,345
 
![Uploading Region vs sales.JPG…]()

 
    - Product Sales Analysis

| Product | Sum of Total Sales |
| --- | --- |
| Shoesn | 613,380.00 |
| Shirt  | 485,600.00 |
| Hat    | 316,195.00 |
| Gloves | 296,900.00 |
| Jacket | 208,230.00 |
| Socks  | 180,785.00 |

![Product vs sales](https://github.com/user-attachments/assets/f5325c5d-e70c-464c-894f-8337cfe7f3a2)

Product Unit Price Analysis

| Product | Sum of Unit Price |
| --- | --- |
| Jacket | 62,025.00 |
| Shoes |  69,540.00 |
| Shirt |  54,520.00 |
| Hat    | 42,325.00 |
| Gloves | 34,635.00 |
| Socks  | 27,215.00 |

Regional Sales Analysis

| Region | Sum of Total Sales |
| --- | --- |
| South | 927,820.00 |
| East | 485,925.00 |
| North | 387,000.00 |
| West | 300,345.00 |

Regional Quantity Analysis

| Region | Sum of Quantity |
| --- | --- |
| South | 24,298.00 |
| East | 20,361.00 |
| North | 12,402.00 |
| West | 11,400.00 |

Monthly Sales Analysis

| Month | Sum of Total Sales |
| --- | --- |
| Feb | 546,300.00 |
| Jul | 274,800.00 |
| Jun | 247,600.00 |
| Jan | 248,000.00 |
| Mar | 107,175.00 |
| Apr | 46,865.00 |
| May | 104,280.00 |
| Aug | 204,180.00 |
| Sep | 34,720.00 |
| Oct | 133,920.00 |
| Nov | 103,950.00 |
| Dec | 49,300.00 |

Findings and Insights

1. Shoes are the top-selling product, accounting for 29.2% of total sales.
2. The South region drives nearly half of total sales.
3. February and July are the highest-selling months.
4. Socks have the lowest sales revenue.

### Recommendations

1. Increase Shoes inventory to meet demand.
2. Analyze South region's success factors and replicate in other regions.
3. Offer targeted promotions during high-selling months.
4. Improve Socks product offerings or pricing.

### Conclusion

This analysis provides valuable insights into Queens Supermarket's sales performance. By implementing the recommended strategies, the business can optimize sales, improve customer engagement, and enhance resource allocation.

### Appendix

1. Data cleaning and preparation process
2. SQL queries SELECT Orderid, 
       SUM(CAST(Quantity AS int) * CAST(Unitprice AS decimal(10, 2))) AS total_sales
FROM salesDataset
GROUP BY Orderid
ORDER BY total_sales DESC;

select * from [dbo].[SalesDataset]
                 [See Here](https://drive.google.com/file/d/1x24fM0uK3UgewyJ3F3X-D8OB_O2uAs6Z/view?usp=sharing)
3. Power BI dashboard screenshots









