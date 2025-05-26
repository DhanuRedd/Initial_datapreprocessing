# Netflix Initial_datapreprocessing steps

Netflix is one of the most popular media and video streaming platforms. They have over 10000 movies or tv shows available on their platform, as of mid-2021, they have over 222M Subscribers globally. This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.

🎯 Objective

Analyze the data and generate insights that could help Netflix in deciding which type of shows/movies to produce and how they can grow the business in different countries. It should be done with the help of proper visualizations in place.

## Dataset

| Feature      | Description                                                |
|:-------------|:-----------------------------------------------------------|
| Show_id      | Unique ID for every Movie / TV Show                        |
| Type         | Identifier - A Movie or TV Show                            |
| Title        | Title of the Movie / TV Show                               |
| Director     | Director of the Movie                                      |
| Cast         | Actors involved in the movie/show                          |
| Country      | Country where the movie/show was produced                  |
| Date_added   | Date it was added on Netflix                               |
| Release_year | Actual Release year of the movie/show                      |
| Rating       | TV Rating of the movie/show                                |
| Duration     | Total Duration - in minutes or number of seasons           |
| Listed_in    | Genre                                                      |
| Description  | The summary description                                    |

## Initial datapreprocessing steps done:

1. Observed the initial shape and understood the datatypes of the features in the dataset.

2. Splitted some string columns and used explode function to assign each string with a row inorder to identlfy deeper realtionships and trends in the data.

3. Found nulls in the dataset and replaced with appropriate values using np.fillna()

4. Formatted few column names to improve the clarity & understanding of the features.

5. Corrected the datatype of 'date_added' column.
