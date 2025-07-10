# LOCATION-BASED-ANALYSIS
1)Project Overview : 
This project performs a geographical analysis of restaurant data using latitude and longitude coordinates, along with city and locality information. The goal is to uncover spatial patterns, distribution, and insights about restaurants across different locations.

2)Objectives : 
Visualize restaurant distribution on geographical maps
Analyze concentration of restaurants by city or locality
Compute average ratings, cost, and cuisine types by area
Identify high-density or high-rated restaurant clusters
Explore patterns that relate restaurant success to location

3)Dataset Summary : 
The dataset contains the following relevant features:
Restaurant name
City and locality
Latitude and longitude
Aggregate rating
Price range and average cost for two
Cuisines offered

4)Key Features Implemented : 
1. Coordinate Visualization
Plotted restaurants on a 2D scatter plot using latitude and longitude
Color-coded by city to show geographic spread

2. Interactive Map (Folium)
Used folium to display an interactive map with:
Restaurant markers
Popups showing name, city, and cuisine
Clustered markers for performance on large datasets

3. City-Level Analysis
Counted the number of restaurants per city
Identified top cities by restaurant count
Calculated average
Rating
Price range
Cost for two
Grouped by city or locality

4. High-Rated Restaurant Clusters
Filtered restaurants with rating ≥ 4.0
Analyzed city-wise distribution of top-rated venue

5)Technologies Used : 
Python
Pandas, NumPy (data processing)
Seaborn, Matplotlib (static visualization)
Folium, MarkerCluster (interactive mapping

