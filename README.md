# Elevvo-ML-Task-2

🎬 Movie Recommendation System

A recommendation system built using the MovieLens 100K dataset that suggests movies based on user similarity, item similarity, and matrix factorization (SVD). The system uses collaborative filtering techniques and evaluates performance using Precision@K.

📌Project Overview

Recommends movies to users based on their past ratings.

Implements User-Based Collaborative Filtering.

Implements Item-Based Collaborative Filtering.

Uses Matrix Factorization (SVD) for latent factor modeling.

Evaluates performance using Precision@K.

Includes visualizations (similarity heatmaps & method comparison).
----
🗂Dataset

MovieLens 100K Dataset

Available on Kaggle

Contains:

u.data → user ratings (user_id, movie_id, rating, timestamp)
u.item → movie details (movie_id, title, genres)

-----               

⚙Tools & Libraries

Python 3.x

Pandas → data manipulation

NumPy → numerical operations

Scikit-learn → cosine similarity, evaluation metrics
Matplotlib & Seaborn → visualizations

----
🚀Features

Build User-Item Matrix for ratings.

Compute User-User Similarity (Cosine Similarity).

Compute Item-Item Similarity.

Recommend Top-N Movies a user hasn’t seen.

Implement Matrix Factorization (SVD) for latent features.

Evaluate system with Precision@K.

Visualize similarities & compare recommendation methods.

----
📊 Visualizations

User Similarity Heatmap

Item Similarity Heatmap (subset for readability)
Precision@K Bar Chart (User vs Item vs SVD)

----
📈 Evaluation Metric

Precision@K → measures how many of the recommended movies are actually relevant for the user.

----
🔥 Bonus Features

Compare User-based vs Item-based vs SVD approaches.

Interactive recommendation (enter user_id to get recommendations).

Export recommendations for all users to CSV.

----
🖥 How to Run

Clone this repo / upload notebook to Google Colab.

Upload MovieLens dataset files (u.data, u.item).

Run cells step by step.

Try different users with the interactive input cell.

----
📌 Sample Output

Top 5 Recommendations for User 1 (SVD):

['Movie A', 'Movie B', 'Movie C', 'Movie D', 'Movie E']

---
📜Future Improvements

Implement Deep Learning (Neural Collaborative Filtering).

Add content-based filtering (using genres, tags, etc).

Deploy as a Web App (Streamlit/Flask) for real-time recommendations.

----
🤝Contributing

Feel free to fork this repo and improve the system by adding new recommendation algorithms or visualizations.

----
