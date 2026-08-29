# 🏠 Seattle Airbnb Market Analysis — Tableau

## 1. Project Overview

This project analyzes Airbnb listing and calendar data for **Seattle, Washington** using **Tableau**.

The objective is to explore how Airbnb prices vary across geographic locations and property sizes, while also examining pricing and revenue patterns over time.

The project demonstrates the use of Tableau to transform real-world rental-market data into visual analysis that can support market research, pricing analysis, and data-driven decision-making.

---

## 2. Business Problem

Airbnb hosts and property investors need to understand how factors such as **location, property size, and time** can influence rental pricing and potential revenue.

This project addresses this problem by analyzing Seattle Airbnb data from multiple perspectives.

The analysis focuses on:

* Geographic pricing differences
* Average price by bedroom count
* Distribution of listings by bedroom count
* Revenue patterns over time
* Location-based market differences

---

## 3. Project Objectives

The main objectives of this project are to:

1. Analyze Airbnb prices across Seattle ZIP codes.
2. Identify geographic differences in listing prices.
3. Examine pricing patterns across the analyzed calendar period.
4. Compare average prices according to the number of bedrooms.
5. Understand the distribution of Airbnb listings by bedroom count.
6. Present the findings through clear and effective Tableau visualizations.

---

## 4. Dataset

The project uses the **Seattle Airbnb Open Data** dataset.

The dataset contains information about Airbnb listings, calendar availability, pricing, hosts, properties, and reviews.

### Dataset Components

#### Listings

The Listings table contains property-level information such as:

* Listing ID
* Property type
* Room type
* Location
* ZIP code
* Bedrooms
* Bathrooms
* Beds
* Accommodation capacity
* Price
* Availability
* Host information
* Review information

#### Calendar

The Calendar table contains daily information associated with individual listings, including:

* Listing ID
* Date
* Availability
* Daily price

#### Reviews

The Reviews table contains information about guest reviews, including:

* Listing ID
* Review ID
* Review date
* Reviewer information
* Review comments

The primary analysis in this project uses the **Listings** and **Calendar** data.

---

## 5. Data Source

**Dataset:** Seattle Airbnb Open Data

**Source:** Kaggle

**Original Dataset:**
https://www.kaggle.com/datasets/airbnb/seattle

The dataset is provided under a **CC0: Public Domain** license.

---

## 6. Data Model & Connection

The Tableau workbook connects to the Excel source file containing the Airbnb data.

The Listings and Calendar tables are related using the listing identifier:

```text
Listings.id = Calendar.listing_id
```

This connection allows property-level attributes such as:

* ZIP code
* Bedrooms
* Property information

to be analyzed together with calendar-level information such as:

* Date
* Availability
* Price

This structure enables the analysis of both property characteristics and time-based pricing information.

---

## 7. Data Preparation

The dataset was prepared for visualization within Tableau.

The main preparation process involved:

* Connecting Tableau to the Excel dataset
* Identifying the relevant Listings and Calendar tables
* Establishing the relationship between listing records and calendar records
* Selecting relevant dimensions and measures
* Using appropriate aggregations for pricing and listing analysis
* Preparing geographic fields for map-based analysis
* Preparing date fields for time-based analysis

The project primarily relies on Tableau's built-in aggregation and visualization capabilities to transform the connected data into analytical views.

---

# 8. Tableau Analysis

The workbook contains five main analytical worksheets and a dashboard.

---

## 8.1 Price by ZIP Code

### Objective

Analyze differences in Airbnb pricing across Seattle ZIP codes.

### Visualization

A comparative chart is used to examine price levels across different ZIP codes.

### Analytical Question

> Which ZIP codes have relatively higher or lower Airbnb prices?

### Business Relevance

This analysis can help identify geographic areas where Airbnb listings command higher prices.

For potential hosts or property investors, understanding geographic pricing differences can provide useful context when evaluating potential locations.

---

## 8.2 Price per ZIP Code

### Objective

Analyze Airbnb pricing geographically across Seattle.

### Visualization

A geographic map is used to visualize price levels by location.

### Analytical Question

> How does Airbnb pricing vary geographically across Seattle?

### Business Relevance

Geographic visualization makes it easier to identify spatial pricing patterns and areas with relatively higher or lower listing prices.

---

## 8.3 Revenue per Year

### Objective

Analyze pricing/revenue-related patterns over the analyzed calendar period.

### Visualization

A time-based visualization is used to examine changes across dates.

### Analytical Question

> How does Airbnb revenue-related activity change over time?

### Business Relevance

Time-based analysis can help hosts understand changes in potential rental income and identify periods of stronger or weaker pricing.

### Important Note

The analysis should be interpreted as **revenue-related pricing analysis**, rather than confirmed realized revenue, because listing prices do not necessarily represent actual completed bookings or collected revenue.

---

## 8.4 Average Price per Bedroom

### Objective

Examine the relationship between property size and average Airbnb price.

### Visualization

A comparison of average price across bedroom categories.

### Analytical Question

> How does average Airbnb price change as the number of bedrooms increases?

### Business Relevance

This analysis provides insight into how property size may influence nightly rental pricing.

It can be useful when comparing potential rental properties or evaluating pricing strategies.

---

## 8.5 Number of Listings by Bedroom Count

### Objective

Understand the composition of the Airbnb market according to property size.

### Visualization

A categorical visualization compares the number of listings across bedroom categories.

### Analytical Question

> Which property sizes are most common within the dataset?

### Business Relevance

Understanding listing supply by bedroom count provides additional context when interpreting pricing differences between property sizes.

---

# 9. Dashboard

The Tableau workbook includes a dedicated dashboard that brings the analysis together into a single analytical interface.

The dashboard combines the project's major views to provide a consolidated overview of:

* Geographic pricing
* ZIP-code pricing
* Revenue trends
* Average price by bedroom count
* Listing distribution by bedroom count

The dashboard allows the individual visualizations to be interpreted together rather than in isolation.

---

# 10. Key Findings

The analysis provides several notable observations.

### Geographic Pricing

Airbnb prices vary across Seattle ZIP codes, indicating that location is an important factor associated with listing prices.

### Property Size

Average Airbnb prices generally increase as the number of bedrooms increases.

### Listing Supply

Smaller properties, particularly one-bedroom listings, represent a substantial portion of the available listings in the dataset.

### Larger Properties

Larger properties tend to have higher average prices but represent a smaller portion of total listings.

### Time-Based Variation

Pricing and revenue-related patterns vary across the analyzed calendar period, suggesting that Airbnb pricing is not constant over time.

---

# 11. Visualization Strategy

Different visualization types were selected based on the analytical question being addressed.

| Analysis                  | Visualization Purpose                  |
| ------------------------- | -------------------------------------- |
| Price by ZIP Code         | Compare pricing between locations      |
| Price per ZIP Code        | Identify geographic pricing patterns   |
| Revenue per Year          | Examine time-based changes             |
| Average Price per Bedroom | Compare pricing by property size       |
| Listings by Bedroom Count | Examine market supply by property size |

The combination of geographic, categorical, and time-based visualizations provides multiple perspectives on the Seattle Airbnb market.

---

# 12. Tools & Technologies

### Primary Tool

**Tableau**

### Data Source

**Microsoft Excel**

### Skills Demonstrated

* Tableau
* Data Visualization
* Exploratory Data Analysis
* Geographic Visualization
* Time-Series Analysis
* Pricing Analysis
* Market Analysis
* Business Intelligence
* Data Storytelling
* Dashboard Development

---

# 13. Tableau Skills Demonstrated

This project demonstrates practical experience with:

* Connecting Tableau to Excel
* Working with multiple related tables
* Creating calculated and aggregated views
* Geographic mapping
* Time-based analysis
* Categorical comparisons
* Numerical aggregation
* Data visualization
* Dashboard composition
* Visual formatting
* Data storytelling

---

# 14. Business Applications

The analytical approach used in this project can be applied to a variety of business scenarios.

### Real Estate

Analyzing property prices and geographic differences.

### Short-Term Rentals

Evaluating rental pricing and potential market opportunities.

### Market Research

Identifying differences in pricing and supply across locations.

### Revenue Analysis

Understanding changes in pricing and potential revenue over time.

### Investment Analysis

Comparing property characteristics and market conditions before making investment decisions.

---

# 15. Limitations

Several limitations should be considered when interpreting the analysis.

### Historical Dataset

The dataset represents a historical snapshot of Seattle's Airbnb market and should not be treated as a representation of current market conditions.

### Revenue Interpretation

Listing prices should not automatically be interpreted as actual revenue because actual revenue depends on bookings, occupancy, discounts, fees, cancellations, and other factors.

### Survey/Listing Coverage

The dataset represents listings captured during the collection period and may not represent every Airbnb property operating in Seattle.

### Market Changes

Rental prices, supply, demand, regulations, and operating conditions can change significantly over time.

---

# 16. Potential Improvements

Future versions of this project could expand the analysis by adding:

* Occupancy-rate analysis
* Estimated annual revenue based on occupancy
* Neighborhood-level analysis
* Property-type comparisons
* Room-type comparisons
* Superhost vs. non-Superhost analysis
* Review-score analysis
* Seasonal pricing analysis
* Interactive filters
* Advanced Tableau calculated fields
* Parameter-driven analysis
* Drill-down functionality
* Profitability analysis after expenses

---

# 17. Recommended Future Dashboard

A future version could expand the current analysis into a multi-page Tableau dashboard consisting of:

### Page 1 — Market Overview

* Total Listings
* Average Price
* Average Bedrooms
* Estimated Revenue
* Geographic pricing map

### Page 2 — Pricing Analysis

* Price by ZIP code
* Price by neighborhood
* Price by property type
* Price by room type

### Page 3 — Property Analysis

* Average price by bedroom count
* Listing distribution
* Accommodation capacity
* Property type comparison

### Page 4 — Revenue & Seasonality

* Monthly revenue trends
* Monthly average price
* Occupancy rate
* Seasonal pricing patterns

This would provide a more complete business intelligence solution.

---

# 18. Repository Contents

The GitHub repository contains:

```text
tableau-seattle-airbnb-market-analysis/
│
├── README.md
│
├── Tableau/
│   └── Airbnb_Full_Project.twb
│
├── Dataset/
│   └── Tableau_Full_Project.xlsx
│
├── Screenshots/
│   └── tableau-analysis.png
│
└── Documentation/
    └── Project_Overview.md
```

---

# 19. Project Outcome

This project strengthened my ability to transform real-world data into meaningful visual analysis using Tableau.

The project demonstrates how geographic, property-level, and time-based dimensions can be combined to investigate pricing patterns and market characteristics.

The resulting analysis provides a foundation for more advanced Airbnb market, revenue, occupancy, and profitability analysis.

---

# 20. Conclusion

The **Seattle Airbnb Market Analysis** demonstrates the use of Tableau to analyze a real-world short-term rental dataset from multiple analytical perspectives.

By combining geographic analysis, pricing comparisons, property-size analysis, listing distribution, and time-based analysis, the project provides a structured view of the Seattle Airbnb market.

The project showcases practical skills in **Tableau, data visualization, exploratory analysis, geographic analysis, business intelligence, and data storytelling**.

---

## 👨‍💻 Author

**Muhammad**

Business Data Analytics Student | Aspiring Data Analyst

**Portfolio:** SQL • Excel • Power BI • Tableau • Python
