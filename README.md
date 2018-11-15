# MOVIE-tmdb-database
Exploratory data analysis on TMBD movie data

Introduction
This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.
Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters.
There are some odd characters in the ‘cast’ column. Don’t worry about cleaning them. You can leave them as is.
The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.


Questions:
Which genres are more popular and profitable
Which company make the most profit
What keywords are the most popular
Which movies are the most popular or profitable
The correlation between features

Procedure
1. Performed data cleaning(remove NaN values and non relevant features)
2. Transformed some features like 'genre' which have multiple values for single record into single value per record
3. Conducted visualization to explore data
