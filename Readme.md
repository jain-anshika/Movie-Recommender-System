# *Movie Match* - Movie Recommendation System

## Overview
This is a simple movie recommendation system built using Python and Streamlit. It recommends similar movies based on user input.

## Features
- Allows users to select a movie from a dropdown menu.
- Recommends similar movies based on the selected movie.
- Displays movie posters along with the recommendations.

## Data Sources
- Movie data: The movie dataset used in this project is obtained from Kaggle. The data is comprised of two files: `movies.csv` and `credits.csv`.
- Movie posters: Movie posters are fetched from The Movie Database (TMDb) API using an API key.

## Tech Stack
- Python
- Streamlit
- NLTK (Natural Language Toolkit)
- Pandas
- Scikit-learn
- Numpy

## File Structure
- `app.py`: Main Streamlit application file.
- `model.ipynb`: Jupyter Notebook containing the code for training the recommendation model.
- `movies.csv`: Raw movie data.
- `credits.csv`: Additional movie data.
- `movie_list.pkl`: Serialized file containing processed movie data.
- `similarity.pkl`: Serialized file containing similarity scores between movies.

## Contributing
Contributions are welcome! Please feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
