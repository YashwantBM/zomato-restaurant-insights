# zomato-restaurant-insights

# 🍽️ Zomato Restaurant Insights Project

## 📌 Objective
Build an end-to-end analytics solution to extract, model, and visualize restaurant data from Zomato to help understand market trends, pricing strategies, and customer preferences across Indian cities.

## 🛠️ Tools & Tech Stack
- **Power BI**: Interactive dashboards & visualizations
- **Excel**: Data cleaning & intermediate transformations
- **API Integration**: Zomato Public API (for dynamic city/restaurant info)
- **Data Modeling**: Star schema design, relationship mapping in Power BI

## 🔄 Workflow Overview
1. **Data Extraction**:
   - Pulled real-time data using Zomato APIs (cities, restaurants, cuisines, etc.)
   - Combined with structured CSV/Excel datasets for enrichment

2. **Data Preparation**:
   - Cleaned and pre-processed in Excel (duplicates, missing values, formatting)
   - Built surrogate keys and structured the dataset

3. **Data Modeling**:
   - Designed star schema (Fact: Orders, Ratings | Dimension: City, Cuisine, Restaurant)
   - Defined relationships in Power BI for optimized querying

4. **Visualization & Storytelling**:
   - Built an interactive Power BI dashboard with slicers, filters, and KPIs
   - Deployed insights into city-wise trends, cuisine preferences, and delivery patterns

## 📊 Dashboard Highlights
- 📍 Top Cities by Restaurant Count
- 🍜 Most Popular Cuisines
- 💸 Average Cost for Two (City & Cuisine-wise)
- ⭐ Rating Distribution & Customer Votes
- 🚚 Online Delivery vs Dine-in Preferences
