# Movie-Recommendation-system

This repository contains a movie recommendation system that employs both content-based and collaborative filtering techniques to provide personalized movie recommendations. Additionally, the system uses web scraping to gather relevant data, enhancing the accuracy and breadth of the recommendations.

## Features

- **Content-Based Filtering**: Recommends movies based on the similarity of movie attributes, such as genre, director, cast, and plot summary, to the user's preferences.
- **Collaborative Filtering**: Utilizes user interaction data (e.g., ratings, watch history) to identify patterns and recommend movies that similar users have enjoyed.
- **Web Scraping**: Extracts movie data from various sources on the internet to ensure a comprehensive and up-to-date database for making recommendations.

## Tech Stack

- **Python**: Core programming language used for implementing the recommendation algorithms and web scraping scripts.
- **Pandas**: Used for data manipulation and analysis.
- **BeautifulSoup**: Library for web scraping to extract movie data.
- **Scikit-Learn**: Provides machine learning tools for building recommendation models.
- **Flask**: Web framework to create a user-friendly interface for interacting with the recommendation system.
- **HTML/CSS**: Front-end technologies to design the web interface.

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/CoderYashVij/Movie-Recommendation-system.git
   cd Movie-Recommendation-system
   ```

2. **Install the required packages**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**:
   ```bash
   python app.py
   ```

4. **Open your web browser** and navigate to `http://127.0.0.1:5000` to start using the movie recommendation system.

## Usage

- **Content-Based Recommendations**: Input your favorite movies to get recommendations based on similar attributes.
- **Collaborative Filtering Recommendations**: Get personalized movie suggestions based on your and other users' watch history and ratings.
- **Web Scraping**: The system periodically scrapes movie information from the web to keep the recommendation database updated.

## Contributing

Contributions are welcome! If you have ideas for new features or improvements, please open an issue or submit a pull request.
