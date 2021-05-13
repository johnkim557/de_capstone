# Data Pipeline Capstone Project


### Process for scraping information for all restaurants in New Jersey
The algorithm for api use is not functioning correctly so a customizable html api has been used to obtain information of all 'type' inputs. For instance, after providing longitude and latitude constraints as well as a radius and type argument then a dictionary of data is outputed as a new page. Creating a bot that can find all zipcodes within New Jersey and finding the coordinates and applying them to this html format will allow me to obtain information on all restaurants, food, bar categories within New Jersey. The method for search will consist of constructing a rectangular encapsulation of an area that borders New Jersey. Afterwards,
utilize gps coordinates to find all corners of the encapsulation and find the distance between points. Divide the area by the search unit argument used within the html api and search through the area of New Jersey as a 2d array. A relational database is used to maintain the data schema and withold all information of incoming data.

A non-relational database such as MongoDB, may be considered for use for creating a self-automated workflow to option possible additions of customer reviews. The google API has a limit of scraping 5 reviews per session. A daily upload of potentially new reviews will be added on a daily basis, if project expands into entire North American region then a No-Shared System can be optimal for quickly inserting into a data warehouse or store.


### New Jersey Search Encapsulation Coordinates
TOP Left Coordinate: 41°27'29" N 75° 51' 34" W
TOP Right Coordinate: 41° 27' 29" 73° 42' 39" W
Bottom Left Coordinate: 38° 52' 15" N 75° 51' 34" W
Bottom Right Coordinate: 38° 52' 15" N 73° 42' 39" W

Top/Bottom Length of Rectangle Encapsulation = 179,000m
Left/Right Side Length of Rectangle Encapsulation = 287,700m
