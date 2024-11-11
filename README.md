# Analysis and Visualization of Mysellar Global Store Sales (2019 - 2021)

## Introduction
Data-driven decision-making is a fundamental process for organizations aiming to transform raw data into actionable insights. This approach allows businesses to discern patterns, predict trends, and engage in informed decision-making. The focus of this project is to analyze a global sales dataset, providing valuable information that will assist in the optimization of sales strategies and initiatives, thereby contributing to sustainable growth and enhancing the organization’s overall performance.

## About the Dataset
Mysellar is multinational retail corporation that operates a chain of stores, online and offline, on all continents.
The dataset has sales data from January 2019 to March 2021. It consists originally of 13 columns which was further modified to 15 columns with an additional dataset for the purpose of this analysis;

- **Region:** Continents where order and sales were made
- **Country:** Countries where order and sales were made
- **Category:** Types of Products sold by the store
- **Sales Channel:** Medium of sales
- **Order Priority:** Rank of order according to priority
- **Order Date:** Date in which the order was placed
- **Order ID:** Unique identifier for each order placed by a customer
- **Ship Date:** Date in which the order was shipped
- **Units Sold:** Volume of orders
- **Unit Price**: Price of product in USD
- **Unit Cost:** Cost of product in USD
- **Total Revenue:** Total sales in USD
- **Total Cost:** Total sales in USD
- **Profit:** Profit in USD
- **GDP:** GDP of each Sub-Saharan African Countries in USD

## Objectives
- **Analyze Revenue Trends:** Examine the annual revenue and profit changes from 2019 to 2021 across regions, countries, sales channels, and product categories.
- **Examine Shipping Trends:** Evaluate the average shipping duration across regions and gather insights on logistics performance.
- **Highlight Key Metrics:** Focus on metrics such as the correlation between total revenue and GDP of Sub-Saharan African countries. 
- **Visualize Data for Better Understanding:** Utilize Excel and Power BI to present the Mysellar Global Store Sales effectively, including line charts to illustrate the monthly trend of revenue, profit, and order volume and display the monthly percentage change in revenue from 2019 - 2021.

## Tools
- Excel
- Power BI

## Technique and Skills
- Data Normalization
- Data Transformation with Powery Query
- Data Modelling
- Bookmarks
- Slicers for interactive filtering
- Report Automation
- Data Visualization

## Datasource
<a href = "https://resagratia.com/library/data-analytics-portfolio-and-capstone-project"> Resagratia </a> 

<a href = "https://en.wikipedia.org/wiki/List_of_African_countries_by_GDP_(nominal)"> Wikipedia </a>

## Data Model
The data was first normalized in Excel, then transformed in Power Query. Also, A date table was created in Power Query. Moreover, an additional GDP dataset was retrieved, normalized in Excel, transformed in Power Query and imported into Power BI. Finally relationships were created between the tables in the dataset. 

![Data Model](https://github.com/Faithe7/Demo-Mysellar-Global-Store-Sales/blob/main/images/mysellar_sales_portfolio_data_model.PNG)

## Dashboard Insights
### Global Sales Overview
Globally, the Total Revenue made between 2019 - 2021 is $1.32 billion with a Total Profit of $388.94 million and Profit Margin of 29.36%. 5 Million products were ordered and delivered within an average shipping time of 9 days.

![Overview Dashboard](https://github.com/Faithe7/Demo-Mysellar-Global-Store-Sales/blob/main/images/mysellar_sales_portfolio_main.PNG) 

- **Revenue and Profit by Region:** Sub-Saharan Africa generated the highest revenue at $321 million and profit at $90 million.
- **Profit by Sales Channel:** Offline sales achieved an impressive total of $676 million, highlighting the strength of traditional retail channels.
- **Shortest Shipping Duration:** Europe guarantees the shortest shipping time, with deliveries completed in just 8 days.

### Product Category Performance
- **Top Performing Categories:** Office supplies, household items, and cosmetics accounted for the highest sales across multiple regions in 2019. However, a significant decline was observed in 2020 and 2021, with office supplies leading the sales followed by cosmetics and baby food.
- **Units Sold (Order Volume) by Region:** Europe has the highest units sold at 1.19 million, followed closely by Sub-Saharan Africa at 1.15 million. This competitive performance highlights the growing demand in these regions. 

### Country-Level Insights
- **Top Countries by Unit Sold:** Vanuatu, Australia, Russia, Tunisia, and Myanmar are leading countries in sales, demonstrating their outstanding market performance.
- **Bottom Countries by Unit Sold:** The Gambia, Liechtenstein, Zimbabwe, the Marshall Islands, and Cape Verde account for the lowest decline in sales volumes, highlighting a significant opportunity for strategic improvements and market engagement.

### Key Metric
It is plausible to expect that countries with higher economic productivity would generate greater sales. However, this analysis shows that there is no significant correlation between total revenue generated in Sub-Saharan African Countries and their GDP. This indicates a need for deeper analysis to understand the unique factors influencing sales performance in these countries.

## Recommendations
- **Expansion of Sales Channel to Untapped Regions:** It is essential to extend sales operations to South America, as this region currently shows no sales activity in order to capitalize on potential growth opportunities.
- **Prioritize High-Performing Regions:** Sales Operations should be strengthened in Sub-Saharan Africa and Europe, as substantial revenue and profit potential is evident in those regions. This can be achieved through a reduction in shipping times, costs and sales delays to secure a competitive advantage and drive even greater success. 
- **Boost Product Offerings in Under-Performing Regions:** Identify and address factors contributing to suboptimal in Central America, Australia Oceania and North America. Customize product offerings and marketing strategies to resonate with consumer preferences in order to significantly boost market performance and accelerate sales growth in these regions. 
- **Improve Shipping Process:** Streamlining shipping times to eliminate unnecessary wait periods and sales delays will significantly boost customer satisfaction and foster lasting loyalty. 
- **Leverage Monthly Trends for Maximum Impact:** Examine monthly trends to pinpoint crucial performance indicators that are essential for improving sales processes and developing targeted marketing strategies aimed at achieving the best results.

## Conclusion
This sales analysis delivers crucial insights into the performance of the MySellar Global Store across various geographic regions. By examining key trends and metrics, it reflects the untapped potential within each market. The findings from this dashboard are not merely informative; they are pivotal in shaping strategic decisions designed to boost profitability and operational efficiency. By leveraging these insights, MySellar can seize profitable opportunities, address inefficiencies, support sustainable expansion and drive sustainable growth in the global market, ultimately ensuring long-term success and competitiveness.

## Download
<a href = "https://github.com/Faithe7/Demo-Mysellar-Global-Store-Sales/blob/main/images/Eliot_Faith_Mysellar_Global_Sales_Project.pbix"> Download the Power BI file </a>

