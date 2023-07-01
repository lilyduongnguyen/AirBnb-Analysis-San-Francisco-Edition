# Airbnb Analysis: San Francisco Edition

![Airbnb Logo](https://upload.wikimedia.org/wikipedia/commons/6/69/Airbnb_Logo_B%C3%A9lo.svg)

This README provides a guide for new hosts looking to invest in Airbnb units in San Francisco. It includes insights from the dataset and offers recommendations on location, amenities, becoming a Superhost, and improving guest experience based on reviews.

## About Airbnb
AirBnb, founded in 2008, is a global platform that connects hosts and guests for unique travel experiences. As of September 2021, the website boasts over 4 million hosts and operates in more than 220 countries and regions. In 2019, hosts in the United States alone earned over $10 billion. Airbnb also offers a Host Guarantee program, providing up to $1 million in property damage protection for eligible bookings.

## Table of Contents

- [Installation](#installation)
- [Data](#data)
- [Analysis](#analysis)
- [Results](#results)
- [Acknowledgments](#acknowledgments)

## Installation

To run this analysis, you need to have the following libraries installed:

- geopandas
- nltk
- pandas
- numpy
- seaborn
- matplotlib
- wordcloud
- folium

You can install the required libraries using the following command:

```
pip install geopandas nltk pandas numpy seaborn matplotlib wordcloud folium
```

## Data

This analysis uses two dataset files:

- `listings.csv.gz`: Contains information about Airbnb listings in San Francisco, including property type, price, availability, review scores, and more.
- `reviews.csv.gz`: Contains reviews for the listings, including comments and ratings.

Please ensure that these files are placed in the project directory before running the code.

## Analysis

The analysis consists of the following steps:

1. Importing necessary libraries and dataset files.
2. Observing the dataset by printing information about the listings dataframe.
3. Analyzing different neighborhoods in San Francisco based on average rating, price, availability, and demand.
4. Exploring amenities across different room types and creating visualizations.
5. Analyzing superhosts and their ratings.
6. Creating word clouds to visualize high and low rating reviews.
7. Creating interactive maps using Folium to visualize the data geographically.

## Results

The analysis provides insights into the following aspects:

- Average rating, price, availability, and demand across different neighborhoods in San Francisco.
- Distribution of amenities among different room types.
- Relationship between superhost status, review ratings, and host response rates.
- Word clouds showing important words in high and low rating reviews.
- Interactive maps displaying the spatial distribution of ratings, prices, and other variables across San Francisco neighborhoods.

The generated visualizations help in understanding the Airbnb landscape in San Francisco and provide valuable insights for hosts and travelers.

## Acknowledgments

The analysis was performed using the San Francisco Airbnb dataset obtained from [Inside Airbnb](http://insideairbnb.com/get-the-data.html). Special thanks to the developers and contributors of the libraries used in this analysis, including pandas, numpy, seaborn, matplotlib, wordcloud, geopandas, nltk, and folium.
