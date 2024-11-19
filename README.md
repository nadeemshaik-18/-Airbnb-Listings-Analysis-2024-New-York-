# Airbnb Listings Analysis 2024 (New York)

## Objective
The primary goals of this project are to:
- Analyze room types, prices, and availability across different neighborhoods.
- Understand host behavior and patterns in listing characteristics.
- Identify price outliers and unusual trends.
- Provide actionable insights for both guests and hosts.

## Dataset
The dataset contains information about Airbnb listings in New York, including the following features:
- **Neighborhood Group**: Borough where the listing is located.
- **Room Type**: Type of accommodation (e.g., entire home, private room).
- **Price**: Nightly rental price.
- **Availability_365**: Number of days a listing is available in a year.
- **Reviews Per Month**: Average number of reviews received monthly.
- **Host Listings Count**: Total number of listings managed by a host.

## Workflow and Steps

### 1. Data Cleaning
- Handled missing values in key columns like price and reviews.
- Converted date columns to appropriate formats for analysis.
- Capped extreme values in price to mitigate skewed distributions.

### 2. Exploratory Data Analysis (EDA)
- **Room Type Analysis**: Visualized room type distributions and identified trends in booking preferences.
- **Neighborhood Insights**: Explored price variations across boroughs, with Manhattan emerging as the costliest area.
- **Price Distribution**: Analyzed price ranges, highlighting affordability patterns.
- **Availability Trends**: Used heatmaps and pair plots to examine correlations between availability, reviews, and prices.

### 3. Data Visualization
- **Bar Charts**: Highlighted room type and neighborhood group distributions.
- **Histograms**: Displayed price distributions to identify common ranges.
- **Heatmaps**: Showed correlations among numerical features.
- **Pair Plots**: Visualized relationships between reviews, price, and availability.

## Key Findings and Insights
- **Price Trends**: Manhattan listings have the highest average prices, with entire homes costing more than private rooms.
- **Room Type Distribution**: Entire homes/apartments dominate the market, offering premium experiences. Private rooms provide budget-friendly options.
- **Host Behavior**: Some hosts manage multiple listings, indicating a trend toward professional hosting.
- **Outliers**: Listings priced above $1,000 per night were detected, suggesting the need for filtering in future analyses.

## Recommendations
### For Guests:
- Opt for private rooms in Brooklyn for affordable stays with good amenities.
- Choose listings with high availability and favorable reviews for a better experience.

### For Hosts:
- Increase availability and improve responsiveness to reviews to attract more bookings.
- Analyze local pricing trends to stay competitive within your neighborhood.

## How to Run the Project
1. Clone the repository:  
```bash
git clone <repository-link>
```
2. Install the required libraries:  
```bash
pip install pandas numpy matplotlib seaborn
```
3. Run the Jupyter Notebook:  
```bash
jupyter notebook Airbnb_Analysis_2024.ipynb
```

## Conclusion
This project provides valuable insights into New York's Airbnb market, helping guests make informed choices and enabling hosts to optimize their listings. Future enhancements, such as predictive modeling and advanced visualizations, can further deepen the analysis.
