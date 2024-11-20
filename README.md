# INTERACTIVE-EXCEL-BLINKIT-DATA-ANALYSIS-INDIAN-GROCERY-APP-DYNAMIC-DASHBOARD-PROJECT

About Blinkit:
Blinkit is an Indian quick-commerce service. Customers of the company use a mobile application to order groceries and essentials online. Blinkit's employees then secure the items from their warehouse and deliver the items to the consumer within 10 minutes.

Blinkit primarily delivers groceries, fresh fruits, vegetables, meat, stationery, bakery items, personal care, baby care and pet care products, snacks, flowers, etc.

Problem Statement:
To conduct a comprehensive analysis of Blinkit's Sales performance, customer satisfaction and inventory distribution to identify key insights and oppurtunities using various KPIs and Visualization.

KPI requirements:

1) Total Sales: The overall revenue generated form all the items sold. 

2) Average Sales: The average revenue per sale. 

3) Number of items: The total count of different items sold.

4) Average Rating: The average customer rating for items sold.
   
Steps Followed:
Step 1 : Review the dataset which is available as a csv file in excel and analyse the number of column heads and the number of rows for the data. The raw data is then formatted by adding a table to the data.

Step 2: The 1st step in Data Analysis after reviewing the data is - Data Cleaning. For Data Cleaning, we will start with the first column of Fat Content. We will replace the "LF" type into "Low Fat" type by using the 'Find and Replace' option.Similarly, we will replace all the "reg" type into "Regular". On successful completion of these replacements, we will have only 2 types of Fat Content options left i.e. "Regular" and "Low Fat". Note: While changing "reg" to "Regular", do select the check box "Match entire cell contents".

Step 3: The next step includes checking for blank/null values in mandatory column heads like in Date, Total Sales columns. some of the non-mandatory column heads like Item weight, or average rating can have null values.

Step 4: In order to calculate, summarize, and analyze data, that lets us see patterns, trends, we will insert a Pivot table. For this, select any cell in the data, and click on Insert Pivot Table in the Insert Tab. The Pivot table is inserted in a separate sheet and we will rename the sheet as "Sheet Design".

Step 5: In the "Sheet Design" sheet, a blank pivot table is added. In the values column of the pivot table, we will insert the following columns respectively:
a) Sales column - To represent Total Sales

b) Sales column - To represent Average Sales( In this case, change the value field settings to Average by right clicking on the the "Sum of sales")

c) Unique Identifier column - To represent the number of items sold(In this case set the Value Field setting to "Count")

d) Rating column - To represent Average Rating( In this case, change the value field settings to Average by right clicking on the the "Rating")

Step 6: Now, we'll add a blank sheet in the Excel workbook to visualize a dashboard. The gridlines will be switched OFF and a new rectangle shape will be inserted as a background for the dashboard. Format the size of the background shape in accordance to the screen resolution of one's device.

Step 7: In the dashboard, we will insert required shapes and text box to display the Visualization. The background color of the shapes will be formatted as per the color coding set for the theme.

Step 8: The 1st visulaization in the dashboard will be the 4 KPIs - Total Sales, Avg Sales, No. Of Oorders, and Avg Rating. For this we will insert a pivot table, and add the required column heads in the Values part.

The values will then be entered in the respective text box by using the following formula

  Value = ='Sheet Design'!A7
We will add the respective text boxes in the 4 KPI visuals, add a corresponding image to enhance the visualization and format the KPI chart in accordance with background theme and colors.

Note: To check whether the values are dynamic(i.e. they change if we select a specific category), insert a slicer and if they don't change then check whether all check boxes are switched ON for all pivot tables in Report Connections option. 


Step 9: Next, we will design a donut chart to analyse the Fat content of the orders delivered by segmenting them into 2 categories - Low Fat and Regular. For this also, we will first insert a pivot table, then design the required chart and formatting it correctly.

Step 10: This will be followed by visualizing a Bar chart to analyse the Sales by Outlet Location and a Bar Chart for analysing Sales by Item Type. 

Step 11: We will also use an Area Chart to study the Sales by Outlet Size, and analyse which type of Outlet size are performing better. Also, we will design a Donut chart to visualize Sales by Outlet Size followed by a Bar chart for analysing the ratings received(from 1-5) corresponding to the number of orders placed.

Step 10: Now, we will investigate the outlet type w.r.t. the KPIs - Total Sales, Avg Sales, and No. of orders by plotting column charts from the pivot tables. 

Step 11: At last, we will add 3 slicers in the dashboard, by clicking any pivot table and in the ANALYZE tab, select the Insert Slicer dropdown option. We also add two buttons to navigate to the the other two sheets in the Excel Workbook.

Insights
Following inferences can be drawn from the dashboard;

[1] Insights regarding Sales, Orders.
a) The Tier 3 outlet location type generated the maximum amount of Sales and also contributed to the highest number of orders received - ₹0.47 millions and 3350 orders respectively..

b) The Supermarket Type 1 outlets were the maximum contributors in terms of Sales as well as No. of Orders(₹787.5K and 5577 orders). 
Thus, we can analyse that Tier 3 cities are performing well in comprison to other outlet location types. The company needs to focus on low performing location to enhance sales and orders.

[2] Insights About Item Category
a) The Fruits/Vegetables and Snack Foods category were the top performing item types in terms of Sales and Orders placed. This was followed by Household, Frozen food and dairy categories. 

b) The seafood category performed the least as it generated  only ₹0.01 millions and received only 64 orders. 

[3] Insights About Rating.
a) The Average rating for the orders was approximately 4 out of a 5 rating scale.

b) The maximum number of orders(around 55%) received a rating 0f 4, followed by a 5 rating(37%). 
Thus, we can analyse that the ratings received on the orders was quite satisfactory. However, the company can still focus on improving it a bit in the future.

[4] Some other insights:
a) The Average sales per order was around ₹141

b) The fat content for most of the products sold delivered was Regular(64%) while only 36% orders were having Low Fat content.

c) Supermarket Type 1 received maximum orders among the various outlet types and corresponded to sales amount of sales(65% of total sales).

About
This repository is used to design a dashboard for Blinkit, a quick commerce service in Excel. The project involved data cleaning, transformation and using pivot tables to design interactive visualizations in Excel only. .









