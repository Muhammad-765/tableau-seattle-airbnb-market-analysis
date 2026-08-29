# 🏠 Tableau – Seattle Airbnb Market Analysis

## 📊 Project Overview

This project analyzes **Seattle Airbnb listing and calendar data** using **Tableau** to understand pricing patterns, geographic differences, revenue trends, and the relationship between property size and nightly pricing.

The analysis transforms Airbnb listing and calendar data into a collection of interactive visualizations designed to answer practical questions about the Seattle short-term rental market.

The project demonstrates practical skills in **Tableau, data visualization, exploratory data analysis, geographic analysis, and business intelligence**.

---

## 🎯 Project Objectives

The analysis focuses on understanding how Airbnb pricing varies across Seattle and how property characteristics influence pricing.

The project explores the following questions:

* How does Airbnb pricing vary across ZIP codes?
* Which areas of Seattle have higher listing prices?
* How are Airbnb prices distributed geographically?
* How does revenue change throughout the year?
* How does average nightly price change with the number of bedrooms?
* How many Airbnb listings are available within each bedroom category?
* What patterns can be identified that may be useful for Airbnb hosts or potential property investors?

---

## 📂 Dataset

The project uses the **Seattle Airbnb Open Data** dataset.

The dataset contains three primary tables:

### Listings

Contains detailed information about Airbnb properties, including:

* Listing ID
* Property type
* Room type
* Location
* ZIP code
* Bedrooms
* Bathrooms
* Beds
* Accommodates
* Price
* Availability
* Reviews
* Host information
* Review scores

### Calendar

Contains daily listing-level information including:

* Listing ID
* Date
* Availability
* Daily price

### Reviews

Contains guest review information including:

* Listing ID
* Review ID
* Review date
* Reviewer information
* Review comments

For this Tableau analysis, the **Listings** and **Calendar** tables are joined using the listing ID.

### Dataset Statistics

| Dataset  |   Records | Purpose                        |
| -------- | --------: | ------------------------------ |
| Listings |     3,818 | Property and host information  |
| Calendar | 1,048,575 | Daily availability and pricing |
| Reviews  |    84,849 | Guest review information       |

**Data Source:** Seattle Airbnb Open Data — Kaggle

The original dataset is published as **CC0: Public Domain**.

---

## 🔗 Data Source

[Seattle Airbnb Open Data – Kaggle](https://www.kaggle.com/datasets/airbnb/seattle)

---

## 🔄 Data Preparation

The Tableau workbook connects to the Excel dataset containing the Airbnb Listings and Calendar tables.

The Listings and Calendar datasets are connected using:

```text
Listings.id = Calendar.listing_id
```

This relationship allows listing characteristics such as bedrooms, ZIP code, and property information to be analyzed alongside calendar-level pricing and availability information.

The project uses Tableau's analytical and visualization capabilities to aggregate the data into meaningful business views.

---

# 📈 Analysis & Visualizations

## 1. Price by ZIP Code

This visualization compares Airbnb pricing across Seattle ZIP codes.

### Purpose

To identify geographic differences in Airbnb prices and determine whether certain ZIP codes command higher prices than others.

### Business Use

This type of analysis can help prospective hosts and property investors understand how location may influence Airbnb pricing.

---

## 2. Price per ZIP Code — Geographic Analysis

A geographic visualization maps Airbnb pricing across Seattle.

### Purpose

To provide a spatial view of pricing patterns and make geographic differences easier to identify.

### Business Use

Mapping pricing data can help users identify areas with relatively higher or lower Airbnb prices and support location-based market research.

---

## 3. Revenue per Year

A time-based visualization analyzes pricing data across the calendar period.

### Purpose

To examine how Airbnb revenue-related pricing patterns change throughout the year.

### Business Use

Understanding seasonal changes can help hosts evaluate periods of stronger or weaker potential revenue and consider pricing strategies accordingly.

---

## 4. Average Price per Bedroom

This visualization compares average Airbnb prices according to the number of bedrooms.

### Purpose

To understand the relationship between property size and nightly pricing.

### Business Use

This analysis can help hosts and investors evaluate how additional bedrooms may influence potential rental pricing.

---

## 5. Number of Listings by Bedroom Count

This visualization examines the number of Airbnb listings within different bedroom categories.

### Purpose

To understand the composition of the Airbnb market by property size.

### Business Use

Comparing listing volume with average price provides additional context for understanding supply across different property sizes.

---

# 🔍 Key Findings

The analysis reveals several notable patterns:

* Airbnb prices vary considerably across Seattle ZIP codes, indicating that location is an important factor in the short-term rental market.
* Geographic visualization makes it possible to identify clusters of relatively higher and lower pricing.
* Average nightly prices generally increase as the number of bedrooms increases.
* One-bedroom properties represent a large share of the listings in the dataset, while larger properties become progressively less common.
* Larger properties command substantially higher average nightly prices, although the number of available listings decreases at higher bedroom counts.
* Calendar-based analysis shows that Airbnb pricing changes over the analyzed period, providing evidence of temporal variation in the market.

These findings demonstrate how location, property size, and time can be analyzed together to understand Airbnb market behavior.

---

# 🛠️ Tools & Technologies

### Primary Tool

**Tableau**

### Supporting Tools

**Microsoft Excel**

### Analytical Skills

* Data Visualization
* Exploratory Data Analysis
* Geographic Analysis
* Time-Series Analysis
* Pricing Analysis
* Business Intelligence
* Data Storytelling
* Interactive Visualization
* Market Analysis

---

# 📊 Tableau Techniques Demonstrated

This project demonstrates practical experience with:

* Connecting Tableau to Excel data
* Combining related datasets
* Creating calculated and aggregated views
* Geographic visualization
* Mapping location-based data
* Time-series visualization
* Comparing categorical dimensions
* Analyzing numerical measures
* Creating interactive analytical views
* Formatting professional visualizations
* Building a cohesive Tableau analysis

---

# 💼 Business Perspective

The analysis can be viewed from the perspective of a potential Airbnb host, property investor, or market analyst evaluating the Seattle short-term rental market.

The visualizations provide insight into three major factors:

### 📍 Location

Where a property is located can have a significant relationship with its market price.

### 🛏️ Property Size

The number of bedrooms provides an important dimension for comparing property pricing and market supply.

### 📅 Time

Pricing patterns across the calendar period provide context for understanding changes in potential revenue opportunities.

Together, these dimensions demonstrate how data visualization can support property-market research and pricing decisions.

---

# ⚠️ Limitations

The analysis is based on a historical Seattle Airbnb dataset and therefore should not be interpreted as a representation of current Airbnb market conditions.

The dataset represents listings and calendar information collected during the analyzed period. Airbnb pricing, supply, regulations, demand, and market conditions can change significantly over time.

Revenue-related analysis should also be interpreted carefully because listing price and potential revenue are not equivalent to actual realized revenue.

---

# 🚀 Future Improvements

Potential improvements include:

* Adding interactive filters for neighborhood, property type, and room type
* Adding occupancy-rate analysis
* Comparing Superhost and non-Superhost performance
* Incorporating review scores into pricing analysis
* Creating more detailed seasonal analysis
* Adding profitability estimates after accounting for fees and operating costs
* Adding KPI cards for total listings, average price, occupancy, and estimated revenue
* Publishing the final interactive workbook through Tableau Public

---

# 📸 Dashboard / Visualization Preview

<img width="1336" height="581" alt="Dashboard" src="https://github.com/user-attachments/assets/686f02b6-9ef7-40f6-a18f-c40c204678bf" />


---

# 📁 Repository Structure

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

# 📌 Project Deliverables

* Tableau workbook
* Source dataset
* Visualization screenshots
* Project documentation
* Analytical findings
* GitHub repository

---

# 🎓 Learning Outcomes

Through this project, I strengthened my ability to:

* Work with real-world business datasets
* Connect and analyze multiple related tables
* Build geographic and time-based visualizations
* Analyze pricing patterns
* Translate data into business-oriented insights
* Design analytical visualizations in Tableau
* Communicate findings through data storytelling

---

# 👨‍💻 Author

**Muhammad**

Business Data Analytics Student | Aspiring Data Analyst

**Portfolio Skills:** Tableau • Power BI • SQL • Excel • Python • Data Analysis • Data Visualization • Business Intelligence
