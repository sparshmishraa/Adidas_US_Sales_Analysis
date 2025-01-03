# ADIDAS US SALES ANALYSIS

## PROJECT DETAILS: 
   This dataset represents a comprehensive collection of information on the sales of Adidas products, providing a detailed view into various aspects of sales performance. 
                    The data includes metrics such as:
                    1. Number of Units Sold: Details on the quantity of Adidas products sold across different regions, time periods, and sales channels.
                    2. Total Sales Revenue: Insights into the monetary value generated from the sales of products, offering a clear picture of revenue distribution.
                    3. Sales Locations: Geographical details on where products are sold, including regional and state-wise breakdowns.
                    4. Types of Products Sold: Categorization of products by type, including footwear, apparel, and accessories, providing a segmented view of sales.
                    5. Customer Demographics: Classification of sales data based on customer gender and product type to identify trends and preferences.
                    6. Sales Channels: Information on the distribution of sales across online platforms, physical retail stores, and outlet channels.

This dataset serves as the foundation for a detailed analysis aimed at uncovering trends and patterns in sales performance.

## BUSINESS TASK:
   The primary business objective is to identify significant trends in sales volume and specific purchase patterns. The findings from this analysis will assist in:
                    1. Designing targeted sales strategies to maximize revenue.
                    2. Making informed decisions regarding inventory management, marketing focus, and regional sales efforts.
                    3. Enhancing overall business efficiency by identifying key drivers of sales and areas for improvement.

## TOOLS USED:
   The analysis and visualization of this dataset were conducted using the following tools:
                    1. Google Sheets: Used for initial data cleaning and preparation, ensuring the dataset is error-free and ready for further analysis.
                    2. Tableau: Utilized for advanced data analysis and the creation of interactive visualizations, providing a clear and accessible presentation of insights.

## DATA CLEANING & PREPARATION
   ### Cleaning the Dataset-
       To ensure the dataset's reliability and usability, the following cleaning steps were performed:
                   1. Duplicate Check: The dataset was examined for duplicate entries, and no such values were found.
                   2. Blank Values: A thorough review confirmed that there were no blank or missing values.
                   3. Formatting: The dataset was formatted appropriately to ensure consistency and compatibility with analysis tools.
       
      Based on this review, the dataset was deemed clean and ready for analysis.

   ### Preparing Data for Analysis-
       To enable in-depth analysis and uncover meaningful insights, the following preparation steps were undertaken:
                    1. Creation of Month and Year Columns: Extracted the month and year from the "Invoice Date" column using the “TEXT”  function in Google Sheets. 
                       This allowed for time-based analysis of sales trends.
                    2. Classification of Products: 
                      -- Introduced a "Gender" column to categorize products as men’s, women’s, or unisex.
                      -- Created a "Product Type" column to further classify items into categories such as footwear, apparel, or accessories.
                    3. Validation of Data: Verified that all transformations and classifications aligned with the original dataset to maintain data integrity.

        These steps ensured that the data was fully prepared for a detailed analysis of sales trends and patterns.

## INSIGHTS
             1. Top Sales by State: New York leads with the highest sales share at 7.14% ($64.2M), followed closely by Florida at 6.59% ($59.3M).

             2. Sales Contribution by Method: 'In-store' sales dominate with 39.63% of total sales, while 'outlet' sales contribute 32.85%, and 'online' sales make up 27.52%.

             3. Monthly Sales Trends: In 2020, April had the highest sales at $24.6M, with December at the lowest, $8M. In 2021, July recorded the highest sales of $78.3M, followed by December at $77.8M.

             4. Yearly Sales Comparison (2020 vs. 2021): Sales in 2021 far outperformed 2020, with even the lowest month in 2021 surpassing the highest month in 2020.

             5. Regional Sales Breakdown: The West region leads with 30% of total sales, followed by the Northeast at 20.7%, combining for 50% of all sales. The Midwest has the smallest share at 15.09%.

             6. Profit by Product Category: Men's Athletic Footwear drives the highest operating profit at 24.9%, followed by Women's Apparel at 20.7%. Women's Athletic Footwear has the lowest profit share at 11.7%, just behind Men's Apparel at 13.48%.
            
             7. Price vs. Units Sold: A scatter plot reveals a positive correlation between price and units sold—higher demand drives higher prices.
             
             8. Top Retailer Sales: West Gear leads all retailers with $242.9M in sales and 625,262 units sold. Foot Locker follows at $220.1M and 604,369 units, while Walmart ranks lowest with $74.6M in sales.

Tableau Dashboard Link: https://public.tableau.com/views/AdidasUSSalesAnalysis_17149002578580/SalesDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
