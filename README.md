#  10000 Movies Dataset 🎥
## 📚 Overview
This dataset collects movie data using The Movie Database (TMDB) API, which provides access to a comprehensive range of movie-related information. The dataset contains various attributes related to movies, categorized into four main sections:**movies**, **trailers**, **posters**, and **cast and crew**.

**Movies Dataset**: Contains essential details about each film, including title, release date, genres, revenue, budget, popularity,etc .
**Trailers Dataset**: Includes all trailer releases associated with each movie, providing video and metadata.
**Posters Dataset**: Holds various images, such as backdrops, logos, and posters, related to each movie.
**Cast and Crew Dataset**: Provides detailed information about the people involved in each production, such as actors, directors, producers, and other key crew members.
These datasets serve as a rich resource for exploring patterns and trends in the movie industry, helping to uncover correlations related to movie success factors like release dates, ratings, genres, and box office performance.

## ➕ Data Integration
All datasets can be merged based on a unique movie ID to facilitate further analysis. By using the unique movie ID, you can combine information from the movies, trailers, posters, and cast and crew datasets to create a more comprehensive view of each movie.

## 📩 Data Storage
Each dataset is saved as a separate JSON file, making it easy to handle and process while maintaining the structure provided by the TMDB API. This format ensures compatibility with various data analysis tools and makes it simple to load and analyze the data as needed.
![image.png](data:image/png;base64,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)
## 📊 Column Descriptions & Summary Statistics

We describe only the important columns for each dataset in the following sections.

**Common Columns for Movies Data:**

| Column Name              | Description |
|-------------------------|-------------|
| `id`              | A unique code assigned to each individual movie |
| `release date`                  | The date on which the movie was officially released. |
| `title`                 | Movie name. |
| `overview`               | A brief summary outlining the plot or content of the movie. |
| `popularity`                 | A numerical value indicating the level of popularity of the movie. |
| `vote count`    | The total number of votes received for the movie. |
| `vote average`  | The average rating given to the movie. |
| `original_language`              | The language used in that movie. |
| `genres`           | The categories or types of the movie, such as Action, Comedy, Thriller, etc. |
| `budget`              | The budget of the movie. |
| `revenue`             | The revenue of the movie. |
| `poster_path`             | The poster image . |


**Common Columns for Cast and Crew Data:**

| Column Name              | Description |
|-------------------------|-------------|
| `adult`              | Indicates if the content is rated for adults (`True` or `False`). |
| `gender`                  | The gender of the individual (0 = Unknown, 1 = Female, 2 = Male). |
| `id`                 | Unique identifier for the individual in TMDb. |
| `known_for_department`               |The department the individual is primarily known for (e.g., \"Acting\"). |
| `name`                 | The full name of the individual. |
| `original_name`    | The original name of the individual (if different from the displayed name). |
| `popularity`  | Popularity score reflecting the individual's prominence in the industry. |
| `cast_id`              | Unique identifier for the cast/crew record in a specific movie or TV show. |
| `character`           | The name of the character portrayed (for cast) or role held (for crew). |
| `credit_id`              | Unique identifier for the credit record. |
| `order`             | The order in which the individual appears in the credits. |

**Common Columns for Poster Data:**

| Column Name              | Description |
|-------------------------|-------------|
| `aspect_ratio`              | The proportion of the image width to height. |
| `height`                  | Image height |
| `iso_639_1`                 | The language code of the image (e.g. en, or null) |
| `file_path`               |The image file path to see the image(e.g. /9nhjGaFLKtddDPtPaX5EmKqsWdH.jpg) . |
| `vote_average`                 | The average vote score for this image. |
| `vote_count`    | The total number of votes received for the image. |
| `width`  | Image width. |

**Common Columns for Trailer Data:**

| Column Name              | Description |
|-------------------------|-------------|
| `iso_639_1`              | The language code of the trailer (e.g. en, or null) |
| `iso_3166_1`                  | The country code where the trailer was released(eg "US means United States") |
| `name`                 | The title or name of the trailer |
| `key`               |A unique identifier used to access the trailer on its hosting platform.  |
| `site`                 | The platform where the trailer is hosted. |
| `type`    | The type of video, such as 'Teaser', 'Trailer', 'Clip', or 'Featurette'. |
| `official`  |  A Boolean value (True or False) indicating whether the trailer is an officially released video. |

If you want to open image such as (backdrops, logos, posters), you have to use a base_url, a file_size and a file_path.
```
base_url = https://image.tmdb.org/t/p/
file_size = "w500"  # Choose a desired image size (w500, original, etc.)
file_path = "/hP7eihpJolSy4LXgyNfghYgPztG.png"
For example, https://image.tmdb.org/t/p/w500/hP7eihpJolSy4LXgyNfghYgPztG.png
```
If you want to open videos from trailer dataset, you have to combine the key ( 'TaFK_ULWBTc') and the site url(which is YouTube) to form the full URL of the video.


```
site_url= https://www.youtube.com/watch?v={key}
For example,https://www.youtube.com/watch?v=TaFK_ULWBTc
```

## 🧮 Selected Summary Statistics
The dataset consists of 10,000 movies, updated as of February 2025, including the latest movie details. After removing duplicate entries based on movie ID in main_movie.json, the final dataset contains 9,979 unique movies.

## 🧩 Limitations of the Data
The process of collecting this data encounters several challenges.

Some movies lack important details such as revenue, budget, popularity, or cast information, and there are inconsistencies in formatting (e.g popularity values like 0.059000000000000004).
Some movies appear multiple times due to different editions, re-releases, or translations. Even when fetching data from the same pagination, merging detailed information—such as trailers and posters—can result in mismatched movies.

That is why, we chose not to merge the data and instead created separate JSON files for further analysis of specific topics like trailers and posters.
The cast and crew dataset is exceptionally large, which can slow down your notebook if you attempt to load all data for a single movie. To manage this, it is necessary to break the data into smaller sections when analyzing specific details.

Furthermore, vote count and vote average were more actively used in the past, whereas newer movies receive fewer votes. This inconsistency makes it difficult to analyze real voting trends accurately.


## 💡 Example Use Cases
In our analysis, we primarily focus on the movies dataset to examine box office revenues by visualizing movie popularity, exploring the relationship between vote count and vote averages, identifying the most common genres, and determining trends in movie releases by year and month.

The trailer dataset allows for multimedia analysis, such as sentiment analysis on trailer content, comparing engagement metrics across different genres, or studying the correlation between trailer views and a movie’s financial success. Researchers can also explore the impact of trailer release timing on audience anticipation and box office performance.

The poster dataset is valuable for visual and design-related studies. Image analysis techniques can be used to examine color schemes and design elements commonly associated with different genres. Typography analysis can reveal how fonts and layouts evolve over time. Additionally, sentiment analysis can assess how audiences react to different types of poster designs.

The cast and crew dataset enables studies on representation, diversity, and career trajectories in the film industry. Researchers can analyze gender and ethnicity distribution among actors and filmmakers, identify collaborations between directors and actors, and track career growth over time. This dataset also supports network analysis to visualize connections between cast and crew members across different productions.

Overall, this dataset is a versatile resource for exploring various aspects of the film industry, from financial success and audience engagement to visual storytelling and industry representation.


## ⚡ Usage and Terms
This dataset is provided by The Movie Database (TMDb) API. Please refer to their [Terms of Use](https://www.themoviedb.org/terms-of-use) for more information.


