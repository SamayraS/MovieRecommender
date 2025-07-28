# Smart Movie Suggestion App

A lightweight content-based movie suggestion web app built using Python and Streamlit. It leverages movie metadata to recommend similar titles.

## 🔧 Setup Instructions

1. **Download or clone** the project.

2. **Install Python and a code editor**:
   - [Python](https://www.python.org/downloads/)
   - [VS Code](https://code.visualstudio.com/download)

3. **Open the project folder** in VS Code or any editor.

4. **Install dependencies** using terminal:

```bash
pip install streamlit pandas requests pickle-mixin
```

5. **Run the app**:

```bash
streamlit run app.py
```

---

## 💡 About the Project

This app recommends movies using a content-based filtering approach. By analyzing movie metadata (such as genre, cast, and keywords), it suggests titles similar to the one selected by the user.

---

## 📁 File Overview

| File | Description |
|------|-------------|
| `app.py` | Core Streamlit app interface + logic |
| `movie-recommender-system.ipynb` | Data preprocessing and model building |
| `movie_dict.pkl` | Dictionary of movie info |
| `movies.pkl` | Refined dataset for app |
| `similarity.pkl` | Precomputed similarity matrix |
| `tmdb_5000_movies.csv` | Movie metadata |
| `tmdb_5000_credits.csv` | Cast and crew info |
| `requirements.txt` | Python dependencies |
| `setup.sh` / `Procfile` | Deployment configuration |
| `.gitignore`, `.gitattributes` | Git tracking settings |

---

## 🧠 Recommendation Logic

The system uses **content-based filtering**. It analyzes the features of movies a user likes and suggests similar ones based on tags, genre, and other metadata — without relying on ratings or user behavior.

---

## 📊 Dataset Source

- [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- More datasets at [Kaggle](https://www.kaggle.com/datasets)


