**1. Project Title:**

Uber vs Lyft Price and Performance Comparison

**2. Executive Summary:**

**Objective:**
The primary goal of this project is to compare the fare structures and performance metrics of Uber and Lyft across different service categories, locations, and contextual factors such as weather. By analyzing ride-hailing data, we aim to uncover patterns and provide actionable insights into the dynamics between these two leading ride-hailing services.

**Context:**
This analysis was performed using a dataset that includes ride prices, distances, ride durations, and weather conditions for various locations. Tools used include Tableau for visualization, Excel for data preprocessing, and machine learning models for prediction.

**3. Business Problem:**

**Problem Identification:**
Uber and Lyft are competitors in the ride-hailing industry. Both companies aim to optimize pricing strategies, increase market share, and enhance customer satisfaction. The challenge is to analyze key factors that influence ride prices and performance across different services and locations to guide pricing strategy and market positioning.

**Business Impact:**
Optimizing pricing and service offerings could significantly impact customer satisfaction and market competitiveness. Insights from this analysis will help both companies make informed decisions regarding fare adjustments, surge pricing strategies, and market expansion plans.

**4. Methodology:**

**Data Cleaning & Transformation:**

**Handling Missing Data:** Missing values in price and rain data were addressed using the median for price (since the data is skewed) and the mode for rain data.
Logarithmic Transformation: The price data was extremely skewed, so logarithmic transformation was applied to normalize the distribution.
Outlier Removal: Outliers were identified and clipped using the empirical rule on the price column.
Analysis Techniques:

**Descriptive Analysis:** Mean, median, and variance analysis was used to understand the basic distribution of ride prices across both services.
ANOVA Tests: Used to compare ride prices between Lyft and Uber across various categories (e.g., cab type, destination, source).
Regression Models: Decision forest regression and linear regression models were used to predict ride prices based on key features such as distance, weather, and surge multipliers.

**5. Skills:**

**Tools, Languages, & Software:**

**Tableau:** For interactive data visualizations comparing Uber and Lyft.
**Excel:** For data preprocessing, basic analysis, and handling missing values.
**Machine Learning:** Applied models including Decision Forest Regression, Boosted Decision Trees, and Neural Networks to predict pricing based on various features.

**6. Results & Business Recommendation:**

**Business Impact:**
**The analysis revealed key differences between Uber and Lyft:**

**Higher Prices for Lyft:** Lyft rides tend to be more expensive on average compared to Uber, particularly in premium categories such as Lyft Lux.
**Dynamic Pricing:** Uber’s prices are generally more consistent, while Lyft shows greater variability in pricing, influenced by higher surge multipliers.
**Geographical Variation:** Certain regions such as Boston University and Fenway have higher ride prices, indicating these are areas where demand is higher, especially for premium rides.

**Insights:**

**Lyft Premium Services:** Lyft’s premium services (e.g., Lux and Lux SUV) have significantly higher prices compared to Uber’s offerings. This presents an opportunity for Lyft to target high-end consumers more effectively.
**Surge Pricing Strategies:** Uber’s surge pricing strategy is more predictable, whereas Lyft’s prices vary widely. Lyft could potentially optimize its surge multiplier to strike a balance between profitability and customer satisfaction.
**Weather Influence:** Weather factors such as rain and temperature have a statistically significant effect on ride prices, especially for Lyft.

**7. Next Steps:**

**Future Work:**

**Enhancing Predictive Models:** Explore advanced predictive modeling techniques, such as ensemble learning, to improve the accuracy of price predictions.
**Traffic & Time Context:** Incorporate additional contextual data such as traffic conditions and time of day to further refine price predictions.
**Service Optimization:** Both companies could optimize service availability in high-demand regions to maximize revenue and improve customer satisfaction.
**Surge Pricing Optimization:** Lyft may benefit from adjusting its surge multiplier policies to increase revenue while maintaining customer loyalty.
