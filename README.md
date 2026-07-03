# Movie Recommendation System
@Shuang Liu
## Project Overview
This repository will introduce a data science project which aimed to provide movie recommendations for users based on approximately 5000 movies obtained from the [TMDB](https://developer.themoviedb.org/reference/getting-started). A series of data manipulation methods were applied to the data, including standardization, data imputation, feature selection, and feature engineering. Two kinds of recommendation systems were developed:
- **Demographic Filtering**: Generate generalized recommendations based on a self-defined weighted rating metric for each movie. 
- **Content Based Filtering**: Calculate Euclidean cosine similarity scores between movies after performing vectorization using TF-IDF and generating metadata, to get top 5 most similar movies.
### Data
**Description**: Merged multi-source datasets of movie data including features such as title, genres, keywords, ratings, etc., as well as cast and staff data.
## Repo Structure
```
├── README.md                              <- You are here
├
├── Movie Recommendation System.ipynb      <- Jupyter notebook containing EDA, feature enginnering, visuallizations, and two recommandation systems
├
├── requirements.txt                       <- Python package dependencies

```
## Key Findings
### Common Characteristics of Top-Scored Movies
#### Popular Movie Themes
<p align='center'>
  <img src='https://github.com/shual25/Movie_recommandation_system/blob/main/Graphs/keywords.png'>
</p>

#### Popular Movie Genres
<p align='center'>
  <img src='https://github.com/shual25/Movie_recommandation_system/blob/main/Graphs/genres.png'>
</p>

#### Percentage of Top-Scored Movies per Decades
<p align='center'>
  <img src='https://github.com/shual25/Movie_recommandation_system/blob/main/Graphs/decade.png'>
</p>

### Testing the CBF Recommendation System
<p align='center'>
  <img src='https://github.com/shual25/Movie_recommandation_system/blob/main/Graphs/Testing1.png'>
</p>

<p align='center'>
  <img src='https://github.com/shual25/Movie_recommandation_system/blob/main/Graphs/Testing2.png'>
</p>

For more details about data processing, visualizations, text analysis, and the construction of recommendation system, go check [**DATA ANALYSIS NOTEBOOK**](https://github.com/shual25/Movie_recommandation_system/blob/main/Movie%20Recommendation%20System.ipynb)
