# Movie Recommender System

## Overview
The Movie Recommender System is a project that utilizes Natural Language Processing (NLP) techniques, TF-IDF vectorization, and cosine similarity to recommend movies based on user preferences.

## DESCRIPTION
- The data set used is tmdb_5000_movies, it contains all the movie information in around 20 columns from budget, genres, tagline, Story ....., and so on.
- The Data is first preprocessed, and the information from all the columns is converted into text and then merged to form a single document for each movie containing all the information for that movie.
- Then, the document for each movie is converted into TF_IDF vectors to convert the textual information into vectors inside a vector space.
- The Cosine Similarity metric is used to find the similarities between the user's TF_IDF vectors of the Movie as the input and the TF_IDF vectors from the processed dataset.
  
## Features
- *TF-IDF Vectorization:* The project uses TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to convert movie descriptions into numerical vectors.
- *Cosine Similarity:* Cosine similarity is employed to measure the similarity between movie vectors, helping to recommend movies that are most similar to the user's preferences.
- *JSONDecodeError Handling:* The system handles JSONDecodeError gracefully, ensuring robust performance even when dealing with malformed JSON data.

## USAGE 
To run the Movie Recommender System, just run the given recommender_system.ipynb file
1. Enter the name of the movie you like.
2. Receive personalized movie recommendations based on your input.


## Dependencies
- make sure your system has all the libraries mentioned 
- Libraries /Modules for this project
- numpy
- pandas
- matplotlib
- json
- sklearn->TfidfVectorizer
- sklearn->cosine_similarity


## Contributing
If you'd like to contribute to the project, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: git checkout -b feature-name.
3. Commit your changes: git commit -m 'Add new feature'.
4. Push to the branch: git push origin feature-name.
5. Open a pull request.


## Contact

For any queriess or feedback, please contact 2021uee0125@iitjammu.ac.in







