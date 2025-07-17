# Project Background (Project in Progress)

On this project the focus is on analysis of sales transaction data from an Etsy store between 2022 to 2025. The primary objective was to provide data-driven insights to the store owner, who is facing a decline in sales and some to issues with physical products.

The Tableau dashboard can be seen [here](https://public.tableau.com/views/SueArtCoAnalysis/TotalRevenuebyCountryDB?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)(Project in Progress)

The R codes to Clean and Prepare the data can be seen [here](sql/Cleaning_and_preparing)

The R codes used to regarding the business questions can be seen [here](sql/Analytical_Queries)

# The Key Goals of this Analysis

Overall Performance Trends: To understand the general year-over-year, monthly, and quarterly revenue

Physical and Digital Product Performance: Make comparison of sales performance between physical and digital products over time, check revenue and order volume trends, average prices, and the proportion of each product type in total sales.

Product Performance Analysis: Identify top-performing and least-performing products from both physical and digital by units sold and total revenue, highlighting the items that contribute to sales or might require attention.

Customer & Geographic Insights: Understand where the customers are buying from, and identify preferences for physical or digital products.

## Data Structure and Initial Checks

Down below you can see the data structure from the SueArtCo sales with a total of 1950 records

![Data Structure](Images/Location_Structure.png) ![Data Structure2](Images/Order_Status_and_Customer_Structure.png)

![Data Structure3](Images/Orders_Structure.png)

## Executive Summary

This project undertook a comprehensive data analysis of Etsy sales records from 2022 to 2025, aimed at providing the store owner with actionable insights to address a suspected decline in performance.

## Some Key Findings

The analysis indicated that the owner's hypothesis was largely supported: the observed decline in overall sales performance was significantly driven by a disproportionate decrease in revenue and order volume from physical products over the period. While digital products showed more stability or even growth in certain periods.

Most revenue by country was concentrated in United States(8534) and United Kingdom(5832), followed by Australia(1054), Germany(605) and Canada(490). As you can see on the map visualisation below.

The analysis of individual listings revealed clear top-performers. The most sold products were predominantly Superhero Art Print set of 3, the digital Wall Art Gift, and Superhero Art Print set of 3, but the physical version of the product, indicating strong market demand or effective listing strategies for these items. 

Conversely, the store has some items with zero sales. Some are physical and others are digital, this can idicate high shipping costs and for the digital products a low demand or bad listing strategies for these specific products. we can also see some very low performance on some others products such as Road Trip Scavenger Hunt and Personalised Wish Party Stickers.

![Total Revenue by Country](Images/Total_Revenue_by_Country.png)

![Moast and Least sold products](Images/Most_and_Least_Sold_Products.png)

