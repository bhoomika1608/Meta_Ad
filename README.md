# Meta_Ad
🚀 Project Overview

This dashboard provides a 360° view of Meta ad campaigns using detailed event-level data. It helps identify the most effective platforms, audience segments, ad formats, and time periods for better marketing ROI.
The dataset includes campaigns, ad creatives, demographic information, and user interaction logs — structured using a star schema (fact + dimensions).


📁 Dataset Description
The dataset consists of four tables:
1. ad_events – Fact table containing impressions, clicks, comments, shares, and purchases.
2. ads – Ad metadata: platform (FB/IG), creative type (image/video/carousel/story), targeting info.
3. campaigns – Campaign-level budget, duration, and strategy.
4. users – User demographics: gender, age, country, location, interests.


📌 Key KPIs Included
From the BRD & dashboard:
- Impressions – Total times the ads were displayed
- Clicks – User interactions
- Shares / Comments – Organic engagement
- Purchases – Total conversions
- CTR (Click-Through Rate)
- Engagement Rate
- Conversion Rate
- Purchase Rate
- Total Budget
- Average Budget per Campaign


📊 Dashboard Features
1. Overview KPI Cards
Displays key performance metrics such as Impressions, Clicks, CTR, Engagement Rate, Purchases, Budget, etc.

2. Purchases by Gender (Donut Chart)
Shows gender-based contribution to purchases and engagement.

3. Purchases by Age (Bar Chart)
Identifies the most responsive age groups (18–30 is the highest).

4. Purchases by Country (Map)
Geographic view of conversions and engagement across major markets.

5. Calendar Heatmap (Month-wise Analysis)
Reveals high-performance days and seasonal peaks.

6. Weekly Purchases Trend (Stacked Bar)
Breaks down weekly activity by ad type.

7. Hourly Purchases Trend (Line Chart)
Highlights the most active hours of user engagement.

8. Analysis by Ad Type (Matrix Table)
Compares Impressions, Clicks, CTR, Purchase Rate, Conversion Rate, and Engagement Rate across creative formats.

9. Dynamic Filters
- Platform (Facebook / Instagram)
- Measure Selection (Purchases, Impressions, Clicks, etc.)
- Campaign Name
- Target Interests


🔧 Tech Stack
1. Power BI (Visualizations & DAX)
2. SQL (Data integration & transformation)
3. MS Excel (Data cleaning & preprocessing)
4. Star Schema Modeling (Fact + Dimensions)


📈 Key Insights From the Dashboard
1. Ads have high CTR (11.86%) and strong engagement rate (13.6%), indicating attractive and effective creatives.
2. Purchase Rate is low (0.57%), showing a weak conversion funnel that needs optimization.
3. Females aged 18–30 show the highest engagement and purchase activity — primary target segment.
4. Video and Story ads outperform other formats in CTR, Engagement Rate, and Conversion Rate.
5. Engagement peaks during afternoons and evenings, suggesting optimal ad scheduling windows.
6. India, US, and Brazil are major contributors — ideal regions for scaling campaigns.

📥 How to Use This Dashboard
1. Download the .pbix file (if shared).
2. Open in Power BI Desktop.
3. Use slicers to filter by platform, campaign, and measure.
4. Explore trends across demographics, geography, and ad formats.
5. Use insights to optimize targeting, budgeting, and creative strategy.

📸 Dashboard Preview
https://github.com/bhoomika1608/Meta_Ad/blob/main/Screenshot%202025-12-08%20220146.png

📝 Conclusion

This dashboard acts as a complete performance monitoring and optimization tool for Meta ad campaigns, supporting strategic decisions through clean visualizations, meaningful KPIs, and actionable insights.
