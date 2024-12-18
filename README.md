# The Location Effect

## 1. Introduction
This project analyzes the sales performance of two restaurants in Panama to identify opportunities for improvement and provide actionable recommendations to increase revenue. The two restaurants differ significantly in location and customer demographics, offering a valuable case study on how external factors like location impact sales performance.

## 2. Dataset Description

**Data Source**: The dataset was provided by the restaurant owners and includes detailed records of sales, product categories, and customer purchasing behavior.

**Key Variables**:
- Category 1: High-level product groupings (e.g., Appetizers, Main Courses, Desserts).
- Category 2: Broad classifications (e.g., Food, Non-Alcoholic, Alcoholic Beverages).
- Sales Data: Total revenue and units sold for each product.
- Timestamps: Date and time of transactions for trend analysis.

## 3. Data Cleaning Process

1. **Standardized Text Formats**: Adjusted text formatting to ensure consistency, converting all-uppercase and all-lowercase entries to title case.
2. **Removed Empty Records**: Deleted rows containing null or empty values to maintain data quality.
3. **Filtered Irrelevant Data**: Removed information not relevant to this analysis.
4. **Categorized Products**:
   - Sorted Category 2 into Food, Non-Alcoholic Beverages, and Alcoholic Beverages.
   -Reorganized Category 1 by correctly assigning items to classifications like Appetizers, Main Courses, and Desserts.

## 4. Methodology

**Exploratory Data Analysis (EDA)**:
- Used visualizations to uncover trends in sales by category, day, and hour.

**Forecasting**:
- Implemented time series forecasting (Prophet) to predict future sales trends.

**Comparative Analysis**:
- Compared performance across categories, products, and locations.

**Insight Extraction**:
- Identified top-performing products and key customer behaviors.

## 5. Insights

**Restaurant 1**:

- **Product Performance**: Alcoholic beverages dominate sales (64%), with luxury items like Dom Perignon and Macallan driving the highest revenue per unit.

- **Peak Times**:
  - Fridays and Saturdays contribute 15% higher sales compared to Mondays.
  - Peak activity occurs between 5 PM and 7 PM, with sales 20% above the daily average.

- **Seasonal Trends**: December sales are projected to be 40% higher than June 2024.

**Restaurant 2**:

- **Balanced Revenue**: Alcoholic beverages (48%) lead sales but are closely followed by food (45%).
- **Midweek Strength**:Best performance occurs on Fridays, with sales 10% higher than the weekly average.
- **Challenges**: Lower visibility and foot traffic due to its alley location impact overall sales performance.

## 6. Visualizations

- **Category Sales**: Bar charts showing revenue distribution across Food, Non-Alcoholic, and Alcoholic categories.
- **Weekly Trends**: Line graphs illustrating peak days for sales.
- **Hourly Performance**: Circular charts highlighting key time windows for customer activity.
- **Forecasting**: Predictive models showing December’s projected sales spike.

## 7. Recommendations

 **For Restaurant 1 **:

- Host premium events leveraging the rooftop location.
- Introduce seasonal menus to capitalize on December sales trends.
- Promote high-margin items like luxury alcoholic beverages.
- Focus marketing efforts on weekends to maximize peak traffic.
- Improve non-alcoholic offerings to diversify revenue.
- Highlight additional extras (e.g., sides, desserts) to increase ticket size.

 **For Restaurant 2 **:

- Improve the alley ambiance with better lighting and signage.
- Offer affordable combo deals to attract budget-conscious customers.
- Launch midweek promotions to capitalize on higher sales during those days.
- Partner with delivery services to offset low foot traffic.
- Promote premium alcoholic products like Don Julio 1942.
- Introduce loyalty programs to encourage repeat visits.

## 8. Conclusions

The analysis confirms that location significantly impacts restaurant performance. Restaurant 1’s premium location drives higher revenue and profitability, while Restaurant 2 faces challenges due to its less favorable setting. However, both restaurants can improve their performance with tailored strategies to address their unique opportunities and challenges.

## 9. Future Work

- Incorporate cost data to calculate profit margins for a more comprehensive analysis.
- Conduct customer surveys to understand preferences and improve menu offerings.
- Use geospatial analysis to identify optimal locations for future restaurants.

## 10. Repository Structure

- dataset.csv: Original dataset provided by the restaurant owners.
- cleaned_dataset.csv: Cleaned and organized dataset.
- visualizations/: Folder containing all generated graphs.
- analysis.ipynb: Jupyter Notebook with the complete analysis.
- README.md: Documentation of the project (this file).
