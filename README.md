# Twitter Analytics Dashboard

This project involves creating an interactive Twitter Analytics Dashboard using Power BI. The dashboard provides insights into key performance metrics, such as engagement rates, media interactions, and impressions, using dynamic filters and Power Query for preprocessing.

## Features

1. **Average Engagement Rate and Total Impressions (Jan-Jun 2020, 3-5 PM IST):**
   - Displays the average engagement rate and total impressions for tweets posted between January and June 2020.
   - Filters out tweets with fewer than 100 impressions and 0 likes.
   - Time-specific focus: Tweets posted between 3 PM and 5 PM IST.

2. **Media Engagements vs. Media Views (12-6 PM, Odd Dates):**
   - Scatter chart showing the relationship between media engagements and views for tweets with more than 10 replies.
   - Highlights tweets with an engagement rate above 5%.
   - Filters include odd dates and word count < 50.

3. **Comparison of Replies, Retweets, and Likes (Jun-Aug 2020, 3-6 PM):**
   - Visualizes replies, retweets, and likes for tweets with media engagements greater than the median value.
   - Filters for tweets posted between June and August 2020, with odd tweet dates, even media views, and word count < 50.
   - Time-specific focus: Tweets posted between 3 PM and 6 PM IST.

## Dashboard Overview

The dashboard includes the following key elements:
- **Key Performance Indicators (KPIs):**
  - Media Views, Impressions, Engagement Rate, and Tweet Count.
- **Dynamic Visualizations:**
  - Bar charts and scatter plots for analyzing tweet performance.
- **Filters:**
  - Filters were applied through **Power Query** and the filter pane in Power BI to streamline data processing and visualization.

## Data Source

The dataset used for this project was obtained from [Data World](https://data.world/), specifically focusing on Twitter analytics and social media engagement data. The dataset provides information on tweet impressions, likes, retweets, replies, media views, and more, along with timestamps and metadata for filtering.

## How to Use the Dashboard

1. Open the Power BI file.
2. Use the dynamic filters in the filter pane to adjust the date range, time frame, and other parameters.
3. Analyze insights using bar and scatter charts.
4. Focus on specific metrics or trends as needed.

## Areas for Improvement

While the dashboard effectively highlights key metrics, some visualizations may need refinement or removal. Consider:
1. **Impressions by Week** - Ensure it's aligned with key objectives.
2. **Tweet Count by Week** - Check for overlap with other time-based charts.
3. Streamlining charts to remove redundancy and improve clarity.

## Tools and Technologies

- **Power BI**: For building visualizations and dynamic dashboards.
- **Power Query**: For data cleaning and transformation.
- **Data Source**: Twitter analytics data from Data World.

## Next Steps

- Refine the layout for better clarity and user experience.
- Add drill-through pages or advanced filters for deeper insights.
- Integrate additional metrics or external data sources.

---
**Author**: Srija Majumdar  
**Contact**: https://www.linkedin.com/in/srija-majumdar-a686772a2
