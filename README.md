Bike Sales SQL Analysis

Overview

This project provides an in-depth SQL-based analysis of bike sales trends, pricing strategies, and resale insights. The goal is to help businesses and consumers make informed decisions by leveraging data-driven insights.

Objectives & Business Impact

Analyze bike sales trends to identify market patterns.

Evaluate brand-wise pricing to determine the most expensive and affordable models.

Assess resale value insights to understand depreciation rates.

Identify factors influencing bike prices and their impact on sales.

Provide data-driven recommendations for buyers and businesses.

SQL Techniques Used

Window Functions (RANK(), ROW_NUMBER(), DENSE_RANK())

Common Table Expressions (CTEs) for structured analysis

Subqueries for filtering and trend detection

Aggregations & Grouping for business-level insights

Data Description

Table Schema:

Column Name

Data Type

Description

brand

Text

Motorcycle brand (e.g., Yamaha, Honda, Bajaj, etc.).

avg_original_price

Numeric

Average original purchase price of the bike before resale.

avg_resale_price

Numeric

Average resale price of the bike in the second-hand market.

resale_value_percentage

Numeric

Percentage of the original price retained during resale.

mileage_category

Text

Categorizes bikes based on mileage (Low, Medium, High).

fuel_type

Text

Fuel type of the bike (Petrol, Hybrid, Electric).

total_sales

BigInt

Total number of units sold for a given category.

insurance_status

Text

Insurance status (Active, Expired, Not Available).

owner_type

Text

Specifies whether the bike is First, Second, or Third-hand.

year_of_manufacture

Integer

Year in which the bike was manufactured.

Key Insights

1. Bike Sales Trends (2015-2024)

Fluctuations in total bike manufacturing over the years.

Decline observed from 2015-2018, followed by a recovery.

Highest production: 2015 (1,046 units) & 2023 (1,009 units).

Steady increase in production from 2022-2024, indicating market recovery.

2. Brand-Wise Price Analysis

Some brands have higher original prices, positioning them as premium choices.

Resale value percentage varies across brands, affecting second-hand market pricing.

3. Resale Market Insights

First-hand bikes retain higher resale prices.

Higher mileage models tend to have better resale value.

4. Engine Capacity vs. Average Distance Travelled

No direct correlation between engine capacity and distance traveled.

Other factors like riding habits, road conditions, and fuel efficiency may impact travel distance.

5. Fuel Type vs. Total Sales

Petrol bikes dominate, but hybrid & electric models are emerging.

Increasing demand for eco-friendly bikes suggests a future market shift.

6. Impact of Insurance on Resale Price

Bikes with active insurance fetch higher resale prices.

Uninsured or expired insurance bikes have lower resale value, showing buyer preference for secured purchases.

Final Business Recommendations

1. Increase Production to Meet Growing Demand

Data shows a recovery in bike production post-2022.

Continue scaling up production to match rising demand in 2024 and beyond.

2. Focus on Brands with Higher Resale Value

Promote brands that retain high resale value, as second-hand buyers prefer them.

Implement marketing campaigns emphasizing "Best Resale Value" models.

3. Expand into Electric and Hybrid Bikes

Though petrol bikes lead in sales, electric & hybrid models are gaining traction.

Invest in R&D and marketing for eco-friendly models to align with market trends.

4. Introduce Extended Warranty & Insurance Packages

Since insurance status impacts resale value, offer extended warranty & insurance renewal packages.

Provide bundled deals to increase buyer confidence and improve resale value.

5. Optimize Pricing Strategy

Offer affordable pricing for budget buyers while maintaining premium models.

Introduce seasonal discounts or financing options to boost sales.

6. Leverage the Second-Hand Market

Develop a certified pre-owned (CPO) program to increase trust in used bike sales.

Establish partnerships with resale platforms to enhance second-hand bike trade.

Conclusion

This analysis highlights that the bike industry is recovering, and consumer preferences are shifting toward eco-friendly options, insured bikes, and high-resale-value brands. Businesses should focus on scaling production, optimizing pricing, and expanding into electric & hybrid models to sustain long-term growth.
