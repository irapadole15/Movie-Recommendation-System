# Movie Recommendation System

This repository contains a **collaborative filtering-based movie recommendation system** built using Python and popular data science libraries such as **Pandas, NumPy, and Surprise**. The project demonstrates how to preprocess datasets, clean data, and implement a recommendation model that suggests movies to users based on their preferences.

---

## Project Overview

The goal of this project is to build a **movie recommendation system** that suggests movies to users based on their preferences and past interactions. The project is divided into two main stages:

1. **Data Acquisition and Cleaning**

   * Load and clean the provided movie and rating datasets.
   * Handle missing values, remove duplicates, and preprocess the data for modeling.

2. **Recommendation System**

   * Implement **collaborative filtering** to predict user ratings.
   * Generate personalized movie recommendations based on user behavior.

---

## Dataset Description

* **`movies.csv`**: Contains details about movies.
  **Columns:** `movieId`, `title`, `genres`, and optionally `poster_path`.

* **`ratings_cleaned.csv`**: Contains user ratings for movies.
  **Columns:** `userId`, `movieId`, `rating`, `timestamp`.

---

## Results

The recommendation system predicts **top-rated movies for users** using collaborative filtering. It provides **accurate suggestions based on user behavior and preferences**, allowing personalized recommendations.

---

## Notebooks

* **`data_acquisition_cleaning.ipynb`**: Performs data cleaning and preprocessing.
* **`recommendation_system.ipynb`**: Implements the collaborative filtering model and generates recommendations.

---

## Dependencies

* Python 3.x
* pandas
* numpy
* scikit-learn
* surprise
* Jupyter Notebook

You can install the required dependencies using:

```bash
pip install pandas numpy scikit-learn scikit-surprise jupyter
```

---

## How to Use

1. Clone the repository:

```bash
git clone <repository_url>
```

2. Open the notebooks in **Jupyter Notebook**.
3. Run `data_acquisition_cleaning.ipynb` to preprocess datasets.
4. Run `recommendation_system.ipynb` to generate movie recommendations.

---

## Contact

For questions, collaborations, or contributions, reach out to:

**Ira Padole**
📧 [irapadole2004@gmail.com](mailto:irapadole2004@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/ira-padole-3487062b4) • [Portfolio](https://irapadole.com)

---


