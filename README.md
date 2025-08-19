# Movie-Recommendation-System-
This repository contains a Movie Recommendation System that suggests films based on content similarity. The system leverages natural language processing (NLP) and machine learning techniques to process movie metadata and generate personalized recommendations.

The preprocess.py script handles data cleaning, tokenization, and feature extraction using TF-IDF vectorization, followed by cosine similarity to measure relationships between movies. It ensures high-quality input by removing stopwords, normalizing text, and combining relevant fields like genres, keywords, and overviews. Preprocessed data and models are stored for efficient retrieval.

The omdb_utils.py module integrates with the OMDb API, fetching detailed plots and posters for recommended movies to enrich the user experience.

A Jupyter Notebook (Movie_recommendation_system.ipynb) demonstrates how to train, test, and interact with the system step by step, making it easy to understand and extend.

This project is ideal for learning recommendation algorithms, text preprocessing, and API integration in Python.
