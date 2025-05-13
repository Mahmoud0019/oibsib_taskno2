# Second Project 
## AB_NYC_2019
### First pic 
![Screanshot (495).](https://github.com/Mahmoud0019/oibsib_taskno2/blob/main/1.png)

##Description:

    This image displays an interactive dashboard visualizing various aspects of Airbnb listings in New York City. The dashboard features several key metrics and visualizations, including:

###Top Metrics: 

Total Sales (48.90K), Number of Neighborhood Groups (5), and Total Number of Neighborhoods (221).
Price vs. Number of Reviews Scatter Plot: Shows the relationship between the price of a listing and the number of reviews it has received, categorized by room type (Entire home/apt, Private room, Shared room).
Count of Rooms by Booking Activity Pie Chart: Illustrates the distribution of listings based on booking demand (High Demand, Low Demand, Moderate Demand).
Count of Rooms by Price Category Pie Chart: Displays the distribution of listings across different price categories (Budget, Mid-Range, Luxury).
Count of Rooms by Room Type Pie Chart: Shows the proportion of each room type (Entire home/apt, Private room, Shared room) among all listings.
Count of Rooms by Price Category Bar Chart (Stacked): Breaks down the number of listings in each price category further by booking demand.
Average Price by Room Type Bar Chart: Compares the average price for each room type.
Average Price by Neighborhood Group Bar Chart: Shows the average price of listings across different neighborhood groups (Manhattan, Brooklyn, Queens, Staten Island, Bronx).
Best Neighborhood Based on Average of Reviews per Month Bar Chart: Ranks neighborhoods based on the average number of reviews received per month.
Interactive Filters: Dropdown menus and a price range slider at the top allow users to filter the data by neighborhood group, room type, and price.

###Analysis:

The dashboard provides a comprehensive overview of the NYC Airbnb market. Key observations include:

Dominant Room Type: Entire homes/apartments appear to be the most common room type, as seen in the "Count of rooms by room_type" pie chart.
Price and Reviews: The scatter plot suggests a wide range of prices and review counts, with some higher-priced listings still attracting a significant number of reviews. There might be a concentration of listings in a certain price range with varying review counts.
Booking Demand Distribution: The "Count of rooms by Booking Activity" chart shows the distribution of demand, which could be useful for hosts in adjusting pricing and availability.
Price Category Distribution: The "Count of rooms by Price Category" chart highlights the prevalence of listings in different price segments.
Neighborhood Price Variations: The "Average price by neighbourhood_group" bar chart clearly shows price differences across the boroughs, with Manhattan likely having a higher average price.
Neighborhood Popularity: The "best neighbourhood based on Average of Reviews_per_month" chart identifies neighborhoods that, on average, receive more reviews per month, potentially indicating higher guest satisfaction or booking frequency.

###Insights:

Market Trends: The dashboard helps identify the most common and potentially most in-demand room types.
Pricing Strategies: Hosts can use the price distribution and the relationship between price and reviews to inform their pricing strategies.
Location Analysis: Understanding the average prices and popularity of different neighborhood groups and specific neighborhoods can guide investment decisions for potential hosts or inform guests about the cost of staying in different areas.
Demand Forecasting: The booking activity data could be valuable for predicting future demand and adjusting strategies accordingly.
Competitive Landscape: Analyzing the number of listings in different price categories and room types provides insights into the competitive landscape for Airbnb hosts.

### Second pic 
![Screanshot (495).](https://github.com/Mahmoud0019/oibsib_taskno2/blob/main/2.png)

###Description:

This image shows an interactive data exploration interface, possibly within a business intelligence tool, visualizing the breakdown of Airbnb listings based on a hierarchical structure of selected dimensions. The current path being explored is:
neighbourhood_group: Showing the five boroughs of New York City (Manhattan, Brooklyn, Queens, Bronx, Staten Island) and the count of listings in each.
neighbourhood: Further breaking down each borough into specific neighborhoods and showing the count of listings within those. "Arverne" in Queens is currently highlighted with 1 listing.
room_type: Categorizing the listings within the selected neighborhood (Arverne) by room type (Entire home/apt, Private room, Shared room). "Entire home/apt" is highlighted with 1 listing.
availability_365: Showing the number of listings within the selected room type (Entire home/apt in Arverne) based on their availability throughout the year. Listings with an availability of "2" and "1" day are shown.
price: Finally, displaying the price of the listings based on the selected availability (e.g., 1 listing for an entire home/apt in Arverne with 2 days of availability has a price of 300).
The interface allows users to drill down through these dimensions to understand the composition of the Airbnb market based on specific criteria. Filters for "neighbourhood_group," "room_type," and "price" are visible at the top, suggesting the user can interactively modify the analysis.

###Analysis:

This visualization allows for a granular exploration of the Airbnb data. Key observations from the current view include:

Hierarchical Breakdown: The structure clearly shows how the total number of listings (starting from "neighbourhood") is distributed across different levels of geographical areas, room types, availability, and finally, price.
Drill-Down Capability: The highlighting of "Arverne," "Entire home/apt," and a price of "300" indicates a user has navigated through the data to focus on a very specific segment of the market.
Listing Counts at Each Level: The numbers associated with each category at each level provide the count of listings that meet the criteria of the path taken. For example, there are 31 listings in Queens, 1 in Arverne, and 1 of those in Arverne is an entire home/apt.
Impact of Filters: The filters at the top suggest that the user can start their exploration from different dimensions (e.g., filtering by a specific price range first).

###Insights:

Niche Market Identification: This type of analysis helps identify niche markets within the broader Airbnb landscape. For example, the current path reveals details about the pricing of entire homes/apartments in a specific neighborhood with limited availability.
Understanding Feature Combinations: It allows users to see how different features (location, room type, availability) combine and their impact on the number of listings and potentially price.
Targeted Analysis: Users can perform targeted analysis based on specific criteria relevant to their interests (e.g., finding affordable private rooms in a particular borough).
Data Granularity: This visualization provides a high level of data granularity, enabling a deep understanding of the underlying data structure and relationships between different variables.
Interactive Exploration: The interactive nature allows for dynamic exploration and discovery of patterns and trends that might not be apparent in aggregated summary statistics.
