# Song-recommendation-system

The code implements two recommendation algorithms:

Popularity-based Recommender:
Algorithm: Popularity-based recommendations, not using machine learning.
Success Measurement: Success is determined by recommending the most popular songs based on cumulative listen counts.

Item Similarity-based Recommender:
Algorithm: Item-based collaborative filtering using cosine similarity.
Success Measurement: Success is based on suggesting songs similar to those a user has listened to.

Key Points for Understanding:

Data Loading and Preprocessing:
Loads data from 'triplets_file.csv' and 'song_data.csv'.
Combines and cleans the data, creating a 'song' feature for better representation.
Limits to 10,000 samples for efficiency.

Popularity-Based Recommendation:
Recommends songs based on overall popularity (listen counts).

Item Similarity Recommendation:
Identifies similar songs based on user listening patterns.
Can recommend songs based on a user's history or specific song titles.
