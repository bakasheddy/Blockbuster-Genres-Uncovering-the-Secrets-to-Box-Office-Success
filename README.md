# <center>TMDB movie data analysis</center>
## <center> by</center>
# <center> Shedrack David </center>

## Dataset overview
The Movie Database (TMDb) is a popular, user editable database for movies and TV shows.This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

For this project, i downloaded this piece of data from udacity students project1 data analysis course, and loaded it into jupyter notebook using pandas framework.
* I checked for data quality and tidiness and it was done both programatically using pandas functions like .info(), .duplicated(), .sample() and through observation of the data
* In tidy data each variable forms a column, each observation forms a row, each type of observational unit forms a table. i made sure all dataframe followed these rules changing wrong datatypes of entries to their appropraite datatype, droping null values and 0 value entries of columns
* Before cleaning, a copy of each dataframe's original was made using the .copy() function.
* After cleaning each data with code, i wrote a test code to check or assert that my data was clean using assert statement and a clean data was saved named TMDB-movies-clean.csv
* after cleaning this data, it is descovered that only 1287 from over 10000 of the data is clean for exploratory analysis

The wrangled dataset contains 1,287 entries in the dataset with 18 columns:
- id
- imdb_id
- popularity
- budget
- revenue
- original_title
- cast	director
- overview
- runtime
- genres
- production_companies
- release_date
- vote_count
- vote_average
- release_year
- budget_adj
- revenue_adj
- vote_levels


## Summary of Findings

1. movies with high vote count generate high revenue
2. movies with high vote count are very popular or have high popularity
3. movie genre that has been popular from year to year are adventure, action, fantasy, science fiction, and thriller
4. high budget movies yielded  high revenues
5. more movies are released in the 2000s than the 90s
6. most high revenue movies has longer runtime
7. high revenue movies has high vote counts, budget, runtime and popularity


## Key Insights for Presentation

#### For the original questions for this analysis:

> Which genres are most popular from year to year? 

From what i observed, Adventure, Action, Science fiction and Thriller has been the the most popular genre of movie release from year to year since 1980.
also, among the top 10 movie genres, "action" is the most popular and it appears even among a mix movie genre
> What kinds of properties are associated with movies that have high revenues?
 
 
 From the correlation matrix, variables which had strong correlation to revenue are Popularity, Vote_counts and Budget, appart from these, runtime seem to be also slightly correlated to revenue; in most cases, movies with longer runtime generated high revenue.
 movies with high vote count generate high revenue,  movies with high vote count are very popular or have high popularity, high budget movies yielded  high revenues, movies that have high revenue tend to be longer in and have no poor votes with very little people voting it as moderate.
 
 Most movies were released in the 21st century and there has been a steady inclease in movie release since the year 2000; there was a slight drop in 2009 but the progression continued until 2012 and 2013 which had a dramatic drop in release, i don't have enough data to deduce the reason for thish drop yet.

## Notes

dataset used for this exploration was gotten from [udacity](udacity.com) and can also be found on [kaggle](kaggle.com)

## Useful Feedback

Many of the data was removed during the wrangling phase due to incomplete data values; more can be gathered for further analysis

## Resources

- [udacity](udacity.com)
- [TMDB](https://www.themoviedb.org/)


```python

```
