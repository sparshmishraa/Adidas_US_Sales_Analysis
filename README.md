# PROJECT DETAILS:

This dataset is a collection of data that includes information on sales of Adidas products.

Include details such as:

1. No. of units sold

2. Total Sales Revenue

3. Location of Sales

4. Type of pdt sold

5. Other relevant information.

Business Task- Business task is to find trends in sales volume and/or specific purchases.

These insights will be used to design appropriate sales strategy and helps in decision making.

# TOOLS USED:

1. Google Sheets for Data Cleaning and Preparation,
  
2. Tableau for Data analysis and visualization.

# DATA SOURCE: 

  https://www.kaggle.com/datasets/heemalichaudhari/adidas-sales-dataset

# DATA CLEANING & PREPARATION

## CLEANING THE DATASET:

1. Check for duplicates- No such values found

2. Blank Values- No Blank values

3. Formatting- Proper formatting

Hence, the data is clean.

### PREPARING DATA FOR ANALYSIS:

1. I want to analyze the sales month and year wise for that I will create a month column and year column and extract month and year from Invoice data column using =Text function.

2. Also it will be better if we further classify products on the basis of gender and the type of product- for that i will create a product and gender column and extract the relevant data from the product column.


# INSIGHTS

1. **Top Sales by State**: New York leads with the highest sales share at 7.14% ($64.2M), followed closely by Florida at 6.59% ($59.3M).
  

2. **Sales Contribution by Method**: 'In-store' sales dominate with 39.63% of total sales, while 'outlet' sales contribute 32.85%, and 'online' sales make up 27.52%.


3. **Monthly Sales Trends**: In 2020, April had the highest sales at $24.6M, with December at the lowest, $8M. In 2021, July recorded the highest sales of $78.3M, followed by December at $77.8M.


4. **Yearly Sales Comparison (2020 vs. 2021)**: Sales in 2021 far outperformed 2020, with even the lowest month in 2021 surpassing the highest month in 2020.


5. **Regional Sales Breakdown**: The West region leads with 30% of total sales, followed by the Northeast at 20.7%, combining for 50% of all sales. The Midwest has the smallest share at 15.09%.


6. **Profit by Product Category**: Men's Athletic Footwear drives the highest operating profit at 24.9%, followed by Women's Apparel at 20.7%. Women's Athletic Footwear has the lowest profit share at 11.7%, just behind Men's Apparel at 13.48%.


7. **Price vs. Units Sold**: A scatter plot reveals a positive correlation between price and units sold—higher demand drives higher prices.


8. **Top Retailer Sales**: West Gear leads all retailers with $242.9M in sales and 625,262 units sold. Foot Locker follows at $220.1M and 604,369 units, while Walmart ranks lowest with $74.6M in sales.

<div class='tableauPlaceholder' id='viz1730794967145' style='position: relative'><noscript><a href='#'><img alt='Adidas US Sales Analysis ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ad&#47;AdidasUSSalesAnalysis_17149002578580&#47;SalesDashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='AdidasUSSalesAnalysis_17149002578580&#47;SalesDashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ad&#47;AdidasUSSalesAnalysis_17149002578580&#47;SalesDashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1730794967145');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1500px';vizElement.style.height='1427px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1500px';vizElement.style.height='1427px';} else { vizElement.style.width='100%';vizElement.style.height='2477px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

