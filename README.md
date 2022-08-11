# Surfs_Up

# Climate Analysis to invest in surf shop

# Project Overview

This project aims to analyze the weather before investing in a surfing shop on Oahu Island. To do this, we use the SQLite weather database. The project also uses SQLAlchemy create_engine to connect the SQLite database and automap_base() to reflect tables into classes and save a reference. To determine if the surf and ice cream shop business is sustainable year-round, We want temperature data for June and December in Oahu.

# Results

## June Temperature
The summary statistics show that we have 1700 observations for June, and the average temperature is 74.94 °F. While the minimum is 64 °F and the maximum is 85 °F. The standard deviation is 3.2, while the first, second, and third quartiles are 73,75, and 77, respectively. The summary shows that the data is spread each temperature around the average mean.

![June temp](https://user-images.githubusercontent.com/105765150/184142985-2024ca20-9115-44ea-8d84-6efccc5cb313.png)


## December Temperature
The summary statistics below show we have 1517 observations. The average temperature on Oahu Island during December is 71 °F, while the minimum is 56 and the maximum is 83 °F. The standard deviation is 3.7, while the first, second, and third quartiles are 71,74, and 74, respectively. The summary shows that each average temperature is equal to the second quartile. This tells us that Oahu's temperature throughout the year is predictable, with slight variants.

![Dec Temp](https://user-images.githubusercontent.com/105765150/184143871-23204d29-b5ef-4975-a484-548bcae6b2f5.png)


# Summary
The result from June and December in the different seasons shows that the weather is very stable and has very low variation throughout the year. Based on our analysis, we strongly recommend our client invest in the Oahu surfing shop since the business can run all year long without significant negative weather impact. 
