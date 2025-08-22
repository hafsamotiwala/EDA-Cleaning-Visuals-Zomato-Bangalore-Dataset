# EDA-Cleaning-Visuals-Zomato-Bangalore-Dataset
This project involves Zomato Bangalore restaurant data analyzed. It includes data cleaning, EDA with stats & visuals (histograms, bar charts) on ratings, cuisines, pricing. Key findings in Markdowns

SUMMARY of Zomato Bangalore Restaurants Analysis: Key Findings and Business Recommendations
After conducting a thorough exploratory data analysis (EDA) on the Zomato Bangalore Restaurants Dataset (43,854 records), we’ve transformed raw data into actionable insights using Pandas, NumPy, Matplotlib, and Seaborn in a Colab notebook. Starting with data cleaning—converting "3.5/5" ratings to numeric values and handling 7,775 missing entries—we’ve uncovered trends to guide Zomato’s strategy.

Key Observations:

Univariate Trends: Ratings average 3.5-4.0, with costs mostly at 300-500 INR (max 6,000 INR). Online orders are adopted by 64.4% of restaurants, while table bookings remain at ~20%.

Bivariate Insights: Votes show a moderate positive correlation (0.43) with ratings, indicating popularity drives feedback. Cost has a weak positive link (0.38) with ratings, and online orders/bookings improve consistency (e.g., 4.0 median for bookings).

Multivariate Results: North Indian, Chinese, and South Indian are top cuisines; Casual Dining and Quick Bites lead types. Hotspots include BTM, Koramangala, and Hsrr. Cantonese stands out with high ratings (~4.5) and costs (>2,000 INR).

Correlation Findings: A heatmap confirms a moderate votes-rating correlation (0.43) and weak cost-related links (0.37-0.38), prioritizing engagement over pricing.

Business Questions & Answers:

Most Popular Cuisines: North Indian, Chinese, and South Indian dominate, reflecting strong local and diverse demand.

Hotspot Locations: BTM, Koramangala, and Hsr are high-density areas ideal for targeting.

High-Cost Ratings: Not guaranteed—high-cost restaurants trend slightly higher, but budget options (300-500 INR) often reach 4.0+, emphasizing quality over price.

Online Order/Book Table Impact: Both positively influence ratings—online orders enhance consistency, while table bookings lift medians to ~4.0.

Optimal New Restaurant Location: Recommend Koramangala or Hsr with North Indian or Cantonese cuisine at 400-800 INR, incorporating online orders and table bookings for maximum success.

Recommendations for Zomato:

Feature Adoption: Incentivize online ordering and table bookings (e.g., featured listings) to improve ratings and customer reach.

Engagement Boost: Encourage reviews to leverage the votes-rating correlation, increasing visibility for underperforming restaurants.

Segment Focus: Promote Cantonese for premium customers and budget options in hotspots to broaden market appeal.

Algorithm Adjustment: Prioritize high-vote restaurants in recommendations to balance popular and emerging spots.

Tools Used:
Pandas: Data cleaning and manipulation.
NumPy: Statistical analysis.
Matplotlib/Seaborn: Visualizations with orange-blue themes (histograms, scatters, pies) and custom heatmaps.
