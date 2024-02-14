# Prerequisites

Before running the movie recommendation system, you'll need to download the necessary data files and generate the PKL files locally. Follow the steps below to get started:

## Step 1: Download Data Files

- Download the movie dataset from Kaggle:
  [Movies Dataset]([https://www.kaggle.com/username/dataset-name](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv))
- Download movie credits dataset from Kaggle:
  [Credits Dataset]([https://www.kaggle.com/username/dataset-name](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_credits.csv))

## Step 2: Run Model Notebook

- Open the `model.ipynb` notebook in Jupyter Notebook.
- Run all cells in the notebook to preprocess the data and generate the PKL files (`movie_list.pkl` and `similarity.pkl`).

## Step 3: Run Streamlit App

- Once the PKL files are generated, navigate to the project directory in your terminal.
- Run the Streamlit app using the following command:
  
  ```
  streamlit run app.py
  ```
  
