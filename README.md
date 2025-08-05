# Project: Movie Recommender System Using Machine Learning!

This project recommends movies based on a selected movie using content-based filtering.

### 🔍 How Recommendation Works

1. **Data Preprocessing**:
   The dataset is processed to extract important features like:

   * Genre
   * Keywords
   * Overview
   * Cast
   * Crew

2. **Tag Creation**:
   All selected features are combined into a single text column called `tags`, which represents the content of the movie.

3. **Text Vectorization**:

   * The `tags` column is vectorized using **CountVectorizer**.
   * This transforms movie content into numerical vectors.

4. **Similarity Calculation**:

   * Cosine similarity is calculated between all movie vectors.
   * This gives a similarity score between each pair of movies.

5. **Recommendation**:

   * When a movie is selected, the system finds the **top 5 most similar movies** based on the cosine similarity scores.
   * It returns their **names and homepage URLs** (if available).

### ▶️ How to Use

1. Select a movie from the dropdown.
2. The system shows 5 recommended movies with their URLs.

<img width="480" height="349" alt="image" src="https://github.com/user-attachments/assets/64af99ea-29b0-42fb-a547-c0b0f9e796ba" />


