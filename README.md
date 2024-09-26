# AdventureWorks Sales Analysis Dashboard


# Overview

This repository contains the Power BI project for AdventureWorks' sales analysis dashboard. The dashboard provides a comprehensive view of the company's sales performance, including revenue, profit, orders, and product-specific metrics.

# Features

Real-time KPI tracking (Revenue, Profit, Orders, Return Rate)

Revenue trend analysis

Order distribution by product category

Detailed product performance metrics

Monthly revenue, orders, and returns tracking

Most ordered and most returned product types

# Dashboard Components:

KPI Summary: Displays top-level metrics including total revenue ($25M), profit ($10.5M), number of orders (25K), and return rate (2.17%).

Revenue Trending: A line chart showing revenue trends from January 2020 to present, with a dotted trendline for reference.

Order by Category: Bar chart breaking down orders by product categories (Accessories, Bikes, Clothing).

Product Performance Table: Detailed breakdown of individual product performance, including total orders, revenue, and return rate.

Monthly Metrics: Cards showing current month's revenue ($1,826,987), orders (2146), and returns (166) with comparison to previous periods.

Product Insights: Quick view of the most ordered product type (Tires and Tubes) and most returned product type (Shorts).


# Setup and Usage

Prerequisites:

Power BI Desktop (latest version recommended)

Access to AdventureWorks data sources (e.g., SQL Server database, Excel files, or other data connections)

Setup Instructions:

Clone this repository or download the .pbix file to your local machine.

Open Power BI Desktop.

Go to File > Open and select the downloaded .pbix file.

Data Refresh:

In Power BI Desktop, go to Home > Refresh to update the dashboard with the latest data.

If prompted, enter your credentials for the data sources.

Customizing the Dashboard:

To modify visuals, click on any chart or graph and use the Visualizations pane to adjust properties.

To add new visuals, select a visual type from the Visualizations pane and drag fields from the Fields pane.

Use the Filters pane to add or modify filters at the visual, page, or report level.

Using Slicers:

The dashboard includes date slicers for time-based filtering. Use these to adjust the time range for all visualizations.

Category and product slicers allow for drilling down into specific product lines or categories.

Interacting with Visuals:

Hover over data points in charts to see detailed tooltips.

Click on categories in the "Order by Category" chart to filter other visuals.

Use the scroll bar in the product performance table to view all products.

# Sharing and Publishing:

To share the dashboard, go to File > Publish > Publish to Power BI.

Select the workspace where you want to publish the report.

Once published, you can set up automatic refresh schedules and share the dashboard with other users in your organization through Power BI Service.

Troubleshooting:

If you encounter data connection issues, verify your data source connections in Home > Transform data > Data source settings.

For performance issues, consider using Power BI's Performance Analyzer to identify bottlenecks.
