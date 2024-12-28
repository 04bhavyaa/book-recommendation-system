## Book Recommendation System
A book recommendation system built using Popularity-Based Recommender, Collaborative Filtering, and Cosine Similarity. This project provides personalized book recommendations to users based on their preferences. It is implemented using Flask as the web framework.

### Features
- Popularity-Based Recommendation: Suggests books based on their popularity (e.g., top-rated books).
- Collaborative Filtering: Recommends books to a user based on the preferences of similar users.
- Cosine Similarity: Used to calculate similarity between user preferences and book attributes for recommendations.
- Flask Web App: A user-friendly interface where users can enter a book title and get recommendations.

### Tech Stack:
- Python: Core language for building the recommendation system.
- Flask: Web framework for creating the book recommender application.
- Pandas, Numpy, Matplotlib, Seaborn: Data manipulation and Visualization for handling, understanding book and user data.
- Cosine Similarity: Measure of similarity between two vectors of user preferences.
- Bootstrap: Front-end framework for responsive design.

### Usage: 
1. Home Page: Users see a collection of top 50 books using popularty based filtering.
2. Recommendation Page: After entering a book title, users will be presented with a list of recommended books, sorted based on collaborative filtering.
3. Recommendation Types:
    - Popularity-Based: Recommends top books based on overall ratings and votes.
    - Collaborative Filtering: Uses user behavior (such as previous ratings and preferences) to recommend books.
    - Cosine Similarity: Recommends books by finding similarities between user ratings or book attributes.

### Directory Structure:
```
Directory structure:
└── 04bhavyaa-book-recommendation-system/
    ├── book-recommendation-system.ipynb
    ├── app.py
    ├── book-data-eda.ipynb
    ├── data/
    │   ├── ratings_books_users.csv
    │   ├── book_data.pkl
    │   ├── popular_books.pkl
    │   ├── Ratings.csv
    │   ├── Users.csv
    │   ├── similarity_score.pkl
    │   ├── pivot_table_data.pkl
    │   └── Books.csv
    ├── README.md
    ├── templates/
    │   ├── index.html
    │   └── recommend.html
    └── static/
        └── styles.css
```

### Future Enhancements
1. Personalization: Allow users to create an account, rate books, and provide more tailored recommendations.
2. Machine Learning Models: Use advanced machine learning models like matrix factorization or deep learning for better recommendations.
3. Integration with Book APIs: Integrate with external APIs (like Google Books or Open Library) to fetch real-time book data and improve recommendations.
