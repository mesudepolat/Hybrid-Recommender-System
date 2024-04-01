# Hybrid-Recommender-System


**Hybrid Recommendation System Project Overview:**

1. **User-Based Recommendation:**
   - Analyzes preferences of similar users based on movies watched by a specific user.
   - Recommends movies liked by similar users.
   - Steps involved:
     - Preparation of data by creating a user-movie dataframe.
     - Determining movies watched by the target user.
     - Accessing data and IDs of other users who watched the same movies.
     - Identifying the most similar users to the target user.
     - Calculating weighted ratings and recommendation scores.
     - Providing top movie recommendations based on scores.

2. **Item-Based Recommendation:**
   - Suggests similar movies based on the characteristics of a particular film.
   - Steps involved:
     - Extracting the last highly rated movie by the user.
     - Preprocessing data including titles, genres, and timestamps.
     - Creating a user-movie dataframe.
     - Calculating correlation between movies.
     - Sorting and selecting top similar movies.
     - Providing top movie recommendations.


- The hybrid system combines user-based and item-based recommendation methods.
- User-based method relies on user similarity to recommend movies.
- Item-based method suggests similar movies based on characteristics of a highly rated movie.
- The system aims to provide a diverse and personalized recommendation experience.
