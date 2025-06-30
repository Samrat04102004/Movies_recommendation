# 🎬 Movie Recommendation System

Discover your next favorite film with an intelligent **content-based movie recommendation system**.  
Built in **Python**, powered by advanced **data processing**, and deployed via a **user-friendly web interface**.

---

## 📌 Table of Contents

- [📖 Overview](#-overview)  
- [✨ Features](#-features)  
- [📽️ Demo](#-demo)  
- [⚙️ How It Works](#-how-it-works)  
- [🧰 Tech Stack](#-tech-stack)  
- [📁 Project Structure](#-project-structure)  
- [🙌 Acknowledgements](#-acknowledgements)  

---

## 📖 Overview

This project is a **movie recommendation system** that suggests similar movies based on a selected title.  
It uses **content-based filtering** by analyzing movie metadata and applying **natural language processing** to generate accurate recommendations.

---

## ✨ Features

- 🎯 **Personalized Recommendations** based on the selected movie  
- 🖥️ **Interactive Web Interface** using Streamlit  
- 🎞️ **Poster Previews** fetched in real-time from the TMDB API  
- ⚡ **Fast & Lightweight** with optimized similarity search  
- 🧹 **Clean Data Processing** using Pandas and NumPy  
- 🧠 **Intelligent Similarity Matching** with CountVectorizer and cosine similarity

---

## 📽️ Demo

🔗 **Live App**: [https://movies-recommendation-samrat.onrender.com](https://movies-recommendation-samrat.onrender.com)

---

## ⚙️ How It Works

1. **Data Preprocessing**  
   Cleans and merges key movie attributes (genres, keywords, cast, crew) using Pandas and NumPy.

2. **Feature Extraction**  
   Combines selected features into a single string and converts them into vectors using **CountVectorizer**.

3. **Similarity Calculation**  
   Computes **cosine similarity** between movie vectors to find the closest matches.

4. **Poster Retrieval**  
   Uses the **TMDB API** to fetch poster images and movie details for each recommendation.

5. **User Interaction**  
   User inputs a movie title and receives top recommendations with visual previews.

---

## 🧰 Tech Stack

| Component       | Technology Used               |
|----------------|-------------------------------|
| Programming     | Python                        |
| Data Handling   | Pandas, NumPy                 |
| ML/NLP          | Scikit-learn                  |
| Web Framework   | Streamlit                     |
| Deployment      | Render                        |
| API Integration | TMDB API                      |

---

## 📁 Project Structure

├── app.py               # Main Streamlit app

├── Movie.ipynb          # Jupyter notebook (exploration and logic)

├── movie_list.pkl       # Preprocessed movie list (Pickle file)

├── similarity.pkl       # Cosine similarity matrix (Pickle file)

├── requirements.txt     # Python package dependencies

├── .gitattributes       # Git LFS configuration for large files

└── README.md            # Project documentation

---

## 🙌 Acknowledgements

This project wouldn't be possible without the following resources and tools:

## 📊 Data & API Sources

- **Movie Metadata**: Sourced from public datasets from [TMDB](https://www.themoviedb.org/)
- **Posters & Movie Details**: Retrieved using the [TMDB API](https://developers.themoviedb.org/3).

## 🧠 Open-Source Libraries Used

- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Scikit-learn](https://scikit-learn.org/)
- [Streamlit](https://streamlit.io/)
- [Requests](https://docs.python-requests.org/)
- [TMDB API](https://developers.themoviedb.org/3)

---
