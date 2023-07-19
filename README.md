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


**Data Wrangling and visualization**


Data wrangling, also known as data preprocessing or data cleaning, refers to the process of transforming and preparing raw data into a suitable format for analysis. It involves cleaning, organizing, and transforming data to ensure its quality, consistency, and compatibility with the analytical tasks at hand.

Data visualization is the process of representing data and information graphically to facilitate understanding, exploration, and communication of insights. It involves creating visual representations such as charts, graphs, maps, and infographics to effectively convey patterns, trends, relationships, and comparisons present in the data.


The dataset contains 7894 unique properties with 16 variables/features. The focus is on analyzing the physical features, facilities, and their relationship with top listing prices. Key variables of interest include room type, property type, price, host, location, and reviews.

The dataset has null values in the "last_review" and "reviews_per_month" columns, which are subsequently dropped. There are 11452 unique hosts registered in the dataset, with multiple properties associated with each host. Sonder (NYC) is the most registered host, followed by Blueground, Kara, and Kazuya. The calculated host listing count reveals that Manhattan has the highest number of registered hosts, followed by Brooklyn, Queens, Bronx, and Staten Island.

Brooklyn is the most reviewed neighborhood, followed by Manhattan, Queens, and Bronx, with Staten Island having the fewest reviews. Although price information does not provide significant insights about neighborhood groups, the highly reviewed places tend to be more expensive.

Further analysis indicates that Manhattan has the highest number of properties, followed by Brooklyn, Queens, Bronx, and Staten Island. Private rooms are the most preferred room type, followed by entire home/apartment, while shared rooms have the fewest listings. In Manhattan, entire home/apartment properties are the most popular, while in other neighborhoods, private rooms dominate. As a result, entire home/apartment listings tend to be the most expensive (around $211), followed by private rooms (around $89), with shared rooms being the cheapest option (around $70). Manhattan is the most expensive neighborhood, followed by Staten Island and Brooklyn, while the Bronx is the least expensive.

The analysis includes various types of charts such as pie charts, bar plots, stack plots, distribution plots, pair plots, and scatter plots to visually represent the data and gain insights.

In conclusion, Manhattan and Brooklyn are the most popular neighborhood groups based on the number of host listings, percentage of unique hosts, and reviews. Manhattan stands out as the costliest and most popular area.

**Solution to Business Objective:**

To address the business objective of helping hosts grow their Airbnb business, the following solutions can be implemented:

1. Regularly monitor and respond to customer reviews to make necessary improvements and upgrades to the rooms based on feedback.

2. Follow the business practices of top active hosts as a benchmark for success and learn from their strategies.

3. Focus on offering private rooms and entire home/apartments as they have high demand among guests.

4. Set the prices of premises within the average range for each room type in the respective neighborhood group to attract more bookings.

5. Keep an eye on nearby host premises to monitor any special offers or promotions they may be providing to visitors. Adjust pricing and offerings accordingly to remain competitive.

6. Pay attention to the location of the premises and identify which room types are in high demand in specific areas. Tailor the offerings accordingly to attract more bookings.

7. For new hosts, consider opening premises in the Manhattan neighborhood group, as it generates the highest number of bookings and revenue compared to other neighborhood groups.

8. Consider adding premises to the Staten Island neighborhood group, as there is less competition and a lower number of listings available, presenting a favorable opportunity for hosts.

9. Maintain a high rating by providing excellent customer service in addition to competitive pricing. Ensuring customer satisfaction will contribute to positive reviews and attract more bookings.

10. Stay updated with market trends and competitors to remain competitive in the dynamic Airbnb business landscape. Regularly analyze and adjust strategies to meet changing guest preferences and demands.

By implementing these solutions, hosts can enhance their Airbnb business, attract more bookings, and provide a great experience for guests, leading to growth and success in the industry.


**Conclusion:**

The analysis reveals several key findings:

1. Manhattan is the busiest neighborhood, followed by Brooklyn, indicating high demand for Airbnb bookings in these areas.

2. Manhattan has the highest number of registered hosts based on the host listing count, indicating a significant presence of hosts in this neighborhood.

3. Brooklyn has the maximum number of unique hosts currently booked in the dataset, making it an attractive destination for visitors.

4. Visitors show a preference for private rooms and entire home/apartments, with a higher preference for entire home/apartments.

5. Rooms with lower prices tend to receive more reviews and bookings, indicating that affordability plays a role in guests' decision-making.

6. Although entire home/apartments are the most expensive room type, they remain popular among guests. Conversely, shared rooms, despite being the cheapest option, are less preferred.

7. Premises in Manhattan receive the most positive reviews, closely followed by Brooklyn, highlighting their popularity among guests.

8. Manhattan and Brooklyn are the most expensive neighborhoods, with the Bronx being the least expensive. However, guests still prefer staying in Manhattan and Brooklyn.

9. Revenue generation is highest in Manhattan, followed by Brooklyn, indicating the profitability of hosting in these neighborhoods.

10. On average, guests spend $212 on entire home/apartments, $90 on private rooms, and $70 on shared rooms.

Based on these insights, it is evident that Manhattan and Brooklyn are highly attractive destinations for tourists, and from a business perspective, they present favorable opportunities for hosts to succeed in the Airbnb market. Hosts should consider the preferences of guests, maintain competitive pricing, and provide excellent service to capitalize on the popularity of these neighborhoods.


We have reached almost the end of this project. In this project, we analyzed almost every column or variable of the data set. In this, we have done data wrangling that is checking or removing null values and checking for unique values and names.
We have analyzed almost every possible problem statement related to the dataset so that the client can easily understand the data set.
