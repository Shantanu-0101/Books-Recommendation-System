# Books-Recommendation-System
A collaborative filtering-based recommendation system that suggests 4–5 similar books to the user based on their selection.
The web app is built with Flask and uses cosine similarity on preprocessed book data to recommend titles.


<h2>How it works:</h2>
-Dataset is preprocessed (removing duplicates, cleaning, structuring).
-A cosine similarity matrix is created based on user-book interactions.
-When a user selects a book, the system finds the most similar books using collaborative filtering.
-Flask serves the recommendations on a user-friendly web page.
