# oibsip_task3
# Airbnb Data Analysis

This project involves exploratory data analysis (EDA) and cleaning of an Airbnb dataset using Python. The goal is to uncover insights about pricing, availability, and property types, while also applying core data cleaning techniques.

---

## Key Objectives

- Understand the structure and quality of the data
- Handle missing values and inconsistent data types
- Remove duplicate and irrelevant records
- Detect and manage outliers
- Explore room types, pricing, and neighborhood distributions

---

## Dataset Features

The dataset includes information on:

- Listing ID and name
- Host information
- Location: neighbourhood, latitude, and longitude
- Room type and price
- Minimum nights required, number of reviews, and availability
- Review dates and frequency

---

## Data Cleaning Steps

1. **Data Type Conversion** – Ensured `last_review` column is in datetime format.
2. **Missing Values** – Filled or removed nulls in `name`, `host_name`, `last_review`, and `reviews_per_month`.
3. **Duplicate Check** – Verified no duplicate entries.
4. **Outlier Detection** – Analyzed extreme values in `price` and `minimum_nights`, then filtered out unrealistic entries.

---

## Key Visualizations

- Distribution of room types
- Top 10 neighborhoods by number of listings
- Average price per room type
- Boxplots to explore outliers

---

## Tools Used

- Python (pandas, matplotlib, seaborn)
- Jupyter Lab
- Git & GitHub

---

## Status

- Completed data cleaning  
- Visualized key insights
  
---

Project developed as part of a data analysis learning journey.

---
