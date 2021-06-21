# Movies-ETL

### Resources 

* Wikipedia Movie Data
* Kaggle Movie Data
* Python 3.7
* pgAdmin 4.5
* PostgreSQL v13

## Project Overview

The purpose of this project is, within the scope of the Amazing Prime Hackathon, to create an automated pipeline that takes in new movie data, performs the appropriate transformations, and loads the data into existing tables. The existing code is refactored into one function that performs the ETL process.

## Requested Objectives

1. Write an ETL function to read three data files,
2. Extract and transform the Wikipedia data,
3. Extract and transform the Kaggle and rating data,
4. Load the data to a PostgreSQL Movie Database.

## Procedure 

1. I consolidated the redundant data,
2. Removed the duplicate data, 
3. Formatted and grouped the data.
4. The Kaggle and rating data were then merged with the Wikipedia movies DataFrame.

# Summary 

The ETL function collects and cleans movie data from different sources (Wikipedia JSON and Kaggle csv files). It transforms and merges the data and loads it into two updatable PostgreSQL dataset tables ready to be used by the hackathon participants for their analysis.
