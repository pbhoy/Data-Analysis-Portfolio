# Data-Analysis-Portfolio
This repository contains my data analysis portfolio projects for continuous learning.
## Project Background
Adventures Sports Inc. established in 2020, is an ecommerce sporting goods e-commerce company that sells its products worldwide through its internet sales only. The Company has significant amount of data on its sales, marketing efforts, operational efficiency, product offerings, and loyalty program that has been previously underutilized. This Project is developed to analyze its sales data and help company to improve by providing insightful recommendations.
## Business Demand Overview
-	Reporter: Sales Manager
-	Value of Change: Visual dashboards and improved Sales reporting or follow up or sales force
-	Necessary Systems: Power BI, CRM System


![User Stories](https://github.com/user-attachments/assets/ec743d79-2527-4614-bfb3-88a08ffd31a0)

## Insights and recommendations are provided on the following key areas:
- Sales Trends Analysis: Evaluation of historical sales patterns, focusing on Revenue, Order Volume, Profit, and Rate of Returns.
- Product Level Performance: An analysis of top performing product, understanding their impact on sales and seasonal trends in the market.
- Average Order Value (AOV) Trend: Evaluation of AOV over last 2 years and understanding what could affects the trends in AOV.
-	Marketing Startegy : An analysis and recommendation on marketing strategy based on historic product sales performance, Coustomer demographics and seasonal trends.
## Data Model & Initial checks
Adventure’s database structure as seen below consists of eight tables: Calander Lookup, Customer Lookup, Territory Lookup, Product Lookup, Product Subcategories Lookup and Product Category Lookup are the dimensions table. Sales Data and Return Order are the fact tables. Prior to beginning the analysis, a variety of checks were conducted for quality control and familiarization with the datasets. The SQL queries utilized to inspect and perform quality checks can be found here.
![image](https://github.com/user-attachments/assets/0b2b1893-0268-4750-8ab2-2f9632e02aec)

## Executive Summary
## Overview Of Findings
After seeing a short decline from June 2020 till November 2020 there is consistent increase in revenue YOY with seasonal trends in play. Key Performance Indicator have shown that order volume has steadily increase from August 2021 while average order value has declined YOY. This decline can be broadly attributed to introduction of small ticket items like accessories and clothing. The following sections will explore additional contributing factors and highlight key opportunity areas for improvement.
## Sales Trends
-	Seasonal Revenue Spikes: There is a consistent trend of revenue increasing from November to December, followed by a sharp decline in January, reflecting customer spending behavior during the holiday season.
- Post-Holiday Drop: Revenue declines significantly at the start of the new year, indicating a typical post-holiday slowdown in consumer spending.
-	Sustained Growth: 2021 saw strong revenue growth, which continued into 2022, with revenue figures surpassing those of previous years.
-	Holiday-Driven Consumer Behavior: The recurring spikes suggest that the holiday season is a key period for maximizing revenue, highlighting the importance of targeted marketing strategies during this time.
-	External Factor Effect: the first half of 2020 shows the consisstant revenue trends but it declined sharply in the second half which shows effect of external factors and the pverall economic downturn of the market.
## AOV Trends
-	2021 AOV Decline: Starting in August 2021, there was an unusual drop in Average Order Value (AOV), indicating a shift in purchasing behavior toward smaller order sizes.
-	Reason for the Decline: Further investigation revealed that the company introduced accessories and clothing in August 2021. Previously, the store exclusively sold bikes, as it was new to the market. The introduction of lower-priced items contributed to the observed decline in AOV.
-	2022 seems to be a recovery year,  but it has not reached the value that we saw in 2020.
## Product Performance
-	Top selling product: 30 Oz Water bottle is the top selling product till date. Bringing in $4067 in monthly revenue and $2546 profit from sale of 404 units.
-	In general, there is constant increase in sales Year over year which shows consmer customer interest.
-	Looking at the order trends, there is influence of seasonality where water bottle sales increase in summer and winter vacation.
## Recommendations
-	To improve AOV, Strategies such as cross-selling or upselling could help accelerate the recovery of AOV levels.
-	Undergrads are the topmost category of consumers so marketing campaings should be more focus on undergrads.
-	Adjust stock levels in anticipation of spikes in orders, particularly before expected high-demand periods (e.g., summer months).
-	Customer Engagement: Implement feedback loops (surveys, reviews) to understand customer preferences for different products.
