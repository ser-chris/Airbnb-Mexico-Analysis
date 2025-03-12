# Airbnb Data Analysis for Mexico

## 1. Background and Overview

**Context:**

The short-term rental market in Mexico is experiencing significant growth, offering lucrative opportunities for Airbnb investors. However, choosing the right city and property type can be a complex task. This project aims to provide data-driven insights to help individual investors make informed decisions in this competitive market.

**Objective:**

This analysis focuses on identifying key factors for successful Airbnb investments in Mexico. The specific goals are:

1.  **Identify the Most Profitable Cities:** By analyzing revenue performance across different regions, we aim to pinpoint the cities that offer the best returns for Airbnb investors.
2.  **Rank Property Types by Revenue Potential:** Help investors understand which types of listings generate the highest returns in specific locations.
3.  **Evaluate Pricing Strategies:** To optimize earnings, considering factors like nightly rates, fees, and location-based performance.

## 2. Data Structure Overview

**Geographic Coverage:**

The dataset includes Airbnb listings from various cities across Mexico, though it does not encompass all available properties. This limits the analysis to a subset of the market.

**Time Frame:**

The data begins from March 2025 onwards, capturing the most recent market trends for short-term rentals in Mexico.

**Available Features:**

* **Location Data:** Information on city, latitude, and longitude, allowing for geographic performance analysis.
* **Pricing Information:** Data on nightly rates, fees, and discounts associated with each listing.
* **Property Type:** The type or category of rental unit, enabling an analysis of how different property types perform.

**Limitations:**

* **Lack of Occupancy Data:** The dataset does not include occupancy rates, so demand is approximated using review counts. This may not fully capture actual demand.
* **Absence of Seasonal Data:** Without seasonality data, trends may not account for fluctuations due to holidays or travel seasons.
* **Limited Property Details:** Missing information like number of rooms, bathrooms, and amenities reduces the depth of analysis and prediction accuracy.

## 3. Executive Summary

This analysis provides a comprehensive examination of the Airbnb market in Mexico, offering insights into profitability and performance across various cities and property types. An [interactive Tableau dashboard](https://public.tableau.com/app/profile/christian.verdugo1554/viz/AirbnbPriceInsightsAcrossMexico/Dashboard2) provides visual insights into city-specific KPIs and property type performance. The focus is on understanding how factors like location, pricing, fees, and discounts impact earnings. Our findings show that:

![Dashboard SS](https://github.com/user-attachments/assets/ccada154-ea64-433b-b245-9bec73547826)

* Nightly Rates and Gross Price are the most significant drivers of Estimated Monthly Earnings, indicating the importance of competitive pricing.
* Certain cities, like Tulum and Brisas De Zicatela, offer the highest returns on investment, driven by both pricing and property type.
* Fees, including Fee Total and Fee Airbnb, are correlated with higher earnings, but their impact is secondary to pricing factors.
* Discounting and ratings have minimal influence on earnings, suggesting that focusing on competitive pricing is the most effective strategy.

## 4. Insights Deep Dive

**Profitability Analysis by City:**

* Cities like Tulum, Brisas De Zicatela, and El Pescadero are top performers, with high revenue potential across various property types.
* Hotel, Loft, and Place properties consistently underperform, indicating that they may be less competitive in terms of profitability.
* The lack of occupancy data limits our ability to fully gauge demand, but review counts serve as a proxy for demand levels.

**Pricing Strategy Impact:**

* Nightly Rates and Gross Price are highly correlated with monthly earnings. Properties with higher pricing perform better in terms of revenue generation.
* The relationship between fees and earnings, though positive, is less significant than that of pricing. This suggests that, while Airbnb’s fees do influence profitability, pricing remains the key factor in earnings.

**Fees, Discounts, and Reviews:**

* Discount Amount and Ratings show negligible correlations with earnings. Discounting and high ratings do not appear to significantly affect profitability.
* Reviews show a weak negative correlation, but it does not offer predictive value in terms of earnings.

## 5. Recommendations

1.  **Focus on Competitive Pricing:** Investors should prioritize setting higher nightly rates and gross prices, as these factors are the strongest predictors of profitability.
2.  **Optimize Property Type Selection:** Home, Apartment, and Guesthouse properties are the most profitable. Consider investing in these types for higher returns.
3.  **Minimize Discounting:** Given that discounts show no significant correlation with earnings, investors should avoid heavily discounting properties unless necessary to remain competitive in specific markets.
4.  **Monitor Fees and Gross Prices:** While fees do have a moderate positive correlation with earnings, the main focus should remain on setting competitive and premium pricing for optimal returns.

