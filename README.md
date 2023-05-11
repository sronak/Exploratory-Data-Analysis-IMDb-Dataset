# Exploratory Data Analysis : IMDb Dataset

This repository contains code and analysis for performing Exploratory Data Analysis (EDA) on the IMDb dataset. The IMDb dataset is a comprehensive collection of information about movies, including details about movies themselves, ratings, directors, writers, and cast members.
In this notebook, we will explore IMDb’s dataset which is available online and refreshed daily.

https://www.imdb.com/interfaces/
# Dataset Overview

The IMDb dataset consists of several tables:

1. **Title Basics**: Contains basic information about movies, such as the movie title, release year, genres, and more.

2. **Title Ratings**: Includes ratings information for movies, such as average rating, number of votes, and more.

3. **Name Basics**: Provides information about individuals involved in the movie industry, including their names, birth/death years, primary professions, and known titles.

4. **Title Crew**: Contains information about the directors and writers associated with each movie.

5. **Title Principals**: Includes details about the principal cast and crew members associated with each movie.

# Exploratory Data Analysis

The EDA performed on the IMDb dataset covers various aspects of the data to gain insights and understand patterns. Here are some of the key analyses conducted:

- Distribution of movie ratings: A histogram is plotted to visualize the distribution of movie ratings, providing an overview of the overall rating trends.

- Movie genres analysis: The frequency of different genres in the dataset is explored, and the median rating for each genre is calculated. A bar plot is generated to show the median ratings for each genre, allowing us to identify the genres with higher average ratings.

- Relationship between movie runtime and ratings: Movies are grouped based on their runtime, and a box plot is generated to analyze the relationship between movie runtime and average rating. This helps us determine if there is a tendency for users to rate movies with longer runtimes higher.

- Analysis of birth year distribution: The birth year distribution of individuals in the dataset is visualized using a histogram, providing insights into the time range of individuals included in the dataset.

- Lifespan analysis: For individuals with available birth and death year information, the distribution of their lifespans is explored. A histogram is generated, showing the distribution of ages at death.

- Successful directors and writers: Directors and writers are analyzed based on their success criteria, which include factors such as average movie rating, number of votes, and number of films. The top successful directors and writers are identified and visualized using scatter plots.

# Usage
To replicate the EDA performed on the IMDb dataset, follow these steps:

1. Clone this repository to your local machine.

2. Download the IMDb dataset and place the necessary files in the repository folder. The required files include:

- `title.basics.tsv.gz`
- `title.ratings.tsv.gz`
- `name.basics.tsv.gz`
- `title.crew.tsv.gz`
- `title.principals.tsv.gz`

3. Run the Jupyter Notebook IMDb_Dataset_EDA.ipynb to execute the code and generate the analysis.

4. Explore the generated visualizations and analysis to gain insights into the IMDb dataset.

# Conclusion
The EDA performed on the IMDb dataset provides a comprehensive analysis of various aspects, including movie ratings, genres, cast/crew members, and more. By exploring the dataset and visualizing the data, we gain valuable insights into the movie industry and its key contributors.

Feel free to explore the code and analysis provided in this repository to gain a deeper understanding of the IMDb dataset and conduct your own analyses.
