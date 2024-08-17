# Ecommerce-Analytics-Dashboard

This repository contains an advanced analytics project focused on the analysis of ecommerce sales data and promotional activities. The primary objective is to derive actionable insights that can enhance decision-making processes in ecommerce management.

## Project Overview

This project involves analyzing customer interactions, product performance, and the effectiveness of promotions. The insights are visualized through a comprehensive dashboard, which highlights key metrics to help businesses optimize their strategies.

## Key Metrics and Insights

- **Sales Trends Analysis:** Identify trends in sales over time, segmented by product categories, brands, and states.
- **User Engagement:** Track customer interactions across different channels (App/Browser) and event types (views, cart additions, purchases).
- **Promotion Impact:** Evaluate the effectiveness of various promotions by analyzing the discount rates and their influence on sales volume.
- **Customer Segmentation:** Segment customers based on their behavior (e.g., high-value customers, frequent shoppers) using the User_Score metric.
- **Product Performance:** Assess the performance of products within specific categories and sub-categories, helping to identify best-sellers and underperformers.
- **Revenue by Promotion:** Visualize the revenue generated during promotional periods compared to non-promotional periods.

## Tools and Technologies

- **Power BI:** For data visualization and dashboard creation.
- **DAX:** For creating calculated columns and measures.
- **SQL:** For querying and analyzing large datasets.
- **Excel:** For initial data cleaning and formatting.

## Dataset Description

### Sales Data

- **user_id:** Unique ID of the customer
- **event_date:** Date of the event
- **Day_of_Week:** Day of the week when the event occurred
- **Channel:** Channel used (App/Browser)
- **event_time:** Time of the event
- **event_hour:** Hour of the event
- **event_timezone:** Time zone of the event
- **event_type:** Type of event (view, cart, purchase)
- **product_id:** Unique ID of the product
- **category_id:** Unique ID of the category
- **category:** Category description
- **sub_category1:** Level 1 sub-category description
- **sub_category2:** Level 2 sub-category description
- **brand:** Brand name
- **price:** Price of the product
- **user_session:** Unique ID of the user session
- **State:** State where the event occurred
- **User_Score:** Segmentation of the customer

### Promotions Data

- **Promotion Id:** Unique ID of the promotion
- **Date:** Date of the promotion
- **Discount:** Discount percentage
- **ProductId:** Unique ID of the product

## Conclusion

The insights derived from this project can significantly impact strategic decisions in ecommerce, helping businesses better understand their customers, optimize their product offerings, and maximize the effectiveness of their promotions.

