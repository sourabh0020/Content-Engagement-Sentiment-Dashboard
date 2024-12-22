# Content-Engagement-Sentiment-Dashboard
A Power BI and Excel dashboard for analyzing content engagement and sentiment trends
# Content Engagement and Sentiment Analysis Dashboard

## Overview
This project demonstrates an interactive dashboard for analyzing content engagement and sentiment trends using Excel and Power BI. It provides insights into:
- Sentiment distribution (Positive, Negative, Neutral)
- Reaction types
- Reaction scores by content type and category
- Top 5 content categories by performance

## Features
- **Data Source**: Excel file containing engagement metrics and sentiment analysis.
- **Tools Used**: Excel (PivotTables, charts) and Power BI (slicers, interactive visuals).
- **Key Visualizations**:
  - Sentiment pie chart
  - Reaction-type bar chart
  - Top categories pie chart
  - Time series for reaction scores
  - Interactive slicers for dynamic filtering

## Files
1. `Content_Engagement_Dashboard.xlsx`: The Excel file containing data and dashboard.
2. `Content_Engagement_Dashboard.pbix`: The Power BI dashboard file.
3. `dashboard_screenshot.png`: Screenshot of the final dashboard.
4. `Power_BI_screenshot.png`: Screenshot of the final dashboard.

## Usage
1. Open the Excel file to view raw data and static visualizations.
2. Load the Power BI file for dynamic interaction with the dashboard.
3. Refer to the screenshots for an overview of the visuals.
---
## Problem Statement
In a data-driven world, understanding how users interact with content is critical. The main challenges in this project were:
1. **Unstructured Data**: The dataset contained raw, unprocessed information with multiple inconsistencies.
2. **Sentiment Analysis**: Classifying sentiments (positive, neutral, negative) from reactions and measuring their impact on engagement.
3. **Performance Metrics**: Evaluating content performance by type (Photo, Video, Audio, etc.) and category (Technology, Animals, etc.).
4. **Visualization**: Creating an interactive dashboard that helps stakeholders explore data dynamically and derive insights easily.
---
## Steps Taken
### 1. Data Cleaning in Excel
- **Raw Data**: The initial dataset was unorganized, containing redundant entries, missing values, and inconsistencies.
- **Steps Taken**:
  - Removed duplicates and irrelevant rows.
  - Standardized reaction types (e.g., "love" and "Love" were merged).
  - Filled missing values with appropriate measures (e.g., sum of sentiment scores).
- **Result**: A clean, structured dataset ready for analysis.
---
### 2. Data Analysis in Excel
- **Pivot Tables**: Used pivot tables to summarize the data:
  - Count of unique reactions by type.
  - Sum of reaction scores by sentiment and category.
- **Charts**:
  - A clustered column is used  to show the count of reactions.
  - Pie charts for category-based sentiment distribution.
- **Result**: Basic insights into sentiment distribution and content performance.
---
### 3. Interactive Dashboard in Power BI
- **Data Integration**: I uploaded the cleaned data to Power BI for advanced visualizations.
- **Visuals Created**:
  - pie charts are used to show the top 5 content caategory.
  - Line graphs to analyze trends in content category.
  - Pie charts for sentiment-wise distributions.
  - Slicers for dynamic filtering by reaction sentiment.
  - Clustered bar chart for comparing the reaction type(e.g,adore,want,cherish etc)
- **Interactivity**:
  - Enabled users to filter data dynamically.
  - Added tooltips for detailed insights on hover.
- **Result**: A fully interactive and user-friendly dashboard.
---
## Results and Insights
1. **Key Findings**:
   - **Sentiment Breakdown**: 56% of reactions were positive, 31% neutral, and 13% negative.
   - **Top Content Types**: Animals and Science generated the highest reaction scores.
2. **Impact**:
   - Identified content categories and types with high user engagement.
   - Helped in understanding audience sentiment and preferences for future content strategies.
---
## Files Included
- **Excel File**: `Content_Engagement_Dashboard.xlsx`
  - Contains the cleaned dataset, pivot tables, and static visualizations.
- **Power BI File**: `Content_Engagement_Dashboard.pbix`
  - Interactive dashboard with visuals and slicers.
- **Dashboard Screenshot**: `dashboard_screenshot.png`
  - A preview of Excel dashboard.
- **Power_BI_Screenshot**: `dashboard_screenshot.png`
  - A preview of the Power BI dashboard.
---
## Usage Instructions
1. Open the **Excel File** to view raw data, summaries, and static charts.
2. Load the **Power BI File** for interactive exploration:
   - Use  dropdown slicers and treemap to filter data dynamically (e.g., by sentiment or content type).
   - Hover over visuals for detailed insights.
3. Refer to the **Screenshot** for an example of the final dashboard.
---
## Tools Used
- **Microsoft Excel**:
  - Data cleaning, pivot tables, and static visualizations.
- **Power BI**:
  - Advanced analytics and interactive visualizations.
