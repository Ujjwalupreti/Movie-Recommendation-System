# 🍿 Movie Recommender System

[![FastAPI](https://img.shields.io/badge/Backend-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Streamlit](https://img.shields.io/badge/Frontend-Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Scikit-Learn](https://img.shields.io/badge/ML-Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)

## 📌 Project Overview
The **Movie Recommender System** is a full-stack machine learning application that suggests movies to users based on collaborative filtering and item similarity. By analyzing historical user ratings (using the MovieLens dataset), the system computes a cosine similarity matrix to instantly find and recommend visually and contextually similar films.

Beyond simple recommendations, the platform includes a real-time analytics loop that tracks user clicks on recommended movies to calculate conversion rates, alongside an interactive dashboard for adding new movies directly into the database.

### 🎯 Key Features
* **🤖 Similarity Engine:** Uses Scikit-Learn to compute a Cosine Similarity matrix across user ratings to identify closely related movies.
* **⚡ FastAPI Backend:** A high-performance REST API handling inference requests, database commits, and click-tracking logic.
* **📊 Interactive Dashboard:** A Streamlit frontend allowing users to select movies, view top-4 recommendations, and monitor real-time "Click Rates" for suggested titles.
* **🔄 Dynamic Database:** Robust SQLAlchemy ORM integration supporting both SQLite (local) and PostgreSQL, allowing for dynamic movie ingestion and rating updates.

---

## ⚙️ Technology Stack

| Component | Tech Stack | Description |
| :--- | :--- | :--- |
| **Frontend** | Streamlit | Rapid, interactive Python web application framework for data tools |
| **Backend** | FastAPI, Uvicorn | Asynchronous Python REST API framework handling ML inference |
| **Database** | PostgreSQL / SQLite | Relational database managed via SQLAlchemy ORM (`models.py`) |
| **Machine Learning** | Scikit-Learn, Pandas, NumPy | Data manipulation and Vector distance calculations (Cosine Similarity) |

---

# 🚧 WORK IN PROGRESS
