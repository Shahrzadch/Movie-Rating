**Movie Rating**

There are 3 tables.
The Movies table contains movie_id and title.
movie_id is the primary key (column with unique values) for this table. title is the name of the movie.

The Users has user_id and name.
user_id is the primary key (column with unique values) for this table.

ovieRating table contains movie_id, user_id, rating, and created_at.
(movie_id, user_id) is the primary key (column with unique values) for this table.
This table contains the rating of a movie by a user in their review.
created_at is the user's review date. 

Write a solution to:
Find the name of the user who has rated the greatest number of movies. In case of a tie, return the lexicographically smaller user name.
Find the movie name with the highest average rating in February 2020. In case of a tie, return the lexicographically smaller movie name.
