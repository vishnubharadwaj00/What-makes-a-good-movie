# What-makes-a-good-movie
The Billion Dollar Question: How do you make a good movie?

**The data:**

“The data set is comprised of 651 randomly sampled movies produced and released before 2016.” This means that random sampling is definitely involved in selecting the 651 movies. The results from the project can be generalized to the entire population of movies.

But we cannot be 100% sure of generalizability because it is entirely possible that the movies that only did well in the theatres may be included, and not the movies that didn’t make it on the imdb and Rotten Tomatoes list.

Random assignment has not been used, as there is no grouping of the movies done. So we cannot infer causality from the results of this analysis.

**The research question:**

Movies play a big part of our lives, from the start to the end. Some movies are not all that extraordinary and then there are some which completely change our lives. Obviously, each of us have our own metrics of a good movie. But overall, the best movies are accepted as the best by a good majority of people. So what makes it a good movie?

Is it possible to predict the audience score, based on combination of features (e.g. genre, reviews, runtime, release date, etc.)?

In other words, is there a correlation between audience score and one or more of the features present in the dataset(genre,reviews,runtime,release date, etc.)

This question is important to both audiences as well as the people who make the movie. For the people who make the movie, it’s a question of optimization to increase their profits. For audiences, it’s to choose from the plethora of options readily available today.

**Conclusion:**

In conclusion, we have found that out of the variables we have selected, some of them very highly insignificant, such as if the actor or actress has won an Oscar. It may not be altogether insignificant, just not significant with this combination of variables. The year of release in theatres was also insignificant here.

We can say that there is a correlation between the variables genre,runtime,MPAA Rating,Best Director Win, Best Picture Nomination and Best Picture Win, with the imdb score. Although we cannot be 100% sure to generalize to all the movies, and we definitely cannot infer causality.

The model created had an R^2 value of 0.3274, meaning 32.74% of the variability in the response variable can be explained by the model. The p-value is very small, <2.2e−16.

There are a few shortcomings with this method as well. Obviously, not all the variables were considered. This was purely my choice, and done for simplicity, so this may not be the most optimum model. Also, the sample size was only 650 when there are a vast number of movies being released every day, all around the world. Taking movies of different languages as well released in the US might help perhaps.

But, at least now, I have a simple way of choosing my next movie.
