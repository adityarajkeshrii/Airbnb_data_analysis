# Airbnb Data Analytics 

An end-to-end data analytics project using Excel and SQL to analyze the Airbnb Open Dataset. Cleaned and formatted raw listings in Excel, then executed complex SQL queries to extract data-driven insights on pricing trends, occupancy patterns, and host behaviors to identify revenue optimization opportunities in the hospitality industry.

## Project Objective
The objective of this project was to identify key factors influencing Airbnb pricing, occupancy, and customer preferences. By translating raw listing data into actionable business insights, this project supports revenue optimization, occupancy management, and customer experience improvements.

## Data Source
* **Kaggle**: Airbnb Open Dataset

## Tools & Technologies
* **Excel**: Used for initial data pipeline engineering, including cleaning duplicates, handling missing text values, and formatting columns.
* **SQL / SQLite**: Used for deep data analysis, executing complex queries, aggregations, and joins to uncover market trends.

## Project Workflow

### 1. Data Cleaning (Excel)
* Removed duplicate listing IDs and standardized date formats.
* Handled missing values in critical columns like price and review scores.
* Filtered out extreme outliers in pricing and minimum night requirements.

### 2. Data Analysis (SQL)
* **Pricing Trends**: Analyzed average price fluctuations across different neighborhoods and seasons.
* **Room Preferences**: Grouped data by room type (entire home, private room, shared room) to evaluate demand.
* **Host Behavior**: Measured listing frequencies per host to identify commercial vs. casual hosts.
* **Property Availability**: Calculated average booking patterns based on 365-day availability metrics.

## Key Insights
* **Accommodation Dominance**: Entire homes and private rooms dominate the market, indicating a stronger host preference toward offering more private accommodation options.
* **Niche Categories**: Shared and hotel rooms represent only a small portion of listings, suggesting a comparatively lower market presence and demand.
* **Overall Market Drivers**: The Airbnb market is largely driven by premium-priced listings, short-stay accommodations, and entire/private room preferences. 
* **Customer Satisfaction**: Guest satisfaction is highly influenced by service quality, pricing strategy, booking flexibility, and property availability.

## Strategic Recommendations
* **Enhance Privacy & Comfort**: Since private and entire room accommodations dominate the market, hosts can focus on improving privacy, comfort, and amenities to attract more guests.
* **Optimize Revenue Potential**: Data-driven pricing and an improved guest experience can help hosts maximize occupancy and revenue potential.
* **Adopt Best Practices**: Hosts should adopt competitive pricing, maintain high service quality, encourage instant bookings, and optimize availability strategies to improve customer satisfaction and maximize revenue.

## How to Run the Queries
1. Download the cleaned dataset file from the `data/` folder.
2. Import the dataset into your SQLite environment.
3. Open and run the scripts provided in the `sql_queries/` folder.
