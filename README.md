# Movie Recommendation System

## Project Overview
This project focuses on building a movie recommendation system using machine learning techniques. It involves analyzing user ratings data, calculating similarity between movies and users, and making personalized recommendations. Key steps include data collection, similarity computation, model development, and evaluation.

## Project Structure

### Part 1: Data Collection
**Objective**: Gather user ratings and movie metadata from a dataset.

**Files**:
- `collect_ratings_data.py`: Script to collect user ratings and movie data.

**Data Directories**:
- `data/`: Stores collected user ratings and movie metadata.

### Part 2: Similarity Calculation
**Objective**: Compute similarity between movies and users to determine preferences.

**Tools**:
- **Cosine Similarity**: Measures similarity between movie ratings by users.
- **Pandas**: Manipulates and cleans data for analysis.

**Files**:
- `calculate_similarity.py`: Calculates similarity matrices based on user ratings.

### Part 3: Building a Recommendation Model
**Objective**: Develop a machine learning model to make movie recommendations.

**Tools**:
- **Scikit-learn**: Implements collaborative filtering techniques.
- **Pandas**: Prepares data for model training and evaluation.

**Files**:
- `movie_recommendation.py`: Trains the recommendation model using collaborative filtering and evaluates its performance.
- `ratings.csv`: Input dataset containing user ratings and movie IDs.

## Key Steps

1. **Collect Ratings Data**: Obtain user ratings and movie metadata from the dataset.
2. **Calculate Similarity**: Compute similarity matrices between movies and users using cosine similarity.
3. **Build and Evaluate Model**: Train a recommendation model using collaborative filtering techniques to generate personalized movie recommendations.

## Results
- **Recommendation Accuracy**: Evaluate the model's performance in predicting user preferences based on historical ratings.
- **Personalized Recommendations**: Provide users with personalized movie suggestions based on their preferences and similarities to other users.

## Usage
1. **Setup Environment**:
   - Install Python 3.8+ and required packages using `pip install -r requirements.txt`.

2. **Run Data Collection**:
   - Execute `collect_ratings_data.py` to collect and save user ratings and movie data.

3. **Calculate Similarity**:
   - Run `calculate_similarity.py` to compute similarity matrices based on collected ratings data.

4. **Build and Evaluate Model**:
   - Execute `movie_recommendation.py` to train the recommendation model and evaluate its performance using prepared data.

## Requirements
- Python 3.8+
- Required Python packages: Pandas, Scikit-learn

## Conclusion
This project demonstrates the implementation of a movie recommendation system using collaborative filtering and similarity computation techniques. By leveraging user ratings and movie metadata, it provides personalized movie suggestions, enhancing user experience and engagement with movie content.
