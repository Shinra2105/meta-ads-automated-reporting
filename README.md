**Meta Ads to Google Sheets Automated Reporter**

Description: Automated reporting pipeline that runs on a schedule (every 6 hours) to extract performance metrics from Meta Ads.

Key Features:

Graph API Integration: Recursive fetching of Campaigns -> AdSets -> Insights.

JavaScript Data Transformation: A complex Code Node calculates custom KPIs not available natively, such as "Cost per Result" based on dynamic optimization goals (ThruPlay, Reach, Conversions).

Data Warehousing: Appends cleaned and formatted data into Google Sheets for visualization in Looker Studio.
