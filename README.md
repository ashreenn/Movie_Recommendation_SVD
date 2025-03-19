# 🎬 Movie Recommendation System using SVD and Power Iteration

This repository implements a movie recommendation system using Singular Value Decomposition (SVD) with the Power Iteration method and deflation techniques. The system leverages user ratings data to generate personalized movie recommendations.

---

## 🚀 Overview

The project includes:

- **Power Iteration Method**: Numerical algorithm to compute the dominant singular vector and singular value of a matrix.
- **SVD with Deflation**: Iteratively computes multiple singular values and vectors by deflating the matrix after each iteration.
- **User-Item Matrix**: Creation of a matrix representing user ratings for movies, used as input for recommendations.

---

## 📂 Dataset

The recommendation system uses two CSV files:

- `ratings.csv`: Contains user ratings with columns `userId`, `movieId`, and `rating`.
- `movies.csv`: Contains movie details with columns `movieId`, `title`, and `genres`.

Please ensure these files are placed in your working directory before running the notebook.

---

## 🛠️ Installation & Dependencies

### Requirements

- Python 3.x
- NumPy
- Pandas
- Jupyter Notebook (optional, for running the notebook)

Install dependencies using pip:

