# Book Recommender System

This project focuses on implementing a Book Recommender System using collaborative filtering and popularity-based approaches. It uses a dataset containing information about books, users, and ratings to provide personalized book recommendations.

## Project Structure

The project includes the following files and directories:

- `.ipynb_checkpoints`: Checkpoint files for Jupyter Notebook.
- `templates`: HTML templates for the web application.
- `index.html`: Main HTML file for the web application.
- `recommend.html`: HTML file for displaying recommended books.
- `Books.csv`: Dataset containing information about books.
- `DeepRec.png`: Image file used in the project.
- `Ratings.csv`: Dataset containing user ratings for books.
- `Users.csv`: Dataset containing information about users.
- `app.py`: Python file for the Flask web application.
- `book-recommender-system.ipynb`: Jupyter Notebook containing the code for the recommender system.
- `books.pkl`: Pickle file containing processed book data.
- `classicRec.png`: Image file used in the project.
- `popular.pkl`: Pickle file containing popularity-based recommendations.
- `pt.pkl`: Pickle file containing processed user-book ratings.
- `recsys_taxonomy2.png`: Image file used in the project.
- `similarity_scores.pkl`: Pickle file containing similarity scores for collaborative filtering.

## Dependencies

The project requires the following dependencies:

- NumPy
- Pandas
- Flask
- Scikit-learn (for cosine similarity)
- Matplotlib (optional for visualization)

## Usage

1. Ensure all dependencies are installed.
2. Run the `book-recommender-system.ipynb` notebook in a Jupyter environment to preprocess data and train the recommender models.
3. Use the Flask web application (`app.py`) to interactively recommend books based on user input.

## Features

- Popularity Based Recommender System: Recommends popular books based on the number of ratings and average ratings.
- Collaborative Filtering Based Recommender System: Recommends books based on user-user collaborative filtering using cosine similarity.
- Web Interface: Provides a user-friendly web interface for users to input preferences and receive book recommendations.

## How to Contribute

Contributions to this project are welcome! If you have any suggestions, improvements, or bug fixes, please feel free to create issues or pull requests.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and distribute the code as per the terms of the license.

---

© 2024 GitHub, Inc.
