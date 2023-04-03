# Analysis of Boston Airbnb Listings

This project analyzes Airbnb listings in Boston to identify seasonal price trends, compare prices across different neighborhoods, and investigate the impact of property type on pricing. The analysis is based on three datasets: boston_calendar.csv, boston_listings.csv, and boston_reviews.csv, which contain information on calendar availability, listing details, and user reviews, respectively.

### Libraries Used
The analysis uses the following Python libraries:

pandas
matplotlib
numpy
datetime

### Motivation
The goal of this project is to gain insights into the pricing of Airbnb listings in Boston and identify any trends or patterns that may be useful for travelers or hosts. By analyzing the data, we aim to answer the following questions:

- How do listing prices change over the year, and are there any seasonal trends?
- Are there significant differences in pricing between different neighborhoods in Boston?
- How does the type of property (e.g. apartment, house, private room) affect the listing price?

### Files in Repository
This repository contains the following files:

- boston_calendar.csv: A dataset containing calendar availability for each listing in Boston. The dataset includes information on the date, price, and availability of each listing.
- boston_listings.csv: A dataset containing detailed information on each listing in Boston. The dataset includes information on the property type, location, amenities, and pricing.
- boston_reviews.csv: A dataset containing user reviews for each listing in Boston. The dataset includes information on the reviewer, the date of the review, and the content of the review.
- seattle_listings.csv: A dataset containing detailed information on each listing in Boston. The dataset includes information on the property type, location, amenities, and pricing. We will not analyse this dataset and only compared it to the Boston dataset in our exploratory analysis. 


### Results

Our analysis of the Boston Airbnb dataset revealed the following insights:

Seasonal price trends: The median listing price in Boston remains relatively stable throughout the year, with a small spike in September and October. This suggests that late summer and early fall may be popular times to visit Boston.

Neighborhood price comparison: There are significant differences in median listing prices across different neighborhoods in Boston. The top 4 neighborhoods with the highest median prices are South Boston Waterfront, Leather District, Downtown, and Chinatown, while the neighborhood with the lowest median price is Hyde Park.

Impact of property type on price: There are significant differences in median listing prices across different types of properties in the Boston Airbnb dataset. Guesthouses have the highest median price, followed by Boat listings and "Other" types of properties, while Camper/RV listings have the lowest median price.

Overall, our analysis suggests that property type, neighborhood, and season are important factors to consider when searching for an Airbnb listing in Boston, as they can have a significant impact on pricing.