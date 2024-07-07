Link to Dashboard: https://app.powerbi.com/reportEmbed?reportId=e9c3e00c2d27-4bc3-9049-909da5eb64b0
## Adventure Works Dashboard: Power BI
###
For this project, I worked for a global manufacturing company that produces cycling
equipment and accessories to track KPIs (sales, revenue, profit, returns), compare regional 
performance, analyze product-level trends, and identify high-value customers.
Used Power BI: 
- Connect and transform the raw data
- Build a relational data model
- Create calculated columns and measures with DAX
- Design an interactive dashboard to visualize the data
## The Data
###
I began by Loading my Data and transforming it in the power Query Editor then I made my data 
model by creating a star schema building relationships between the sales, Calendar, Customer, 
Product, and Territories tables. after learning about relational models, cardinality, and filter flow
![image](https://github.com/inioluwa279/Adventures-works-using-Power-BI/assets/133115794/2fb4de65-2f46-4a59-830d-69b2e8854732)
###
Some Exciting Dax Functions used:
CALCULATE (): It allows you to overrule existing report filters and “force” new filter context.
RELATED (): Returns related values in each row of a table based on relationships with other tables.
ALL (): Returns all rows in a table, or all values in a column, ignoring any filters that have been applied.
Iterator Functions: Iterator (or “X”) functions allow you to loop through the same expression on each row of a table, then apply some sort of aggregation to the results (SUM, MAX, etc.)
I Created 4 dashboards with in-depth knowledge of visualization skills. I am attaching screenshots of the dashboard to share details and findings
## Executive Dashboard: 
-	Inserted card visuals to executive-level KPIs, which show total revenue, profit orders, and return rate of products. I also added three more KPI cards to give an idea about how the company manages to achieve monthly targets compared to the previous month. I set a monthly target of 10% more than last month for revenue, orders, and returns. Here we can see that only the orders category fell short of achieving its monthly target. I tried to highlight this achievement using conditional formatting. 
- I was able to include some drill-through functionality after introducing the table with the top 10 products and the orders, revenue, and return rate linked to them. This indicates that you may examine more information about a single product by clicking on it to access a different dashboard (the Product Detail Dashboard).
-	The introduction of the filter at the top right corner allows users to filter through different years and continents. Here is the result of the dashboard showing numbers for the Year 2022 and the Europe continent.
![image](https://github.com/inioluwa279/Adventures-works-using-Power-BI/assets/133115794/46b8dc1a-2e0e-48ff-add2-8da9a9c98d41)
Map: Assigned categories to geospatial fields, added multiple location fields, and used latitude and longitude when possible.
![image](https://github.com/inioluwa279/Adventures-works-using-Power-BI/assets/133115794/dbadee30-eeea-4cb3-b2c8-f2be2c241227)
## Product Dashboard: 
This dashboard is drilled through Type, which shows more details for products shown in the top 10 tables of the executive dashboard.
![image](https://github.com/inioluwa279/Adventures-works-using-Power-BI/assets/133115794/6281e3ef-6fed-4460-996f-3599b865d1f6)
-	In the product dashboard the inclusion of gauge bars to show KPI numbers against the target for selected products.
-	Also, there is an adjusted price displayed using numeric parameters to compare weekly profit and adjusted profit.
-	Lastly, I added different product metrics using field parameters to showcase the weekly trend of selected metrics.
## Customer Details: 
This dashboard displays customer-level KPIs. I made use of the line chat to show the total number of customers by week. Added two donut charts showing total orders by income level and total orders by occupation. Implemented a visual level filter to display the three occupations with the most orders.  
![image](https://github.com/inioluwa279/Adventures-works-using-Power-BI/assets/133115794/5ba96103-2596-4e7a-b4ae-847a8edfe8ed)
