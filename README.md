# Data-analysis-of-Kuala-Lumpur-data
Data:
 • List of neighborhoods in Kuala Lumpur. This defines the scope of this project which is confined to the city of Kuala Lumpur, the capital city of the country of Malaysia in South East Asia.
 • Latitude and longitude coordinates of those neighborhoods. This is required in order to plot the map and also to get the venue data.
 • Venue data, particularly data related to shopping malls. We will use this data to perform clustering on the neighborhoods.

Sources of data and methods to extract them 
This Wikipedia page (https://en.wikipedia.org/wiki/Category:Suburbs_in_Kuala_Lumpur) contains a list of neighbourhoods in Kuala Lumpur, with a total of 70 neighbourhoods. We will use web scraping techniques to extract the data from the Wikipedia page, with the help of Python requests and beautiful soup packages. 
The geographical coordinates of the neighbourhoods using the Python Geocoder package are obtained which will give us the latitude and longitude coordinates of the neighbourhoods.
Foursquare API is used to get the venue data for those neighborhoods. Foursquare has one of the largest databases of 105+ million places and is used by over 125,000 developers. Foursquare API will provide many categories of the venue data, we are particularly interested in the Shopping Mall category in order to help us to solve the business problem put forward. 

Data science skills used:
1) Web scraping (Wikipedia)
2) Working with API (Foursquare) 
3) Data cleaning
4) data wrangling
5) Machine learning (K-means clustering)
6) Map visualization (Folium)

