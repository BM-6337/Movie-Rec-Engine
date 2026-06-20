# Movie Recommendation Engine

## Project Overview

This project implements a content-based Movie Recommendation Engine that recommends movies similar to a user's selected movie. The system analyzes movie metadata such as genres, keywords, taglines, cast, and directors to identify relationships between movies and generate personalized recommendations.

The recommendation pipeline uses TF-IDF Vectorization and Cosine Similarity to compute similarity scores between movies and suggest the most relevant titles.

## Features

- Content-based movie recommendation system
- TF-IDF feature extraction from movie metadata
- Cosine similarity-based recommendation ranking
- Movie title matching for user queries
- Top-N similar movie recommendations
- Efficient similarity computation and retrieval

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity
- Jupyter Notebook

## Dataset

The project uses a movie metadata dataset containing:

- Movie Titles
- Genres
- Keywords
- Taglines
- Cast Information
- Director Information

The dataset is used to build feature vectors and calculate similarities between movies.

## Methodology

1. Load and preprocess movie metadata.
2. Handle missing values in relevant columns.
3. Combine important movie features into a single text representation.
4. Convert textual features into numerical vectors using TF-IDF.
5. Compute cosine similarity between all movies.
6. Match user-input movie titles.
7. Generate recommendations based on similarity scores.

## Example

### Input

```text
Avatar
```

### Recommended Movies

```text
Guardians of the Galaxy
John Carter
Star Trek
Jupiter Ascending
The Fifth Element
```

## Applications

- Movie recommendation platforms
- Content discovery systems
- Personalized entertainment suggestions
- Streaming service recommendation engines

## Future Improvements

- Collaborative filtering implementation
- Hybrid recommendation systems
- User-based personalization
- Web application deployment
- Real-time recommendation updates

## License
MIT
