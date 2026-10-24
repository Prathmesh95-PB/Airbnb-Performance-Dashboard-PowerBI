# Global Airbnb Performance Dashboard | Power BI

## Project Overview

An interactive Power BI dashboard that analyzes Airbnb's global marketplace across 10 cities, focusing on listing distribution, room-type pricing, customer review patterns, host verification, and property ratings.

The project uses data visualization, analytical calculations, and business-focused storytelling to transform Airbnb listing and review data into actionable insights.

## Project Purpose

The objective of this project is to understand how Airbnb listings perform across different cities, how customer review activity varies over time, and how pricing, ratings, and host verification contribute to marketplace insights.

The dashboard is designed to help stakeholders explore marketplace distribution, evaluate customer engagement, compare listing prices, and identify areas for further investigation.

## Business Problem

Airbnb operates across cities with different listing volumes, price levels, customer engagement patterns, and host characteristics. Understanding these differences is important for evaluating marketplace performance and identifying potential opportunities.

Analyzing multiple datasets separately can make it difficult to identify patterns in review frequency, pricing, listing distribution, and customer ratings.

This project addresses the challenge through an interactive Power BI dashboard that brings these dimensions together in a structured analytical report.

## Project Goals

- Analyze Airbnb listing distribution and market share across cities.
- Compare customer review activity across months and locations.
- Investigate review frequency and cumulative reviewer patterns.
- Examine host identity verification and profile-related trust indicators.
- Compare prices across different room types.
- Evaluate city-level ratings for cleanliness, communication, accuracy, value, and location.
- Translate dashboard findings into business observations and recommendations.

## Tech Stack

- **Power BI Desktop** — Dashboard development and reporting
- **Power Query** — Data cleaning and transformation
- **DAX** — Measures and analytical calculations
- **Data Modeling** — Organizing tables and relationships
- **Data Visualization** — KPI comparisons, trend analysis, cumulative analysis, and heatmaps

## Data Source

**Dataset:** Airbnb Listings & Reviews

**Provider:** Maven Analytics Data Playground

**Dataset link:** [https://mavenanalytics.io/data-playground/airbnb-listings-reviews](https://mavenanalytics.io/data-playground/airbnb-listings-reviews)

The dataset provides Airbnb listing and review information for analysis. The exact tables, fields, and reporting period depend on the downloaded dataset version.

## Dashboard Features

### Page 1: Review Frequency & Trust

**1. Review Frequency Analysis**

- Examines the distribution of reviewers by review frequency.
- Uses a bar chart and cumulative percentage line to highlight how frequently reviewers contribute reviews.
- Helps identify whether review activity is concentrated among occasional or frequent reviewers.

**2. Monthly Review Trends**

- Compares monthly review activity across cities.
- Highlights seasonal variation and differences in review patterns between markets.
- Supports exploration of customer engagement throughout the year.

**3. Host Trust Analysis**

- Compares identity-verified and non-verified hosts.
- Examines the availability of host profile pictures.
- Provides a view of host identity and profile-related trust signals.

### Page 2: Market Share & Ratings

**1. Market Share by City**

- Compares listing counts across 10 cities.
- Distinguishes Superhost and non-Superhost listings.
- Uses a cumulative percentage line to show how the leading cities contribute to the selected total.

**2. Pricing by Room Type**

- Compares average listing prices across hotel rooms, entire places, shared rooms, and private rooms.
- Helps identify price differences between accommodation categories.

**3. City-Level Ratings**

- Compares five rating dimensions: cleanliness, communication, accuracy, value, and location.
- Uses a color-coded heatmap to make differences between cities and rating categories easier to identify.

## Key Business Questions

1. Which cities account for the largest share of Airbnb listings?
2. How concentrated is listing distribution across the selected cities?
3. How does review activity vary across months and locations?
4. What does reviewer frequency reveal about customer review behavior?
5. What proportion of hosts have verified identities or profile pictures?
6. How do listing prices differ by room type?
7. Which cities perform relatively well or poorly across the available rating dimensions?
8. Which areas may warrant further investigation to improve marketplace performance and guest experience?

## Business Insights Highlighted in the Dashboard

The dashboard annotations highlight the following observations from the displayed analysis:

- **Market concentration:** Paris, New York, and Sydney are highlighted as major contributors to the listing and review totals.
- **Reviewer frequency:** The review frequency analysis indicates that most reviewers contribute only a small number of reviews.
- **Review seasonality:** The monthly review chart highlights differences in review patterns across cities, including stronger activity in some European cities during the summer period.
- **Host verification:** The trust section emphasizes the proportion of hosts with verified identities and the availability of profile pictures.
- **Pricing differences:** The room-type comparison shows differences in displayed average prices, with hotel rooms having the highest price among the categories shown.
- **Rating comparisons:** The city-level heatmap makes it easier to compare ratings across cleanliness, communication, accuracy, value, and location.

These observations describe the dashboard's displayed analysis. They should be interpreted in the context of the selected dataset, its reporting period, and the measures used.

## Business Impact

The dashboard demonstrates how Power BI can support marketplace analysis through:

- **Market prioritization:** Identifying cities with a large share of listings.
- **Pricing analysis:** Comparing room-type prices to support further pricing investigations.
- **Customer engagement analysis:** Monitoring review activity and identifying seasonal patterns.
- **Trust analysis:** Exploring host verification and profile-related indicators.
- **Service quality evaluation:** Comparing city-level ratings to identify dimensions that may need attention.
- **Decision support:** Presenting multiple analytical perspectives in a consolidated, easy-to-understand report.

## Project Workflow

1. Downloaded the Airbnb Listings & Reviews dataset from Maven Analytics.
2. Explored the available data and identified relevant listing, review, host, and rating attributes.
3. Cleaned and transformed the data using Power Query where required.
4. Organized the data model and relationships for analysis.
5. Created analytical calculations and measures using DAX where applicable.
6. Developed the review frequency, monthly trend, trust, market share, pricing, and rating visuals.
7. Applied chart formatting, color coding, and annotations to improve readability.
8. Interpreted the dashboard results and documented business observations.

## Key Learnings

- Building a multi-page Power BI dashboard around business questions.
- Comparing categorical and time-based data.
- Using cumulative percentage analysis to examine market concentration.
- Comparing listing prices across accommodation categories.
- Analyzing host verification and customer rating indicators.
- Using heatmaps and chart annotations to communicate insights.
- Connecting data visualization with practical business interpretation.

https://github.com/Prathmesh95-PB/Airbnb-Performance-Dashboard-PowerBI/blob/main/Overview.png

https://github.com/Prathmesh95-PB/Airbnb-Performance-Dashboard-PowerBI/blob/main/Reviews.png

https://github.com/Prathmesh95-PB/Airbnb-Performance-Dashboard-PowerBI/blob/main/Ratings.png
