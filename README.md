# Global Superstore Sales Analysis Report

## Overview
This Power BI report provides a comprehensive analysis of the sales transactions of the Global Superstore, which operates branches worldwide. The report includes visualizations segmented by country, region, and market, allowing users to explore sales performance, profit margins, shipping modes, product categories, and customer behavior interactively.

## Table of Contents
- Objectives
- Data Preparation and Cleaning
   - Data Cleaning Steps
- Key Visualizations and Insights
   - Page 1: Sales Overview
   - Page 2: Detailed Sales Analysis, Customer and Product Insights
- Interactive Features
- How to Use the Report
- Key Findings and Recommendations
  - Sales Insights
  - Product Insights
  - Customer Insights
  - Recommendations
- Video Explanation
- Technical Details
- Conclusion
- Repository Contents
- Contact Information
- Additional Resources

## Objectives
The primary objectives of this analysis are:
- Analyze Sales Data: To provide a comprehensive overview of sales performance by region, state, city, and market.
- Visualize Shipping Distribution: To analyze the percentage distribution of shipping methods based on ship modes.
- Identify Key Drivers: To identify top-performing products, categories, and customers.
- Create Interactivity: To build an interactive, user-friendly report that allows stakeholders to explore data dynamically.

## Data Preparation and Cleaning
Before creating the visualizations, the dataset underwent thorough data cleaning to ensure accuracy and reliability:
### Data Cleaning Steps:
1. Duplicate Removal:
Identified and removed duplicate records to ensure data integrity.
2. Handling Missing Values:
Missing values in critical columns (like sales and profit) were filled with mean values or omitted if necessary.
3. Data Type Corrections:
Corrected data types for all columns (e.g., dates, numerical values) to ensure accurate analysis.
4. Outlier Detection:
Identified and treated outliers in the dataset to prevent skewed results in the analysis.
5. Data Filtering:
Filtered irrelevant data, such as records outside the analysis scope, to focus on meaningful insights.

## Key Visualizations and Insights
The report comprises several key visualizations, each providing valuable insights:
- *Page 1: Sales Overview*
1. **Sales and Profit by Segment:**
This bar chart provides a breakdown of sales and profit across different customer segments, such as Consumer, Corporate, and Home Office. It’s easy to see which segment is contributing the most to our sales and profit.
2. **Sales and Profit by Category:** 
A clustered bar chart comparing total sales and profits across product categories like Technology, Office Supplies, and Furniture. This helps identify which categories drive the most profit. 
3. **Sales Over Time by Market:** 
A line chart showing sales trends over time (from 2011 to 2014) across various markets (e.g., US, EMEA, APAC). Consistent growth is noted in the US and EMEA markets.
4. **Sales by State:** 
A bar chart that breaks down sales by state, highlighting the top-performing states such as England and California.
5. **Sales Distribution by Ship Mode:** 
A pie chart illustrating the percentage of sales by different ship modes. The 'Standard Class' dominates with around 60% of sales, indicating a preference for economical shipping options.
6. **Total Sales by Region:** 
A map visual displaying sales distribution across global regions. Key insights indicate that North America and EMEA regions contribute the highest sales, while regions like Oceania and Southeast Asia show lower sales.

![Report Preview](https://github.com/user-attachments/assets/39e107d7-a04c-4e5d-9318-3b9a7412449b)

- *Page 2: Sales Distribution Analysis*
1. **Return Rate by Category:** 
A bar chart visualizing the return rate for each product category. This is useful for identifying categories with higher return rates and investigating potential quality issues.
2. **Average Order Value per City (Top 10):**
A stacked bar chart highlighting the top 10 cities with the highest average order value, indicating high-value customer locations.
3. **Count of Customer ID by Region:**
The pie chart  represents the percentage distribution of customers across various regions. This breakdown is essential for understanding market penetration and customer distribution geographically.
4. **Total Profit by Product Name (Top 5 and Bottom 5):**
Two bar charts displaying the most profitable products and the least profitable ones. This helps in inventory and product line management.
5. **Top 10 Customers:**
A bar chart visual listing the top 10 customers by sales volume, providing insights into customer behavior and loyalty.

![Report Preview(1)](https://github.com/user-attachments/assets/39f6518f-035d-4bf3-aec3-dfc8c0f0a58b)


## Interactive Features
To enhance usability, the report includes several interactive elements:
- Slicers and Filters:
Slicers are provided for Country, Region, Market, and Date, allowing stakeholders to dynamically segment the data for detailed analysis.
- Page Navigation Buttons:
Interactive buttons enable easy navigation between report pages.
- Drill-Through and Drill-Down:
Drill-through options allow users to dive deeper into specific data points, while drill-down functionality is available in hierarchy-based visuals.

## How to Use the Report
Follow these steps to explore the report effectively:
1. Open the Report:
Launch the report in Power BI Desktop or Power BI Service.
2. Use Slicers and Filters:
Utilize slicers on each page to filter data by specific regions, countries, or time periods.
3. Navigate Between Pages:
Click on the navigation buttons to move between different pages of the report.
4. Interact with Visuals:
Click on data points within the visuals to drill down or cross-filter other visuals, revealing deeper insights.
5. Clear Filters:
Use the "Clear all slicers" button to reset all filters and return to the default view.

## Key Findings and Recommendations
### Sales Insights:
- High-Performing Regions: North America and EMEA regions are the top contributors to total sales.
- Preferred Shipping Mode: The majority of shipments are via the 'Standard Class,' suggesting cost efficiency as a priority for customers.
### Product Insights:
- Top Categories: Technology and Office Supplies are the most profitable categories.
- Product Return Concerns: Certain categories, like Furniture, have a higher return rate, which may require quality checks.
### Customer Insights:
- Key Customers: The top 10 customers contribute significantly to sales, indicating potential for targeted loyalty programs.
### Recommendations:
- Optimize Inventory: Focus on high-performing product categories and reduce inventory of low-performing items.
- Improve Shipping Efficiency: Investigate opportunities to promote alternative shipping options for better cost management.
- Address Return Rates: Analyze the reasons behind higher return rates for specific categories and implement quality control measures.

## Video Explanation
A comprehensive video walkthrough is available to guide stakeholders through the report. The video covers:
* An introduction to the report's objectives and structure.
* Step-by-step guidance on using interactive features.
* Key insights from each visualization.
* A summary of findings and recommendations.

## Technical Details
* Software Used: Power BI Desktop
* Data Source: Global Superstore Dataset
* Data File Format: Excel
* Report File Format: .pbix (Power BI)

## Conclusion
The Global Superstore Sales Analysis Report provides a comprehensive and interactive overview of the company's sales performance across various dimensions, including regions, markets, and product categories. By leveraging Power BI's advanced visualization and interactivity features, the report enables stakeholders to easily explore and understand key trends, patterns, and insights hidden within the sales data. 
This report serves as a valuable tool for strategic decision-making, providing stakeholders with the ability to interact with and analyze data effectively. Moving forward, the insights from this report can guide the development of targeted business strategies to capitalize on the store’s strengths and address areas for improvement. This report provides valuable insights into the Global Superstore's sales performance to support strategic decision-making.

## Repository Contents
1. **Readme.md:** This file contains a detailed overview of the project, including objectives, data preparation, key findings, instructions for using the report, and conclusions.
2. **Global Superstore Report.pbix:** The Power BI report file that includes all visualizations, slicers, and insights based on the Global Superstore dataset.
3. **Global Superstore.pdf:** The power BI report file in pdf format.
4. **Report Preview.png:** A screenshot or image that provides a preview of the Power BI report. This helps viewers quickly understand the contents and layout of the report.
5. **Global Superstore Sales Analysis.mp4:** A video file explaining the key visualizations, insights, and interactivity in the Power BI report. This video is part of the assignment requirements for presenting the report to stakeholders.


## Contact Information
For further information or questions, please contact:
Email: deepthydevadasan@gmail.com

## Additional Resources
https://drive.google.com/file/d/1QMlY5rCDVTRUPyqa1Y_1_rLrWzZYBRc1/view?usp=drive_link – Video explaining the report and its features.
