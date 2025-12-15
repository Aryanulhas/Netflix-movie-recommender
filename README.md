# Netflix-movie-recommender
Netflix Movie Recommender

A content-based movie recommender system that suggests similar movies based on genre and plot description using TF-IDF vectorization and cosine similarity.

This project demonstrates how basic NLP techniques can be applied to build a similarity-based recommendation system in Python.

📌 Overview

The recommender works by converting movie text data into numerical vectors and measuring similarity between movies in a vector space.
It does not rely on user ratings or collaborative filtering, making it simple, interpretable, and suitable for learning core recommendation system concepts.

🧠 Methodology

Combine movie genre and description into a single text feature

Convert text into vectors using TF-IDF

Compute similarity using cosine similarity

Rank movies by similarity and return top recommendations

Handle minor spelling errors using fuzzy matching

📂 Dataset

A small custom dataset inspired by Netflix titles.

Columns used:

title

genre

description

▶️ Example
get_recommendations("Inception")


Output:

['Interstellar', 'The Matrix', 'Shutter Island', 'John Wick', 'The Dark Knight']

📁 Project Structure
netflix-movie-recommender/
├── recommender.ipynb
├── netflix_small.csv
├── requirements.txt
└── README.md

🛠️ Technologies Used

Python

Pandas

Scikit-learn

TF-IDF Vectorization

Cosine Similarity
