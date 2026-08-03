# Hybrid Movie Recommendation System

## Overview

This project is a hybrid movie recommendation system developed using Python. It recommends movies by combining natural language processing, sentiment analysis, movie clustering, user preference clustering, and collaborative filtering.

The system analyzes user reviews, identifies user interests, and recommends movies based on similar users and movie categories.


## Features

* Extracts keywords from movie reviews using KeyBERT.
* Performs sentiment analysis using TextBlob.
* Groups movies into different clusters based on review content.
* Identifies user preferences from watched movies and ratings.
* Uses cosine similarity to find users with similar interests.
* Generates personalized movie recommendations.


## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* TextBlob
* KeyBERT
* Sentence Transformers
* Google Colab


## Project Structure

Movie-Recommendation-System/
│
├── personalized_recommendations.ipynb
├── reviews.csv
├── README.md
├── requirements.txt

## How to Run

1. Clone the repository.
2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Open the notebook in Google Colab or Jupyter Notebook.
4. Run all the cells in order.


## Dataset

The project uses a custom dataset (`reviews.csv`) containing:

* User ID
* User Name
* Movie ID
* Movie Name
* Movie Rating
* Movie Review


## Recommendation Process

1. Load the dataset.
2. Clean and preprocess review text.
3. Extract keywords from reviews.
4. Perform sentiment analysis.
5. Cluster movies based on extracted keywords.
6. Cluster users according to their movie preferences.
7. Calculate user similarity using collaborative filtering.
8. Recommend movies based on user interests and similar users.


## Future Improvements

* Use a larger dataset.
* Improve recommendation accuracy.
* Build a web interface using Flask or Streamlit.
* Integrate external movie APIs for additional movie information.
