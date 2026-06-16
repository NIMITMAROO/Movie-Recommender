# 🎬 Movie Recommendation System

A content-based movie recommendation system built using Machine Learning and deployed with Streamlit.

The application recommends movies similar to a selected movie by analyzing movie metadata and computing similarity scores using feature engineering and cosine similarity.

---

## 🚀 Live Demo

[Add Streamlit Link Here]

---

## 📌 Features

- Movie recommendation based on content similarity
- Interactive Streamlit user interface
- Fast recommendation retrieval using precomputed similarity matrix
- Trained and developed using Python and Scikit-Learn
- Ready for deployment on Streamlit Cloud

---

## 🧠 Machine Learning Approach

This project uses a **Content-Based Filtering** recommendation system.

### Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Engineering
4. Text Vectorization
5. Similarity Computation
6. Recommendation Generation

### Techniques Used

- Data Cleaning
- Feature Engineering
- Count Vectorization / Text Representation
- Cosine Similarity
- Recommendation Systems

---

## 🛠️ Tech Stack

### Languages

- Python

### Libraries

- Pandas
- NumPy
- Scikit-Learn
- Pickle
- Streamlit

### Development Environment

- Google Colab
- VS Code
- Git & GitHub

---

## 📂 Project Structure

```text
Movie-Recommender/
│
├── app.py
├── movies.pkl
├── similarity.pkl
├── requirements.txt
├── Project_Movie_Recommendation.ipynb
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/NIMITMAROO/Movie-Recommender.git

cd Movie-Recommender
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## 📊 Dataset

The dataset contains movie information including:

- Movie Title
- Genres
- Keywords
- Cast
- Crew
- Overview

These features are combined to generate movie similarity scores.

---

## 🎯 Example

### Input

```text
Iron Man
```

### Recommendations

```text
Iron Man 2
The Avengers
Captain America: Civil War
Thor
Guardians of the Galaxy
...
```

---

## 📈 Future Improvements

- Movie poster integration using TMDB API
- Search autocomplete
- Top-rated movie recommendations
- Hybrid recommendation system
- Collaborative filtering
- User authentication
- Personalized recommendations

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

Feel free to fork the repository and submit a pull request.

---

## 👨‍💻 Author

**Nimit Maroo**

GitHub: https://github.com/NIMITMAROO

---

## ⭐ If you found this project useful

Consider giving the repository a star.
