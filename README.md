# Movie Analysis

## Project Overview

The MovieAnalysis project involves gathering data from APIs and webscraping. After the data was gathered, exploratory data analysis was used to generate insights for making recommendations for the new Microsoft Movies team. 

### Data

#### Movie datasets are collected from:
  * IMDB website with Beautiful Soup
  * https://www.themoviedb.org/ with API call

#### The visuals were provided by manipulating the following variables:
  * Genres
  * Gross Revenues
  * Release Month
  * IMDB Ratings
  * TMDB Popularity
  * Runtime


### Graphs

This graph demonstrates the skewed distribution. 
![gross_earnings_distribution](graphs/gross_earnings_distribution.jpg)


This graph demonstrates the popularity of each genre from the TMDB database. Drama, thriller, and comedy are the three most popular genres based on our findings. 
![distribution_genre](graphs/Distribution_genre.png)


Adventure, family, animation, and action generate the largest revenue. 
![average_gross_earnings](graphs/Average_Gross_Earnings.png)


This boxplot demonstrates the IMDB Ratings of each genre. There is no clear favorite for the genres, but war movies has the largest variation. 
![average_rating](graphs/Average_IMDB_Ratings.png)


From the graph one can see family, animation, fantasy, and adventure are more popular, on average. 
![TMDB_popularity](graphs/Average_TMDB_Popularity.png)


These graphs were made to show if there is any variation per month in gross per genre.
![month_genre_gross_median](graphs/month_genre_gross_median.png)
