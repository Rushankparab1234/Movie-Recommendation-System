# End-to-End Movie Recommendation System

A complete content-based movie recommendation system built from scratch using NLP, TF-IDF, and FastAPI.

## 📌 Project Overview

This project demonstrates how recommendation engines work behind platforms like Netflix and Prime Video. It covers the full lifecycle of a machine learning project, from data gathering and cleaning to building a production-ready API and UI.

## 🎯  Key Features

- Data Processing: Cleaning movie meta data and preparing featurs    
 (overvire, genres and tagline).
- NLP Pipeline: Text preprocessing using tokenization, stop word removal, lemmatization
- Recommendation Engine: Using TF-IDF Vectorization and Cosine Similarity to find  movies based on       content
- Deployment:
 Backend built with FastAPI.
 Frontend built with Streamlit.


## 🛠 Tech Stack
- Python
- Pandas & NumPy
- Scikit-learn (TF-IDF, Cosine Similarity)
- NLTK (Text Preprocessing)
-FastAPI (Backend)
- Streamlit (UI)
- TMDB API (Movie data/posters)


# 🚀Installation & Usage

### Clone the repository: 
    git clone https://github.com/Rushankparab1234/Movie-Recommendation-System.git


### Install dependencies: 
    pip install -r requirements.txt


### Set up your .env file with your TMDB_API_KEY.


### Run the API:
     uvicorn main:app --reload


### Run the frontend:
     streamlit run app.py


# 📊 Project Structure
- main.py: FastAPI application logic.
- app.py: Streamlit frontend.
- pkl: Pickle files containing the trained model and indices.



# 👨‍💻 Author

**Rushank Parab**

Bachelor of Engineering (Computer Science Engineering - AI & ML)

# ⭐ If you found this project helpful, consider giving it a star on GitHub!