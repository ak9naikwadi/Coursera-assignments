# Capstone Project
This is the assignment of week 4.
## Battle of Neighborhoods
In this file, the Introduction and Data section of the project are given.
### Introduction
Many people shift from their old home to new home. But many a times people find it difficult to find a new home having amenities of their preferences. This is because of the reason that they want to keep their lifestyle same as before. This project will mainly focus on recommending neighbourhoods which are similar to their former one. They want similar kind of restaurants they used to frequent before, they want school, colleges for their children in their neighborhood, they want their previous facilities at almost the same distance as they were before. To solve such problems, this project will use clustering to find out similar neighborhoods.
### Data
We will utilize neighbourhoods information of Toronto and Scarborough, Foursquare information on venue categories, top tips, location data, ratings to tackle this task. Neighbourhood information can be accessed through: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M
The main problem can be solved by applying K-means clustering to perform city segmentation. With the neighbourhoods being clustered into clusters, this task becomes finding the neighbourhoods within the same cluster as the previous neighborhood
The requirement of wanting the previous amenities can be solved by providing venue and ratings information from Foursquare API. The neighbourhoods with high ratings of the required restaurants, required grocery store, etc will become our target neighbourhoods.
