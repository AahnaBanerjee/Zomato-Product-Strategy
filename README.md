# Zomato Restaurant Analysis - README

## Abstract

Zomato is one of the leading online food delivery platforms in India, offering users ratings and reviews for restaurants across the country. These ratings and reviews play a crucial role in determining the quality and popularity of a restaurant. In this project, we focus on analyzing a real-time dataset from Zomato, specifically for Bengaluru City. The goal is to understand the factors that influence restaurant establishment, customer preferences, and aggregate ratings in this dynamic and diverse city.

## Content

The primary objective of this analysis is to explore the factors that affect the success and establishment of various types of restaurants in different locations across Bengaluru. With over 12,000 restaurants in the city, Bengaluru offers a wide variety of cuisines from around the world. As new restaurants continue to open, the competition remains fierce, especially for those serving similar types of food.

Bengaluru, known as the IT capital of India, has a large population that relies on restaurant food due to busy lifestyles. This makes it essential to study the demographic and culinary preferences of different localities. For instance, understanding whether a locality prefers vegetarian food or if it is dominated by a particular community, such as Jains, Marwaris, or Gujaratis, can provide valuable insights for restaurant owners.

In this analysis, we consider various features that users typically look for when choosing a restaurant, such as:

- Location of the restaurant
- Approximate price of food
- Whether the restaurant is theme-based
- Which localities have the highest concentration of restaurants serving specific cuisines
- The dining preferences of the neighborhood
- Popularity of specific types of food in certain areas

The dataset used in this analysis was scraped from Zomato and is accurate as of March 15, 2019. The data scraping was conducted in two phases:

### Phase I:
In the first phase, the URLs, names, and addresses of restaurants were extracted from Zomato's website. This initial extraction focused on gathering basic information visible on the front page of the site. The recorded URLs were then saved in a CSV file for further processing.

### Phase II:
In the second phase, detailed data for each restaurant was scraped individually. This included 15 variables such as online order availability, table booking options, ratings, votes, phone numbers, locations, restaurant types, disliked dishes, cuisines, approximate costs, reviews, and menu items. This comprehensive data allowed for an in-depth analysis of restaurant performance and customer preferences in Bengaluru.

## Acknowledgements

This dataset was scraped entirely for educational purposes. All rights and copyrights of the data belong to Zomato Media Pvt. Ltd. This analysis does not claim any ownership of the data and is intended solely for research and learning purposes.
