# Sales Performance Dashboard

## About

The dataset comprises U.S. sales orders including customer details, product categories (furniture, office supplies, technology), regions, and sales figures. It provides insights into customer behaviour, product performance, regional trends, and potential areas for optimisation to enhance sales and profitability.

## Purpose of the Project

this project aimed to gain insight into the dataset and create a dashboard in Excel based on the following categories.

## About Data

 Column         |  Description      
:---------------| :-----------------------------------------------------------------------------------------
Order ID	| The order identity no
Order Date	| The date on which the particular item was ordered
Customer ID	| The customer Identity no
Customer Name	| The name of the customer
Segment	        | The segment helps to analyze customer behaviour
Country	        | This tells us that the country is the US 
City	        | This indicates the city within the United States where the item is going to be delivered
State	        | State in which the particular item is going to 
Postal Code	| The state postal code
Region	        | Region is divided into four parts based on the geographical distribution 
Product ID	| The product identity no
Category	| Category in which the product belonged to
Sub-Category	| This refers to the actual category that best describes the product
Product Name	| Name of the product
Sales           | Price of that particular item

### Approach used

**Data Wrangling:** This is the first step where inspection of data is done to make sure **NULL** values and missing values are detected and data replacement methods are used to replace, missing or **NULL** values.

No null values were found in the dataset.

**Feature Engineering:** This will help us create a pivot chart based on the dataset.

1) the first pivot table created made use of the order date(year), and order date(month) which were placed under the rows and also the sales column which was placed under the values section in the field list.

A pivot line chart with markers was then selected and used to create a plot based on the dataset on the first pivot table.

2) the second pivot table was created which was based on region and also the region column was placed under the rows and the sales was placed under the values section of the field list.

A  pivot pie chart that looked like a doughnut was used to plot the data in the pivot table.

3) The third pivot table created was based on product share which refers to the category and Sub-Category. The category and sub-category were placed under the rows and the sales column was placed under the values section of the field list.

A pivot clustered column chart was then selected and used to create and analyze the pivot table.

4) the fourth pivot table was created which was based on the segment column which was placed under the rows section and the sales was placed under the values section of the field list.

A pivot pie chart was used to show the plot of the pivot table.

5 The fifth pivot table was created on the sales made by each state. It was made up of the states column which was placed under rows and the sales column which was placed under the values section of the field list.

A clustered bar chart was then created based on the data in the pivot table.


the 5 pivot chart were put together with 5 slicers or filters. the five filters are region, segment, category, sub-category, order date(year) and state. 
Various relationships were established between the slicers and the charts.
