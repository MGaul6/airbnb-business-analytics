# Airbnb Business Analytics: Pricing, Availability & Customer Satisfaction Analysis

## Project Overview

This project analyzes Airbnb listing data to uncover insights related to pricing, customer satisfaction, host performance, and occupancy trends. The goal is to help Airbnb hosts and property investors make data-driven decisions to optimize listing performance and improve guest experience.

## Dataset

The dataset contains over 100,000 Airbnb listings and includes information about:

* Property details
* Host information
* Pricing
* Availability
* Customer reviews
* Booking policies
* Neighborhood information

### Key Features

* Price
* Service Fee
* Room Type
* Availability (365 Days)
* Number of Reviews
* Review Rate Number
* Instant Bookable
* Cancellation Policy
* Host Verification Status
* Neighborhood

## Business Questions

1. Which neighborhoods have the highest average prices?
2. What factors influence customer ratings?
3. Does instant booking impact customer satisfaction?
4. Which room types generate the highest revenue potential?
5. How does availability affect demand?
6. Which hosts manage the most listings?

## Tools & Technologies

* SQL
* Power BI
* Microsoft Excel
* GitHub

## Data Cleaning

Performed the following preprocessing steps:

* Removed duplicate records
* Handled missing values
* Converted price and service fee columns to numeric format
* Standardized date fields
* Validated review and availability metrics

## SQL Analysis

### Pricing Analysis

* Average price by neighborhood
* Average price by room type
* Premium vs Budget listings

### Customer Satisfaction Analysis

* Review score analysis
* Rating comparison across room types
* Rating comparison across cancellation policies

### Host Analysis

* Top hosts by listing count
* Verified vs Non-verified hosts

### Occupancy Analysis

* Availability trends
* High-demand listings
* Neighborhood demand comparison

## Dashboard Features

### KPI Cards

* Total Listings
* Average Price
* Average Rating
* Total Reviews
* Average Availability

### Visualizations

* Price by Neighborhood
* Price by Room Type
* Rating Distribution
* Host Performance Analysis
* Availability Analysis
* Customer Satisfaction Insights

## Key Insights

* Entire homes generally command higher prices than private rooms.
* Listings with higher ratings tend to receive more reviews.
* Some neighborhoods consistently outperform others in pricing and demand.
* Availability can serve as a strong indicator of occupancy and booking activity.

## Business Recommendations

* Optimize pricing based on neighborhood benchmarks.
* Encourage guest reviews to improve listing visibility.
* Consider enabling instant booking to improve customer convenience.
* Monitor availability trends to identify demand patterns.

## Project Structure

```text
Airbnb-Business-Analytics/
│
├── data/
│   ├── Airbnb_Open_Data.csv
│
├── sql/
│   ├── data_cleaning.sql
│   ├── pricing_analysis.sql
│   ├── customer_satisfaction.sql
│   ├── occupancy_analysis.sql
│   └── host_analysis.sql
│
├── dashboard/
│   ├── Airbnb_Dashboard.pbix
│
├── images/
│   ├── dashboard_overview.png
│
└── README.md
```

## Author

Mansi Gaul
