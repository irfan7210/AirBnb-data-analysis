# AirBnb-data-analysis
**Project summary**
Airbnb stands for 'Air Bed and Breakfast', and it is an online service that lets property owners rent out their premises, houses, or places to travelers looking for a place to stay. The prices of Airbnb premises are comparatively cheaper than hotels. And it allows the owner to fix the price of premises for the traveler. These days' people are preferring Airbnb to stay instead of expensive and luxurious hotels. In this growing industry, there is a lot of competition among hosts, all hosts want to make their listings attractive, and it is difficult for some hosts to make their listings attractive. Using data science, we make this problem quite simple by collecting lots of data and analyzing it using python's libraries (i.e., pandas, numpy, seaborn, and matplotlib). This analysis helps us to attract customers and give them world-class service at their level, and so different types of factors like price, area, reviews, and services affect their choices. Here, we will analyze the data and try to make a correlation between different variables, and find the relation between top listings so that in the future a host can take business decisions using these insights gained after EDA.

**Problem Statement**

The task at hand is to analyze the given data and identify the variables and their relationships. Our initial focus is on the physical features and facilities of the properties, specifically exploring the relationship between top listings and their prices. We pay close attention to the property's room type, property type, price, host, location, and reviews.

- **id**: Each property has a unique ID, which helps us identify distinct properties.

- **Host_id**: Each host is assigned a unique ID, enabling us to analyze the number of hosts, their maximum number of listings, identify the most popular host, and assess their charges.

- **Neighbourhood_group & neighborhood**: We examine these variables to determine which neighborhood group has the highest number of properties, identify the most popular neighborhood, and find the most expensive place to live.

- **Room_type**: The data includes three types of rooms: private, shared, and entire home. Our aim is to determine which room types are the most popular and the most expensive.

- **Number_of_reviews**: We utilize this variable to assess the quality of service provided by each property and identify hosts that offer exceptional service.

- **Availability_365**: This variable helps us determine the availability of properties throughout the year.

By analyzing these variables and their relationships, we can gain insights into the property listings, hosts, neighborhoods, room types, and overall availability.


**Business Objective**

The objective of this project is to conduct exploratory data analysis on NYC Airbnb bookings. By analyzing all the variables present in the dataset, our goal is to identify factors that can assist Airbnb hosts in growing their business.

Through comprehensive data analysis, we aim to gain insights into various aspects of the Airbnb bookings in NYC. This analysis will help us understand the dynamics of the market, discover patterns and trends, and uncover valuable information that can be used to guide hosts in improving their business strategies.

By examining the variables related to property features, host information, neighborhood characteristics, room types, reviews, and availability, we can identify key factors that significantly impact the success and growth of an Airbnb business. These insights can help hosts make informed decisions regarding pricing, property management, amenities, customer service, and marketing strategies.

Ultimately, the objective is to provide actionable recommendations and insights derived from the data analysis that can empower Airbnb hosts in NYC to enhance their business performance and achieve sustainable growth.

**About Data Set**
Link: https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data

Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present a more unique, personalized way of experiencing the world. Today, Airbnb has become one of a kind service that is used and recognized by the whole world. Data analysis on millions of listings provided through Airbnb is a crucial factor for the company. These millions of listings generate a lot of data that can be analyzed and used for security, business decisions, understanding of customers' and providers' (hosts') behavior and performance on the platform, guiding marketing initiatives, implementation of innovative additional services, and much more. This dataset has around 49,000 observations with 16 columns, and it is a mix of categorical and numeric values.

**Variable Description**

Here is a description of the variables present in the dataset:

- **id**: Each premise in the dataset has a unique ID assigned to it.

- **host_id**: Hosts on Airbnb are identified by unique IDs. A host may have multiple IDs if they manage multiple premises.

- **neighbourhood_group & neighborhood**: The dataset includes information about four neighborhood groups, each containing multiple neighborhoods where Airbnb operates.

- **room_type**: The dataset categorizes rooms into three types: private rooms, shared rooms, and entire homes.

- **number_of_reviews**: Premises are reviewed and rated by users based on their experiences during their stay.

- **availability_365**: This variable indicates the availability of a premise for booking throughout the year, specifying the number of days it is available.

- **latitude & longitude**: The latitude and longitude coordinates represent the location of each premise.

- **minimum_nights**: This variable specifies the minimum number of nights that guests must stay in a particular premise.

- **calculated_host_listings_count**: It denotes the count of listings managed by a host in a specific premise.

These variables provide key information about each premise, including its unique identifier, host details, neighborhood characteristics, room type, guest reviews, availability, location coordinates, minimum stay requirements, and the number of listings managed by each host.

By analyzing these variables, we can gain insights into various aspects of the Airbnb listings, host activity, guest preferences, and geographic distribution, enabling us to uncover valuable information and patterns within the dataset.


**Data Wrangling and Vizualization**



