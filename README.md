# Algonive Movie Recommendation System

## Project Overview

This project develops a Movie Recommendation System using the MovieLens dataset. The system uses both Content-Based Filtering and Collaborative Filtering to recommend movies to users.

## Dataset

The MovieLens dataset was used for this project.

- Number of Users: 610
- Number of Movies: 9,724
- Ratings Dataset: Movie ratings provided by users

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

## Methodology

### 1. Data Preprocessing

The Movies and Ratings datasets were loaded and checked for missing values and basic information.

### 2. Exploratory Data Analysis

Movie ratings and highly rated movies were analyzed using visualizations.

### 3. Content-Based Filtering

Movie genres were converted into numerical features and cosine similarity was used to identify movies with similar genres.

### 4. Collaborative Filtering

A user-movie rating matrix was created. Similar users were identified using cosine similarity, and movies liked by similar users were recommended.

### 5. Recommendation System

The system provides movie recommendations based on:

- Movies similar to a selected movie
- Preferences of similar users

## Evaluation

The recommendation system was evaluated using Precision@10.

**Average Precision@10: 0.0226 (2.26%)**

## Example

For example, when the user enters:

`Toy Story (1995)`

the system recommends movies with similar genres such as:

- Antz (1998)
- Toy Story 2 (1999)
- Monsters, Inc. (2001)
- Shrek the Third (2007)

## Conclusion

The project successfully demonstrates a movie recommendation system using both content-based and collaborative filtering techniques. The system analyzes movie genres and user rating patterns to generate recommendations.
