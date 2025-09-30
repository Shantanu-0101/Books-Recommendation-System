# Books-Recommendation-System
A collaborative filtering-based recommendation system that suggests 4–5 similar books to the user based on their selection.
The web app is built with Flask and uses cosine similarity on preprocessed book data to recommend titles.


<h2>How it works:</h2>
-Dataset is preprocessed (removing duplicates, cleaning, and structuring).

-A cosine similarity matrix is created based on user-book interactions.

-When a user selects a book, the system finds the most similar books using collaborative filtering.

-Flask serves the recommendations on a user-friendly web page.


<h2>Demo:</h2>
Demo is in the folder named 'demo images' in this repo.


<h2>Installation:</h2>
# Clone the repository
git clone https://github.com/YourUsername/Books-Recommendation-System.git

 Navigate to the project directory
-cd Books-Recommendation-System

Install dependencies
-pip install -r requirements.txt

Run the Flask app
-python app.py

<h2>Future Improvements</h2>

-Use content-based filtering (book genres, authors, keywords)

- Hybrid model (collaborative + content-based)

- Improve UI/UX with better frontend design

- Deploy on Heroku/Render/Streamlit Cloud

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.
