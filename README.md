DATABASE DESCRIPTION:
This database will store a set of films and can be used to find trends among films in the set, or for general info on films (think IMDb). 
We will have a table for movies, directors, lead actors, and genres. 

We have a table for our movies. Since it is possible for two movies to have the same name, we have a unique ID for each movie. 
Each movie must have a name, release date, director, an associated genre, and a lead actor. It can optionally have a worldwide gross figure, and a budget - but these are optional as they are not always known information. 

Although there are many directors, it is possible that there may be more than one movie directed by the same person, so we have a separate table for our directors. It is possible for two different directors to have the same name, and so we use a unique directorID to identify the director. 

The same problem we have for directors applies to our actors, and so we have a table for our actors analogous to our director table.

It is likely that different movies will have the same genre. For robustness we will have a separate table for our genres, where each genre can simply be referenced by a unique genreID. 


## Submit each assessment in a separate folder within the repository
* /DatabaseDesign
* /HotelDatabase
