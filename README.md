Movie Recommender System
This repository contains the code for a movie recommender system that suggests movies based on user input. The system leverages Natural Language Processing (NLP) and machine learning techniques to identify movies similar to your favorites.

Features
Data Loading: Reads the movie dataset using pandas.
Data Preprocessing: Fills missing values and combines selected features (genres, tagline, keywords, overview, title, cast, director) into a single string.
TF-IDF Vectorization: Converts text data into TF-IDF feature vectors.
Cosine Similarity: Computes similarity between movies using cosine similarity.
Movie Recommendation:
Takes a movie name as input.
Finds the closest match in the dataset.
Lists the top 30 movies similar to the input movie based on cosine similarity.
How It Works
Import Libraries: Import necessary libraries including pandas, numpy, difflib, TfidfVectorizer, and cosine_similarity.
Load Dataset: Load the movie dataset into a pandas DataFrame.
Data Cleaning: Handle missing values by filling them with empty strings.
Combine Features: Create a combined string for each movie that includes genres, tagline, keywords, overview, and title.
Vectorization: Convert the combined text data into TF-IDF vectors.
Similarity Calculation: Compute cosine similarity between all movie vectors.
User Input: Accept a movie name as input from the user.
Find Close Match: Use difflib to find the closest matching movie title in the dataset.
Recommend Movies: Retrieve and sort movies based on similarity scores and display the top 30 recommendations.
Usage
Clone the repository.
Ensure you have the necessary libraries installed: pandas, numpy, sklearn, and difflib.
Run the script and enter your favorite movie when prompted.
Get a list of recommended movies!
