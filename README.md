# Movie Recommendation System 🎬

This project is a **Movie Recommendation System** built using **Python** and **Streamlit**. It recommends movies similar to the one selected by the user based on content-based filtering using cosine similarity.

## 📌 Features

- Recommend similar movies based on content
- Display posters and movie details using the TMDB API
- Simple and interactive Streamlit web interface
- Uses precomputed similarity matrix for fast performance

## 🛠 Tech Stack

- Python
- Streamlit
- Pandas
- Scikit-learn
- Requests (for TMDB API)
- TMDB API

## ⚙️ How It Works

1. Select a movie from the dropdown list.
2. The system calculates cosine similarity scores.
3. Top 5 similar movies are displayed along with their posters.

## 📁 Files

- `app.py` – Main Streamlit application
- `movies.pkl` – Movie metadata
- `similarity.pkl` – Cosine similarity matrix (not included in repo due to size limit)

## 🔗 Download `similarity.pkl`

Due to GitHub's file size limitations, you can download the Project from Google Drive:

👉 [Download from Google Drive](https://drive.google.com/drive/folders/13Vd-k7kbCVl3ZSY3HxceyZDTNhu5NYRO?usp=drive_link)

Place it in the root directory of the project.

## ▶️ Run the Project

After cloning the repository and downloading the `.pkl` files:

```bash
pip install -r requirements.txt
streamlit run app.py
