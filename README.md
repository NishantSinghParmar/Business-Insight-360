# Business Insights 360
## Project Overview
AtliQ Hardware, a rapidly growing company, is facing the challenge of effectively leveraging its increasing volume of data to gain a competitive edge and make informed, data-driven decisions. The company has identified the need to implement a robust data analytics solution, specifically Power BI, for the first time in its operations. The goal of this project is to provide comprehensive insights across various aspects of the business including finance, sales, marketing, and supply chain. The stakeholders are seeking answers to their questions through this implementation, aiming for a holistic understanding of the business performance. The successful execution of this project is crucial for AtliQ Hardware’s continued growth and market leadership.
## Tools Used
- SQL
- PowerBi Desktop
- Excel
- DAX language
## PowerBI Skills Learnt
Here are the key learnings for Power BI:

- Asking the right questions before starting the project
- Creating calculated columns
- Creating measures using DAX language
- Data modeling
- Using Bookmarks to switch between two visuals
- Page navigation with buttons
- Using divide function to prevent zero division errors
- Creating date table using M language
- Dynamic titles based on the applied filters
- Using KPI indicators
- Conditional formatting the values in visuals using icons or background color
- Data validation techniques
- Understanding Power BI services
- Publishing reports to Power BI services
- Setting up personal gateway to set up the auto refresh of data
- Collaboration, workspace, access permissions in Power BI services
## Business related terms
- Gross price
- Pre-invoice deductions
- Post-Invoice deductions
- Net Invoice sale
- Gross Margin
- Net sales
- Net profit
- COGC - cost of goods sold
- YTD - Year to Date
- YTG - Year to Go
- Direct
- Retailer
- Distributors
- Consumer
## Problem Statement
AltiQ hardware is a company which has grown vastly in the recent years, and opened business all over the globe. It is a company which sells, computer and computer accessories through three mediums/channel

- Retailers
- Direct
- Distributors
Recently the company has faced a unforeseen loss by opening store in America based on the surveys, intuition and some excel analysis and also the company’s competitors has handful of analytics team to perform analysis and make data driven decision. So, the AltiQ hardware has no other option other than building their analytics team for data driven insights and decisions in the future to survive better in the industry.
Project kick off session, where you should get clear of for what and why this project and all other questions you have with regards to the project
## Dataset Understanding
Understanding what data is available will be more helpful while doing analysis. before jumping on to the analysis get good understanding of what are data available.

Dimension table : It will have the static data like details of customer and products

Fact table : It will have the data about the transactions

gdb041:
- dim_customer
	- 27 distinct markets (ex India, USA, spain)
	- 75 distinct customers thorough out the market
	- 2 types of platforms
	- Brick & Motors - Physical/offline store
	- E-commerce - Online Store (Amazon, flipkart)
	- Three channels( Regular, Direct, Distributors)

- dim_market
	- 27 distinct markets (ex India, USA, spain)
	- 7 sub-zones
	- 4 regions( APAC,EU,NAN,LATAM)

- dim_product
	- Divisions( P & A, PC, N&S)
	- There are 14 different categories, Like Internal HDD, keyboard
	- There are different variants available for the same product
   
- fact_forecast_monthly
	- This table is used to forecast the customer’s need in advance, which can help in,Higher customer satisfaction,Reduced cost in warehouses for storage purpose
	- The table is denormalized by data engineering team, as it is a data warehouse which is aimed to be used for analytical work.
	- All the date of the month will be replaced by the start date of the month
	- It will have all the column names and in the end it will have the forecast quantity need of the customer
  
- fact_sales_monthly
	- This table is more or less is same as fact_forecase_monthly table, but the last column has the value of sold quantity instead of forecast value.
  
- gdb056
	- freight_cost
		- This table has details of travel cost and other cost for each market with fiscal year
	- gross_price
		- Has the details of gross prices with product code
	- manufacturing_cost
		- Has the details of manufacturing cost with product code with year
  - Pre_invoice_dedutions
		- Has the details of pre invoice deductions percentage for each cutomer with year
	- Post_invoice_deductions
		- Post invoice deductions and other deductions details

## Data Model
- Data modeling plays a vital role and is considered as the basement of report.
- All the visuals will be build upon the data model.
- Poor data modeling affects the over all performance of the report.
- In this project, we have followed Snowfall data modeling method. 
![Screenshot 2023-09-24 162824](https://github.com/NishantSinghParmar/NishantSinghParmar/assets/145843778/b527758b-3008-4feb-b890-116a23aed8e6)


 
 ## Home view
 In Home view, all the views button will be available. User will land on specific view page by clicking the button
	-Info
	-Finance View
	-Sales View
	-Marketing View
	-Supply chain View
	-Executive View
	-Support

 You Can Find the Overall Report Here.
 https://www.novypro.com/profile_projects/nishantsingh-parmar
