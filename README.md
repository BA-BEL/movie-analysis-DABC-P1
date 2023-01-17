# DABC-Project-1
### Two Decades Of Movies: An analysis of movies available in Australia on Netflix, Stan and Amazon Prime.
----

## Project Overview:

This analysis was conducted to research:

- which platform provides the best quality of film on average;

- which genres have brought the most success over a 20 year period;

- which platform's films have the most diverse range of countries of origin;

- which platform hosts the most profitable films?

Using TMDb and IMDb, a dataset of movies released after 2000 was prepared. These movies were specified to be on Netflix, Stan, and Amazon Prime.

## Project Objectives:

1. Retrieve dataset for movies from 2000-2023 with information on their availability on three streaming platforms: Netflix, Amazon Prime Video and Stan.  

2. Perform data clean-up, filter and formatting for a standardised master dataset.  

3. Create visualizations for data analysis of the following:  

	a. Overview of movies available from the source. 
	
	b. Distribution of genres, ratings and budget per group year(5 year increments). 
	
	c. Comparison of movies across three streaming platforms: audience rating, runtime, country proudction, etc.   

----

## Using the code:

### All the required code can be found in submission-files/main.ipynb

#### IMDb

IMDb data can be downloaded from https://datasets.imdbws.com/

- files were too large to upload to the repository

- metadata for the datasets can be found on https://www.imdb.com/interfaces/


#### TMDb API

TMDb API requires an API key to make calls

- sign up here: https://www.themoviedb.org/signup

##### IMPORTANT API_KEY used for the tmDB Dataset ####
Use the following in the code wherever "api_key" is used in filter_params
api_key = "1058f1538710de09e2cc162ffc042010"


#### Geoapify

This API also requires a key, which can be obtained by signing up at https://myprojects.geoapify.com/register

