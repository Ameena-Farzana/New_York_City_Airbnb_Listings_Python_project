# New_York_City_Airbnb_Listings_Python_project

 ![image](https://github.com/Ameena-Farzana/New_York_City_Airbnb_Listings_Python_project/assets/121862099/86e0e0c9-f95b-43d6-914d-eca613f0789f)


The Airbnb dataset provides a comprehensive and detailed snapshot of the New York City lodging market as presented on the Airbnb platform. It encompasses a wide array of attributes that encapsulate various aspects of the listings,hosts, and guests. This dataset serves as a valuable resource for understanding the dynamics of short-term rentals in one of the world's most bustling cities. Let's delve into its key components:

## Listing Information: 
The dataset includes crucial details about each listing, such as the unique identifier (id), the name of the listing (name), the host's identifier (host_id), the host's name (host_name), the neighborhood group (neighbourhood_group), the specific neighborhood (neighbourhood), geographical coordinates (latitude and longitude), the type of room (room_type), the nightly price (price), the minimum number of nights required for booking (minimum_nights), the total number of reviews (number_of_reviews), the date of the last review (last_review), and more.

## Host Information: 
In addition to the listing details, the dataset provides insights into the hosts behind the listings. This includes the host's name (host_name), unique identifier (host_id), and calculated host listing count (calculated_host_listings_count), representing the number of listings managed by each host.

## Guest Reviews: 
The dataset captures the guest experience through attributes like the number of reviews (number_of_reviews), the average number of reviews per month (reviews_per_month), and the availability of the listing for the next 365 days (availability_365).

## Geographical Data: 
The geographical coordinates (latitude and longitude) enable the visualization of listings on maps, allowing insights into the distribution of properties across different neighborhoods.

## Price and Cost Insights: 
The price information (price) helps analyze the cost of accommodations across different room types, neighborhoods, and boroughs of New York City.

## Room Types and Availability: 
The room_type attribute categorizes listings into types such as 'Entire home/apt,' 'Private room,' and 'Shared room.' Additionally, the availability data (availability_365) offers insights into how frequently listings are open for booking throughout the year.

## Neighborhood Insights: 
The dataset provides a breakdown of listings by neighborhood, revealing the concentration and distribution of accommodations across different areas of the city.

## Temporal Trends: 
The inclusion of data related to the date of the last review (last_review) and the average number of reviews per month (reviews_per_month) allows for the exploration of temporal trends and patterns.

# Steps Taken to Analyze and Visualize New York City Airbnb Data 

### Data Loading and Exploration:

Loaded the Airbnb dataset, which includes various attributes related to listings, hosts, and guest reviews.
Explored the dataset's structure, including columns, data types, and null values.

### Data Cleaning:

Addressed missing values by either imputing or removing them, ensuring data integrity.
Filtered out extreme values to enhance visualizations and analyses.

### Initial Descriptive Analysis:

Calculated summary statistics for key attributes, including price and number of reviews.
Visualized price distributions, room type distributions, and neighborhood insights.

### Neighborhood Analysis:

Investigated the distribution of listings across neighborhoods using bar plots and count plots.
Created violin plots to compare price distributions among different neighborhoods.

### Room Type Analysis:

Grouped data by room type and calculated statistics for price and number of reviews.
Visualized room type distribution using a pie chart.

### Top Listings Analysis:

Identified the top-reviewed listings and showcased them using descriptive observations.
Highlighted the popularity of certain listings based on their number of reviews.

###Geospatial Visualization:

Plotted geographical coordinates on a scatter plot to visualize listing prices by latitude and longitude.
Created a geospatial visualization showcasing price distribution across different areas.

### Correlation Analysis:

Calculated correlations between numerical attributes to uncover potential relationships.
Visualized correlations using a heatmap.

### Availability Analysis:

Explored the availability of listings across neighborhoods using box plots.
Compared the availability of room types in different neighborhood groups.

## Conclusion

Highly Reviewed Listings: The listing "Room near JFK Queen Bed" stands out with an impressive 629 reviews, followed closely by "Great Bedroom in Manhattan" with 607 reviews, indicating their popularity among travelers.

Limited Shared Rooms: The scarcity of 'Shared room' listings among the top 10 neighborhoods with the highest listing densities suggests a preference for 'Entire home/apt' and 'Private room' types, highlighting a demand for privacy and convenience.

Room Type Distribution: The dataset is primarily dominated by two room types: 'Entire home/apt' (53.1%) and 'Private room' (46.7%), with 'Shared room' making up only 2.4% of the listings.

Popular Destinations: Manhattan and Brooklyn emerge as highly sought-after travel destinations, leading to a higher availability of listings. Bedford-Stuyvesant and Williamsburg are popular in Manhattan, while Harlem is a preferred neighborhood in Brooklyn.

Price Range Variation: Manhattan boasts the highest price range, with an average of $150 per night, followed by Brooklyn at $90. Queens and Staten Island show similar price distributions, while Bronx offers more budget-friendly options.

Cost of Living: The higher prices in Manhattan reflect its status as one of the world's most expensive places to live. In contrast, Bronx offers relatively more affordable accommodations, indicating a potential variance in living standards.
