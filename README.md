# Recommendation System for Games using IGDB API

This project implements a recommendation system for games using data collected from the IGDB API. The system utilizes the CountVectorizer and Cosine Similarity algorithms to suggest games based on user preferences and game attributes.

## Algorithms

### CountVectorizer

The CountVectorizer algorithm is used to convert a collection of text documents into a matrix of token counts. It works by tokenizing the input text and building a vocabulary of known words. Each document is then converted into a vector of token counts, where each element in the vector represents the frequency of a word in the vocabulary within the document.

### Cosine Similarity

Cosine Similarity is a metric used to measure the similarity between two vectors by calculating the cosine of the angle between them. In the context of the recommendation system, it is used to measure the similarity between the user's preferences (input vector) and the game attributes (vectors of game descriptions or features). A higher cosine similarity indicates a higher degree of similarity between the two vectors.

## Usage

To use the recommendation system, follow these steps:


1.Get the files and run the Jupyter Notebook
2. Input user preferences.
3. Use the model to recommend games based on the user's preferences.



