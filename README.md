# British Airlines Data Analysis Dashboard

## Overview
This project focuses on analyzing British Airlines data using Tableau. The dashboard provides insights into the airline's service ratings and trends based on different dimensions and metrics.

### Key Features:
- **Interactive Map**: Displays the Average Rating of a selected service by country.
- **Filters**: Users can filter data by:
  - Month of Date
  - Traveller Type
  - Seat Type
  - Continent
  - Aircraft
- **Graphs**:
  - Average Rating of a selected service by Month
  - Average Rating of a selected service by Aircraft
- **Dashboard**: Combines all visualizations to provide a holistic view of the data.

### Tableau Public Link:
Access the dashboard [here](https://public.tableau.com/views/BritishAirlinesAnalysis/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

## Data Source
The analysis is based on two datasets:
1. **Countries Data** (`countries.xlsx`): Contains information about countries and their respective attributes.
2. **British Airlines Reviews** (`ba_reviews.xlsx`): Includes customer ratings for various services provided by British Airlines.

### Data Connection
The datasets were joined in Tableau on the following columns:
- **Countries Data**: `Country`
- **British Airlines Reviews**: `Place`

## Parameters and Filters
### Parameters:
- The dashboard allows users to select a metric for analysis from the following options:
  1. Overall Rating
  2. Food & Beverage
  3. Entertainment
  4. Seat Comfort
  5. Value for Money
  6. Ground Service
  7. Cabin Staff Service

### Filters:
- Month of Date
- Traveller Type
- Seat Type
- Continent
- Aircraft

## Visualizations
1. **Average Rating of [Selected Metric] Service by Country**:
   - Interactive map showing service ratings geographically.
2. **Average Rating of [Selected Metric] by Month**:
   - Trend line displaying ratings over time.
3. **Average Rating of [Selected Metric] by Aircraft**:
   - Bar chart showing ratings categorized by aircraft type.

## Dashboard Preview

![Dashboard Preview](./British%20Airlines%20Dashboard%20Preview.png)


## Repository Structure
```plaintext
- countries.xlsx        # Dataset containing country-level information
- ba_reviews.xlsx       # Dataset with reviews and ratings
- README.md             # This documentation file
