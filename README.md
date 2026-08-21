# MovieMatch AI 🎬

MovieMatch AI is a Python-based personalized movie recommendation system created as a Data Analytics Hackathon project.

The project demonstrates how user preferences, viewing history, statistical analysis, and basic machine-learning techniques can be combined to generate personalized movie recommendations.

## Project Overview

MovieMatch AI uses a synthetic dataset containing movie information and user profiles. Each user has:

* A name and age
* Preferred movie genres
* A viewing history
* Ratings for previously watched movies

The recommendation system analyzes this information to suggest movies that match each user's interests while excluding movies they have already watched.

For example, the system can generate recommendations such as:

> "You may enjoy The Godfather because it matches your interest in Drama movies."

## Features

* Personalized movie recommendations
* Content-based filtering
* User viewing-history analysis
* Genre-based recommendation scoring
* Pearson correlation for comparing user rating behavior
* K-means clustering to group users with similar preferences
* Cluster-based recommendations
* Data preprocessing and feature engineering
* Interactive recommendation demo
* Data visualizations including bar charts, pie charts, line charts, and heatmaps
* Object-oriented recommendation system

## Technologies Used

* Python
* Pandas
* NumPy
* SciPy
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

## Recommendation Approach

The project uses several approaches to personalization.

### Content-Based Filtering

The primary recommendation engine identifies movies that match a user's preferred genres, removes movies the user has already watched, and ranks the remaining options.

### Pearson Correlation

SciPy's Pearson correlation is used to compare rating patterns between users. Users with similar rating behavior can provide useful information for future recommendations.

### K-Means Clustering

User genre preferences are converted into numerical features and SciPy's k-means clustering is used to group users with similar interests. Movies enjoyed by users in the same cluster can then be used to generate additional recommendations.

## Data Visualization

The notebook includes visualizations exploring:

* Distribution of movie genres
* Individual user genre preferences
* Movie ratings over time
* Average ratings by genre
* User genre preference patterns
* User clusters

## Dataset

The project uses a self-contained synthetic dataset created within the notebook. This allows the entire project to run without downloading external data files.

The current dataset contains 24 movies and 8 simulated users and is intended to demonstrate the recommendation techniques rather than serve as a production-scale recommendation system.

## Running the Project

Open `Hackathon_1.ipynb` in Jupyter Notebook or Google Colab and run the cells from top to bottom.

The final section contains an interactive MovieMatch AI demonstration where a user can be selected and personalized movie recommendations are generated.

## Future Improvements

Possible future improvements include:

* Expanding the movie and user datasets
* Using a real-world movie ratings dataset
* Adding more sophisticated collaborative filtering
* Incorporating additional features such as directors, actors, and release years into recommendation scoring
* Evaluating recommendation accuracy using larger test datasets

## Project Purpose

This project was created to demonstrate practical application of Python programming, data analysis, statistical methods, visualization, object-oriented programming, and introductory machine-learning concepts in a personalized recommendation system.
