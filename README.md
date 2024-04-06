# Project Title

# Madhav Store Online Sales Dashboard with PowerBI


## Problem Statement

Our client owner of “Madhav Store” wants us to create a dashboard which helps the airlines understand their customers better. It helps them to track and analyze their online sales across India. Requirements from Our client are as follows;

1)	Profit by Month
2)	Top 6 Profitable Sub-categories
3)	Top 6 Ordering States.
4)	Top 6 Online Buyers.
5)	Top 3 Order products.
6)	Modes of Payment for online orders.
7)	Option to view Annual or quarterly reports.
8)	Total orders by Quantity.
9)	Total orders by Profit.



### Steps followed 

- Step 1 : Load data into Power BI Desktop, the dataset is a CSV file.
- Step 2 : Open the power query editor & in the view tab under the Data Preview section, and check the "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, the profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except the header setting was wrong system did not pick up 1st as a header which created a heading problem in the Data set to resolve this we started the transformation data and fix this issue.
- Step 5 : For calculating profit by month we used a stack column chart.
- Step 6 : In the report view, under the view tab, the theme was selected.
- Step 7 : For calculating the “Top 6 profitable subcategories” of online products we used categories and profit variables and for visualization, we used a stacked bar chart. 
- Step 8 : For calculating “Top 6 Ordering states” we used state and Total profit variables and for visualization, we used a stacked bar chart.
- Step 9 : For calculating “Top 6 Online Buyers” we used customer name and  Sum of Amount variables and for visualization, we used a stacked column chart.
- Step 10 : Two donuts charts were also added to the report to calculate  the “Top 3 ordered category by quantity” and “Mode of Payment for online orders”.
- Step 11 : To get a bird eye view of Annually or quarterly sales reports we used Visual filters (Slicers) were added for four fields named "1st Quarter", "2nd Quarter", "3rd Quarter" & "4th Quarter” 
- Step 12 : We also added 4 cards to summarize the total quantity, total sales, total profit and AOR(Average Order Value). For AOR we need to go into data transformation and add a new table  of AOR by using Amount/Quantity.

        

 

 
 # Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload]([Screenshot.pdf])(https://github.com/Akunsait/Ecommerce-Dashboard/files/14892763/Screenshot.pdf)

# Insights

A single-page report was created on Power BI Desktop & it was then published to Power BI Service.


