# Comprehensive Analysis of the Polish Housing Market Using Otodom Data
This project provides a comprehensive analysis of the housing market in Poland, using data from the popular real estate website Otodom. The analysis aims to answer various questions related to renting and buying properties in major Polish cities.

# Description
The analysis covers important aspects such as:

Average rental prices for different types of apartments (1-room, 2-room, 3-room, and 4-room) in major cities.
Identifying suburbs in Warsaw where apartments of a specific size and price range can be found.
Exploring the size of apartments that can be expected within a given rental price range in different cities.
Showcasing the most expensive apartments in major cities, including details such as the ad title, city, suburb, cost, and size.
Examining the percentage of private and business ads on Otodom.
Analyzing the average sale prices for apartments within a specific area range (50-70 sqm) across major cities.
Investigating the average rental prices for apartments in different suburbs of Warsaw, categorized by surface area (0-50 sqm, 50-100 sqm, and over 100 sqm).
Identifying the top three most luxurious neighborhoods in Warsaw based on the number of apartments costing over 2 million PLN.
Determining the top five most affordable neighborhoods in Warsaw for small families looking for apartments between 40-60 sqm.
Highlighting the suburbs in Warsaw with the most and least number of private ads.
Comparing the average rental and sale prices in major cities.

# Technologies Used
Snowflake: Cloud-based data storage and analytics service used for data transformation and finding insights.
Google Sheets API: Used to convert text descriptions from Polish to English.
Python (geopy): Utilized to transform house addresses from longitude and latitude format to readable human language.

# Data Transformation
The project involved extensive data transformation to prepare the dataset for analysis:

Converting JSON data from the source into a CSV file format.
Translating the description column from Polish to English.
Converting longitude and latitude coordinates into proper addresses using geopy.
Removing unnecessary null values and special characters.

# Conclusion
This housing market analysis provides valuable insights into the Polish real estate market, helping potential buyers and renters make informed decisions. By exploring various aspects such as prices, locations, and property characteristics, this project aims to serve as a comprehensive guide for those interested in the housing market in Poland.
