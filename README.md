# Boston Bluebike Analysis
This is a course project which we leveraged SQL, Tableau, and Python to analyze Bluebike riding patterns and the relationship between rides and weather.

Course Info: BA775 (2025fall) Analytics Toolbox, Mater of Business Analytics, Boston University

Group Member: Grace Kung, Vishesh Goyal, Mokhinur Talibzhanova, Anton Falk, Emily Su

## Project Overview
This project analyzes how hourly weather conditions influence Bluebikes usage across Boston from January through September 2025. After cleaning and unifying both trip-level and weather data, we examined trends across stations, rider types, and extreme weather scenarios to identify which conditions most strongly shape demand.

The analysis shows clear patterns: commuter-heavy stations around MIT and Central Square stay busy in all weather, weekend ridership shifts heavily toward casual users, and rain or cold reduces demand far more than heat. By isolating which stations are resilient versus weather-sensitive, we highlight where rebalancing pressure is most likely to occur during storms or winter cold snaps. These insights support more accurate demand forecasting and more efficient operational planning, helping Bluebikes maintain consistent bike availability while reducing the risk of stations becoming empty or full.

## Data Source
1. The first dataset comes from the official Bluebikes System Data, which provides detailed trip-level information for the Boston metropolitan bikeshare network. We combined nine monthly CSV files covering January 1 through September 30, 2025, resulting in a unified dataset of 3,568,121 rows × 13 columns (~855 MB). Each file contains trip-level observations including timestamps, station locations, bike type, rider type, and geographic location.
The data is publicly available at: [Bluebikes Datasets](https://bluebikes.com/system-data)
2. The second dataset contains daily Boston weather observations for the same period. This dataset includes maximum/minimum temperature, precipitation, wind speed, snowfall, and other atmospheric conditions. It consists of 273 rows × 33 columns (~84 KB). The cleaned data is hosted in our BigQuery environment, and originates from publicly available weather records. The data is publicly available at: [Weather Dataset](https://www.visualcrossing.com/weather-query-builder/)

### ERD
<img width="1500" height="956" alt="Database ER diagram (crow&#39;s foot) (1)" src="https://github.com/user-attachments/assets/e1ed7c87-693c-4715-bf6a-3e6638a3d31f" />

## Dashboard
<img width="1919" height="1027" alt="螢幕擷取畫面 2025-12-09 093941" src="https://github.com/user-attachments/assets/fea602c5-e710-4da1-9b98-d910ade1dc5f" />
<img width="1919" height="1040" alt="螢幕擷取畫面 2025-12-09 094037" src="https://github.com/user-attachments/assets/c9cbbfb0-0893-452b-8183-facf6bfdc4cc" />
