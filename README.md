# CODSOFT
I will post all the codsoft tasks that are assigned to me for my internship purpose open the folders to view the particular topics 

# Movie Recommendation System

This project is a simple movie recommendation system that suggests movies based on their similarity to a movie chosen by the user. It uses cosine similarity to compare the combined features of movies, including keywords, cast, genres, and directors.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This recommendation system aims to provide a list of movies similar to a given movie. It uses a dataset of movies and their associated metadata such as keywords, cast, genres, and director. By combining these features, the system calculates the similarity between movies and recommends the top 10 most similar movies.

## Features
- Combines multiple features (keywords, cast, genres, director) to determine movie similarity.
- Uses cosine similarity to compute the similarity scores between movies.
- Provides a list of the top 10 movies similar to a given movie.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/movie-recommendation-system.git
    ```
2. Navigate to the project directory:
    ```bash
    cd movie-recommendation-system
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Ensure you have the `movie_dataset.csv` file in the project directory.
2. Run the Python script:
    ```bash
    python Recommendation_system.py
    ```
3. The script will output the titles of the top 10 movies similar to the movie specified in the `movie_user_likes` variable.

## Contributing
Contributions are welcome! If you have any suggestions or improvements, please create a pull request or open an issue.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


# Tic Tac Toe AI

This project is a Tic Tac Toe game implemented in Python using Pygame. It includes an AI opponent that uses the Minimax algorithm to make decisions. The game allows for a single-player experience where the player competes against the AI.

## Features

- **Single-player mode**: Play against an AI opponent.
- **Minimax Algorithm**: The AI uses the Minimax algorithm to determine the best move.
- **Graphical Interface**: The game has a simple and clean graphical interface built with Pygame.
- **Restart functionality**: Press 'R' to restart the game.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/tictactoe-ai.git
    cd tictactoe-ai
    ```

2. **Create and activate a virtual environment** (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies**:
    ```bash
    pip install pygame numpy
    ```

## Usage

To start the game, run the following command:
```bash
python tictactoe.py

