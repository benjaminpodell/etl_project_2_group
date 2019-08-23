# etl_project_2_group

Our group wanted to compare fast food restaurants with average incomes in certains areas. The csv dataset from data.world shows over 10,000 fast food restaurants and includes the restaurant's address, city, latitude and longitude coordinates, name, and more. The second csv dataset from kaggle contains records on US Household Income Statistics & Geo Locations. We wanted see if there was any relationship between the number of fast food restaurants and the average income in particular areas (zip codes).

The datasets were cleaned by renaming and excluding columns that were not pertinent. The datasets were then joined together on corresponding information. It was then loaded onto postsql relational database.