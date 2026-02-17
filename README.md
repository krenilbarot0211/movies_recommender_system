# movies_recommender_system

🎬 Movie Recommender System (NLP + ML + FastAPI + Streamlit)

📌 Project Overview

This project is an end-to-end Movie Recommendation System built using Machine Learning and Natural Language Processing (NLP).
It recommends movies based on similarity in genre and story/plot using content-based filtering.

The application is deployed as a complete full-stack ML app:

* Streamlit for frontend UI
* FastAPI for backend API
* TMDB API integration for real movie posters and details



🚀 Features

✅ Recommend movies based on text similarity
✅ Uses Cosine Similarity to find the most similar movies
✅ Compares Bag of Words vs TF-IDF
✅ TF-IDF performed better and gives more meaningful recommendations
✅ Fetches movie posters & metadata using TMDB API
✅ Clean and interactive UI using Streamlit
✅ Backend served using FastAPI



🧠 Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* NLP (Text Preprocessing + Vectorization)
* FastAPI
* Streamlit
* TMDB API

---

📊 Workflow

1️⃣ Exploratory Data Analysis (EDA)

* Analyzed dataset structure
* Checked missing values and duplicates
* Studied distribution of movie genres and metadata

2️⃣ Data Preprocessing

* Removed missing/invalid entries
* Selected important columns for recommendation
* Combined relevant text features (genres + overview + keywords etc.)

3️⃣ NLP Preprocessing

Performed text cleaning such as:

* Removing punctuation
* Converting to lowercase
* Removing noise/unnecessary tokens
* Preparing text for vectorization

4️⃣ Feature Extraction (BoW vs TF-IDF)

To convert text into numerical form, I compared:

* Bag of Words (BoW)
* TF-IDF

⭐ Result: TF-IDF gave more accurate and meaningful recommendations

5️⃣ Similarity Calculation

Used:
✅ **Cosine Similarity**
to compute similarity between movies and recommend the most relevant ones.

---

🖥️ Application Architecture

Frontend

* Built using **Streamlit**
* User selects a movie title
* App returns recommended movies with posters

Backend

* Built using FastAPI
* Handles requests for recommendations and TMDB API calls

External API

TMDB API** is used to fetch:

  * Movie posters
  * Movie title info
  * Movie metadata



📌 How Recommendations Work

1. Movie dataset is cleaned and preprocessed
2. Movie descriptions/genres are vectorized using TF-IDF
3. Similarity between movies is calculated using Cosine Similarity
4. Top N most similar movies are returned as recommendations



📈 Results

* Implemented and compared **BoW vs TF-IDF**
* **TF-IDF** performed better for recommendations
* Recommendations are generated using **Cosine Similarity**



🏆 Key Learnings

This project helped me gain hands-on experience in:

* Building real-world **NLP pipelines**
* Text vectorization (**BoW vs TF-IDF**)
* Similarity-based recommendation systems
* Full-stack ML app development (**Streamlit + FastAPI**)
* Real-time API integration (**TMDB API**)



🔮 Future Improvements

* Add collaborative filtering
* Add hybrid recommendation system
* Improve UI with filters (genre/year/rating)
* Deploy on cloud (Render/Streamlit Cloud)



👨‍💻 Author

Krenil


