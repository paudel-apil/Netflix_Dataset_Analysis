# Project Summary: Netflix Dataset Analysis

### Overview
This dataset includes different Movies and TV-Shows with their description, cast starring, release date, genre etc
Brief EDA of these columns is done, also spaCy is used for NLP for the description.

### Key Insights:

## EDA
  - Number of movies is **5379** and tv shows is **2410**
  - **United States** produces the most of these while India is in the second.
  - Most used ratings for TV-Show is **MA** while for the movies is **R**.
  - Average duration of the movie is **99** minutes while for the show it is **1.77** season.
  - Most common genre is **Documentaries** in this dataset.

## NLP
  - List of most used words in the description are 'Life', 'Young', 'New', 'Family', etc
  - Sentiment Analysis is done for the descriptions using **NLTK VADER**
  - Recommendation system for the movies and tv shows is made using cosine similarity

#### Used Tools: numpy, pandas, matplotlib, seaborn, scikit-learn, spaCy
