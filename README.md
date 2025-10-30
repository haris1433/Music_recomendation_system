# Music Recommendation System

A comprehensive music recommendation system that implements various recommendation algorithms to suggest songs to users based on their listening history and preferences.

## Overview

This project implements different types of recommendation systems to provide personalized music suggestions. It includes the following approaches:

1. **Popularity-Based Recommendations**
   - Recommends the most popular songs based on overall play counts
   - Simple yet effective for new users (cold-start problem)

2. **Content-Based Filtering**
   - Recommends songs similar to what the user has liked before
   - Based on song features and metadata

3. **Collaborative Filtering**
   - Recommends songs based on the preferences of similar users
   - Uses user-item interaction data

4. **Matrix Factorization (SVD)**
   - Advanced technique to discover latent features in user-item interactions
   - Provides more personalized recommendations

## Dataset

The system uses the following datasets:

1. `song_data.csv` - Contains detailed information about songs
2. `triplets_file.csv` - Contains user-song interaction data (user_id, song_id, play_count)

## Project Structure

```
Music_recommendation_system/
├── Dataset/
│   ├── song_data.csv
│   └── triplets_file.csv
└── Jupiter files/
    ├── Colabarative based.ipynb
    ├── Popularity Based Sin.ipynb
    ├── content based (Matrix Factorization based Recommender System(SVD)).ipynb
    └── content based.ipynb
```

## Getting Started

### Prerequisites

- Python 3.6+
- Jupyter Notebook
- Required Python packages (install using `pip install -r requirements.txt`)

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Music_recommendation_system
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open the desired notebook from the `Jupiter files` directory.

## Usage

1. **Popularity-Based Recommendations**:
   - Open `Popularity Based Sin.ipynb`
   - Run all cells to see the most popular songs

2. **Content-Based Filtering**:
   - Open `content based.ipynb`
   - Follow the notebook to get song recommendations based on content similarity

3. **Collaborative Filtering**:
   - Open `Colabarative based.ipynb`
   - The notebook demonstrates user-based collaborative filtering

4. **Matrix Factorization (SVD)**:
   - Open `content based (Matrix Factorization based Recommender System(SVD)).ipynb`
   - This implements a more advanced recommendation system using SVD

## Results

Each notebook includes visualizations and explanations of the results. The system can be evaluated using various metrics such as precision, recall, and RMSE (Root Mean Square Error).

## Future Enhancements

- Implement a hybrid recommendation system combining multiple approaches
- Add real-time recommendation capabilities
- Create a web interface for the recommendation system
- Include audio feature analysis for better content-based recommendations

## Acknowledgments

- The project utilizes the Million Song Dataset for music recommendations
- Various open-source libraries and frameworks that made this project possible
