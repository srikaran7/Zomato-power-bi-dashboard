Zomato Dashboard Documentation in Power BI
Overview
This documentation outlines the process for building a Zomato Dashboard in Power BI. The dashboard provides insights into restaurant data, customer reviews, pricing trends, and more. The goal is to analyze the Zomato dataset to gain valuable insights into the food industry, customer preferences, and market trends.

Dataset
The Zomato dataset includes restaurant information from various cities around the world. Typical columns include:

Restaurant Name: The name of the restaurant.
City: The city in which the restaurant operates.
Cuisine: The type of cuisine served by the restaurant.
Rating: The average rating given by customers.
Price Range: The pricing level of the restaurant.
Votes: The number of votes or reviews received.
Delivery: Whether the restaurant provides food delivery services.
Address: The restaurant’s address.
Key Metrics & KPIs
Average Rating: The average customer rating for restaurants in a specific location or overall.
Total Restaurants: The total number of restaurants in the dataset.
Top Cities: Cities with the highest number of restaurants.
Popular Cuisines: The most frequently served cuisines.
Price Range: Distribution of restaurants by price category (e.g., low, medium, high).
Number of Reviews (Votes): Number of customer reviews or votes a restaurant has received.
Steps to Build the Zomato Dashboard
1. Data Preparation
Before importing the dataset into Power BI, make sure the data is clean and formatted correctly. This may include:

Removing duplicates.
Filling missing values in critical columns like restaurant names, ratings, etc.
Standardizing data (e.g., categorizing price ranges into specific levels).
Data Columns
Restaurant ID: Unique identifier for each restaurant.
Name: Name of the restaurant.
City: City where the restaurant is located.
Cuisine: Cuisine types offered.
Rating: Average customer rating.
Price Range: A categorical value indicating the pricing level (1 to 4, with 1 being the cheapest).
Votes: Number of reviews or votes for each restaurant.
2. Import Data into Power BI
Open Power BI Desktop.
Click Get Data and select CSV (if using a CSV dataset) or the appropriate source.
Import the Zomato dataset into Power BI.
Clean and format the data as required (e.g., changing data types, renaming columns).
3. Create Data Relationships
Ensure that if you have multiple tables (e.g., restaurants, reviews, cuisines), the relationships between tables are correctly set up:

City Table (if you have a separate table with city details).
Cuisine Table (if cuisines are in a separate table).
In the Model view, check that relationships are established between relevant tables, such as between Restaurant ID and City.

4. Build Visuals
A. Total Number of Restaurants
Visual Type: Card.
Field: Count of Restaurant ID.
This visual shows the total number of restaurants in the dataset.
B. Average Rating of Restaurants
Visual Type: Gauge or Card.
Field: Average of Rating.
This visual displays the average rating across all restaurants.
C. Top Cities by Number of Restaurants
Visual Type: Bar Chart or Column Chart.
Fields: City (Axis) and Count of Restaurant ID (Values).
Sort the chart by the number of restaurants.
D. Popular Cuisines
Visual Type: Pie Chart or Donut Chart.
Fields: Cuisine (Legend) and Count of Restaurant ID (Values).
Shows the distribution of cuisines served by restaurants.
E. Price Range Distribution
Visual Type: Bar Chart or Pie Chart.
Fields: Price Range (Axis) and Count of Restaurant ID (Values).
Visualizes how many restaurants fall into each pricing category (1-4).
F. Rating Distribution
Visual Type: Histogram or Column Chart.
Fields: Rating (Axis) and Count of Restaurant ID (Values).
This visual displays the spread of restaurant ratings.
G. Number of Reviews (Votes)
Visual Type: Column Chart.
Fields: Votes (Axis) and Count of Restaurant ID (Values).
Displays the number of votes or reviews that restaurants have received.
5. Adding Filters
Add slicers for key filters such as City, Cuisine, and Price Range.
Users can select a specific city or cuisine to filter the visuals and analyze trends based on their selection.
Example Filters:
City Filter: Allows users to filter the dashboard by city.
Cuisine Filter: Allows users to filter by a specific type of cuisine.
Price Range Filter: Filters the visuals based on the price category.
6. Drill-Down Functionality
Enable drill-down on certain visuals (e.g., Top Cities) so that users can click on a specific city and see detailed information like the most popular cuisines or highest-rated restaurants in that city.

7. Format the Dashboard
Choose a Theme: Select a Power BI theme or customize colors to match Zomato's branding (e.g., use shades of red, white, and black).
Title and Labels: Ensure all visuals have clear titles and axis labels.
Tooltips: Add tooltips to provide more detailed information when hovering over visuals.
8. Publish the Dashboard
Once the dashboard is complete, you can publish it to Power BI Service:

Click Publish on the Home ribbon.
Select a Workspace in Power BI Service where you want the dashboard to be available.
Share the dashboard link with stakeholders or embed it in a website for public use.
Key Insights from the Zomato Dashboard
City-wise Distribution: Identify which cities have the highest number of restaurants.
Popular Cuisines: Analyze customer preferences for different cuisines.
Rating Analysis: Understand which restaurants have the best ratings and customer feedback.
Price Trends: Compare restaurants based on price ranges and identify budget-friendly or luxury dining spots.
Review Analysis: Gauge customer engagement through the number of votes or reviews.
Conclusion
This Power BI Zomato Dashboard provides a clear, visual overview of restaurant trends and customer preferences. With filters and interactive visuals, users can deep-dive into specific cities, cuisines, and price ranges, making it a valuable tool for restaurant owners, marketers, and data analysts.
