# Global-Product-Trends-and-Inventory-Analysis
[Introduction](#Introduction)

[Objective](#Objective)

[Story of Data](#StoryofData)

[Data Splitting and Preprocessing](#DataSplittingandPreprocessing)

[Pre-Analysis](#Pre-Analysi)

[In-Analysis](#In-Analysis)

[Post-Analysis and Insights](#Post-AnalysisandInsights)

[Data Visualizations & Charts](#DataVisualizations&Charts)

[Recommendations and Observations](#RecommendationsandObservations)

[Conclusion](#Conclusion)

[References & Appendices](#References&Appendices)

## Introduction

This report presents a comprehensive analysis of global product trends and inventory performance for the year 2023. Using Microsoft Excel, the study investigates how product categories,
pricing, customer ratings, stock quantity, and other factors influence business outcomes. The analysis aims to help stakeholders make data-driven decisions to improve product strategies, optimize inventory, and enhance customer satisfaction.

### Objective of the Project

This project aims to evaluate and understand global product performance trends in 2023 using Microsoft Excel. The objective is to identify how product categories, pricing, customer 
ratings, inventory levels, and other variables such as color, size, and warranty period influence business performance.

### Problem Being Addressed

Businesses often face challenges in determining which product lines drive the highest returns and customer satisfaction. This analysis seeks to:

* Which product categories get the best customer reviews?
  
* Which product categories are the most expensive?
  
* Are higher-rated products more expensive?

* Does a longer warranty increase price?
  
* Do certain colors or sizes get higher ratings?
  
* Are newer products getting better reviews?

* Which specific products are the most expensive?
  
* Does stock quantity impact product rating?
  
* Is there any correlation between the number of tags and product rating?


1.3 Key Datasets and Methodologies
The analysis uses sales and inventory data from internal systems. Key Excel tools and functions include:

Pivot Tables for summarization.

Statistical functions such as SUMIF, COUNTIF, SUMIFS, COUNTIFS.

CONCATENATE and SUBSTITUTE for text processing.

Dashboards and visualization tools like bar charts, pie charts, and column graphs.

2. Story of Data
2.1 Data Source
The dataset was collected from the company’s internal retail and product management system, capturing data from various global regions.

2.2 Data Collection Process
The data was logged using automated tools integrated into point-of-sale and warehouse management systems, supplemented by monthly updates from regional offices.

2.3 Data Structure
Rows: Each row represents a unique product.

Columns: Include fields such as Category, Product Name, Price, Rating, Stock Quantity, Warranty Period, Size, Color, and Month of review or sale.

2.4 Important Features
Product Category: Classifies items (Clothing, Electronics, Home Appliances).

Price: Reflects consumer value and business positioning.

Rating: Indicates customer satisfaction.

Color/Size: Consumer preference indicator.

Warranty: May influence perceived value.

Stock Quantity: Inventory availability.

2.5 Data Limitations
Limited granularity on regional sales.

Some missing values in warranty and ratings.

Monthly data available for only three months.

3. Data Splitting and Preprocessing
3.1 Data Cleaning
Removed duplicates and null values.

Standardized format for colors and product names.

3.2 Handling Missing Values
Used average imputation for missing ratings and warranty fields to maintain integrity without deleting records.

3.3 Data Transformations
Created new fields such as “Price by Rating” and “Average Rating by Category”.

Used SUBSTITUTE to clean textual inconsistencies.

Used CONCATENATE for combining size and color for composite analysis.

3.4 Data Splitting
Dependent variables: Price, Rating.

Independent variables: Category, Stock, Warranty, Month, Color/Size.

3.5 Industry Context and Stakeholders
Industry: Retail and Consumer Goods.

Stakeholders: Sales team, Inventory Managers, Product Developers, Marketing Department.

4. Pre-Analysis
4.1 Key Trends Identified
Home Appliances are the highest priced category on average ($258.8).

Clothing holds the best average product rating (3.02).

Blue/Medium sized products receive the best feedback (3.015 rating).

4.2 Potential Correlations
Products with a higher stock range (81–100) are generally rated better.

Longer warranties are associated with slightly higher prices.

4.3 Initial Insights
Ratings peak in March, suggesting potential seasonal or campaign influence.

Electronics are competitive in pricing but fall behind in customer satisfaction.

5. In-Analysis
5.1 Unconfirmed Insights
High-priced products may drive customer expectations and lower ratings unless supported by warranty and quality.

Some variations like Red/Small also perform well, suggesting size and color influence perception.

5.2 Recommendations
Increase inventory for best-performing variants (e.g., Blue/Medium clothing).

Bundle extended warranties with electronics to improve perceived value.

Monitor high-price items (e.g., monitors) for return rates and satisfaction trends.

5.3 Excel Techniques Used
Pivot Tables: Summarizing average prices and ratings.

Formulas:

=SUMIF(Category, "Clothing", Price)

=COUNTIFS(Rating, ">3", Warranty, ">1")

=SUBSTITUTE(Product, " ", "_")

=CONCATENATE(Color, "/", Size)

6. Post-Analysis and Insights
6.1 Key Findings
Best-reviewed category: Clothing (3.02 rating).

Highest average price: Home Appliances ($258.8).

Most expensive product: Monitor ($259.12).

Top-rated variation: Blue/Medium (3.015).

Best month: March (3.048 average rating).

6.2 Comparison with Initial Findings
Initial expectations suggested Electronics might dominate. However, Clothing products outperformed others in customer satisfaction despite lower pricing.

7. Data Visualizations & Charts
7.1 Visuals Included
Bar Charts: Price by category, product rating by stock, color/size ratings.

Pie Chart: Average rating by category.

Column Charts: Price by warranty, rating by month.

Dashboard Highlights: Key indicators and best-performing segments.

7.2 Explanation of Visualizations
Each visual offers quick insights:

Clothing’s consistent performance is seen across price, rating, and warranty data.

Inventory levels strongly correlate with better product reviews.

8. Recommendations and Observations
8.1 Actionable Insights
Increase production of high-rated combinations (Clothing, Blue/Medium).

Reprice underperforming products in the Electronics category.

Reassess stock levels for low-rated products with high inventory.

8.2 Optimizations
Shift marketing spend toward best-rated months and categories.

Extend warranty coverage on mid-tier products to raise perceived value.

8.3 Unexpected Outcomes
March performed exceptionally well across all categories; requires further investigation into marketing actions during that period.

9. Conclusion
9.1 Key Learnings
Product attributes like size, color, and warranty period significantly affect customer satisfaction.

Clothing products offer the best balance between affordability and customer rating.

9.2 Limitations
Limited time span of analysis (3 months).

Dataset does not include geographic segmentation or returns data.

9.3 Future Research
Explore integration of customer sentiment (reviews).

Analyze year-over-year performance for long-term trends.

Incorporate sales volume for deeper profitability insights.

10. References & Appendices
References
Internal Sales and Inventory Systems

Microsoft Excel Documentation

Product Management Records

Appendices
Appendix A: Full Pivot Table Output

Appendix B: Excel Formulas Used

Appendix C: Raw Dataset (sanitized)

Appendix D: Screenshot of Final Dashboard
