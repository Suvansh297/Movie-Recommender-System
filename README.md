# Movie Recommender System

## Overview

This is a simple movie recommender system built using Python. The system recommends movies based on their tags (e.g., genre, plot, director) using a content-based filtering approach. It employs text processing techniques, including uni-grams, bi-grams, and tri-grams, to capture a richer context from movie tags.

## Features

- **Movie Recommendation:** Provides recommendations based on the similarity of movie tags.
- **Fuzzy Matching:** Handles user input with fuzzy matching to find the closest movie title in the database.
- **Dynamic Data Fetching:** Fetches additional movie data from the OMDb API if the movie is not found in the local database.
- **Advanced Vectorization:** Uses uni-grams, bi-grams, and tri-grams for vectorizing movie tags to capture more context and improve recommendations.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/movie-recommender-system.git
   cd movie-recommender-system
   
2. **Put API key:**
   It uses an API key from https://www.omdbapi.com/ which you can use
    ```bash
   API_KEY = 'YOUR_API_KEY'
