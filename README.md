## overview

For this challenge, restaurant data from a JSON file was imported into a MongoDB database. The data was cleaned and then analysed.

The original data can be found in the 'Resources' folder as 'establishments.json'.

## setup

The establishments.json file was imported into the 'establishments' collection of the 'uk_food' database.

Additional data for a new restaurant was added to the collection and unnecessary documents were identified and deleted. Finally, relevant datatypes were updated.

The code for the setup can be found in the 'NoSQL_setup.ipynb' file.

## analysis

Once the data has been cleaned, a series of queries were performed to answer the following questions:

1. Which establishments have a hygiene score equal to 20?
2. Which establishments in London have a RatingValue greater than or equal to 4?
3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

All code and query results can be found in the 'NoSQL_analysis.ipynb' file.

## references

All data was collected and produced for the edX University of Birmingham Data Analytics Bootcamp.

UK Food Standards Agency (2022). UK food hygiene rating data API. 

https://ratings.food.gov.uk/open-data/en-GB. Contains public sector information licensed under the Open Government Licence v3.0 Links to an external site.

Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).
