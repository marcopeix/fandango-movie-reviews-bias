# Analyzing Movie Reviews

This project analyzes data from 4 major moive reviews sites: Rotten Tomatoes, Fandango, Metacritic and IMDB. Each site presents their rating on a different scale:
* RottenTomatoes: 0-100 with increments of 1
* Metacritic: 0-100 with increments of 1
* IMDB: 0-10 with increments of 0.1
* Fandango: 0-5 with increments of 0.5

It is important to note that only Fandango offers movie tickets, whereas the other sites are solely review sites.

The dataset compiles the score for many movies. Here is the description of some relevant columns:
* `FILM` - The title of the movie
* `RottenTomatoes` - The RottenTomatoes critic score
* `RottenTomatoes_User` - The RottenTomatoes user score
* `Metacritic` - The Metacritic critic score
* `Metacritic_User` - The Metacritic user score
* `IMDB` - The IMDB score
* `Fandango_Stars` - Number of stars for a movie according to Fandango

**Objective:** The objective is to determine if Fandango is biased in its reviews since it sells movie tickets. Therefore, is Fandango rating movies better to increase ticket sales?

**Techniques used:**
* Pandas, matplotlib
* Scipy.stats, linear regression
* Data visuzalition 
