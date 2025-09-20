# Star Wars Survey Analysis

This repository contains an analysis of the survey data about Star Wars fans.
The goal is to explore preferences and demographics using Python and data visualization.
This projects is based on [Star Wars Survey Analysis by Dataquest](https://www.youtube.com/watch?v=5bgr1YnLSyk&t=2797s).

## Data

The dataset used comes from [fivethirtyeight/star-wars-survey](https://github.com/fivethirtyeight/data/tree/master/star-wars-survey).
It contains responses from 1187 participants about:

- Favorite Star Wars movies
- Favorite characters
- Demographics (age, gender, location, etc.)

## Example Visualizations

### Movie Ranking

![Favorite Movie Distribution by Gender](src/figures/avg_movie_ranking.png)

### Percentage of Fans

![Percentage of Fans](src/figures/fans_percentage.png)

### Character Popularity

![Character Popularity](src/figures/character_popularity.png)

### Correlation of Character Popularity

![Correlation of Character Popularity](src/figures/character_popularity_correlation.png)

### Trilogy Preference

![Favorite Movie Correlation](src/figures/favorite_movie_correlation.png)

As you can see in the correlation matrix shown above, there is a clear correlation between (dis)liking the first three movies and the last three movies. When someone likes a movie of the prequel trilogy (Ep I-III), the probability of that person liking other movies in the prequel trilogy is higher than the probability of that person liking a movie from the original trilogy (Ep IV-VI). This is of course also true for the other way around.

![Trilogy Preference by Age](src/figures/trilogy_preference.png)

Since there is a correlation between liking individual movies and the trilogy they're from, we can group the two trilogies together and find out if there is a trend in which demographic likes which trilogy. Apparently, older people (>60) are more of a fan of the prequel trilogy and younger people like the original trilogy more.


## License

This project is licensed under the [MIT License](LICENSE).
