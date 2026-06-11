# 🎬 Movie Recommendation System

A full-stack Movie Recommendation System built using **FastAPI, Streamlit, Pandas, Scikit-Learn, and TMDB API**. The application allows users to discover movies, view detailed information, and receive personalized recommendations based on content similarity and genres.

## 🚀 Live Demo

* **Frontend:** Streamlit Cloud
* **Backend API:** Render
* **Movie Data:** TMDB (The Movie Database)

## ✨ Features

* 🔍 Search movies by title
* 🎬 View detailed movie information
* 📈 Trending, Popular, Top Rated, Upcoming, and Now Playing movies
* 🤖 Content-Based Recommendations using TF-IDF
* 🎭 Genre-Based Movie Recommendations
* 🖼 Movie posters and backdrops from TMDB
* ⚡ FastAPI backend for high-performance APIs
* 🌐 Responsive Streamlit frontend

## 🛠️ Tech Stack

### Frontend

* Streamlit
* Python
* Requests

### Backend

* FastAPI
* Uvicorn
* Pandas
* NumPy
* Scikit-Learn

### APIs & Data

* TMDB API
* TF-IDF Vectorization

## 📂 Project Structure

```bash
Movie_Recommended_System/
│
├── App.py                 # Streamlit Frontend
├── main.py                # FastAPI Backend
├── requirements.txt
├── df.pkl                 # Movie Dataset
├── tfidf.pkl              # TF-IDF Model
├── tfidf_matrix.pkl       # TF-IDF Matrix
├── indices.pkl            # Movie Indices
└── README.md
```

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/1vinay0056/Movie_Recommended_System.git
cd Movie_Recommended_System
```

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate Environment

```bash
.venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Backend

```bash
uvicorn main:app --reload
```

### Run Frontend

```bash
streamlit run App.py
```

## 📊 Recommendation Techniques

### Content-Based Filtering

Uses TF-IDF Vectorization to analyze movie overviews and identify similar movies.

### Genre-Based Recommendation

Suggests movies based on shared genres and movie categories.

## 🎯 Future Improvements

* User Authentication
* Hybrid Recommendation Engine
* Watchlist Feature
* Rating-Based Personalization
* Collaborative Filtering

  
 ## 🚀 Live Demo

- 🌐 Frontend: https://movierecommendedsystem-fvtgac79psdayqxljg4gk6.streamlit.app/
- ⚡ Backend API: https://movie-recommended-system-h45h.onrender.com

## 👨‍💻 Author

**Vinay Kumar**

* GitHub: https://github.com/1vinay0056
* LinkedIn:(http://www.linkedin.com/in/vinay-kumar-6634a0289)

---

⭐ If you found this project useful, don't forget to star the repository.
