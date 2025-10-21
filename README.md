# Learning Path Recommendation System

This project recommends personalized learning paths for interns based on their past learning activities.

## Objective
To suggest custom learning modules for each intern using collaborative filtering (matrix factorization).

## Description
The system analyzes intern-course interactions such as views, starts, completions, and ratings. It assigns weights to these activities and uses them to train a recommendation model that predicts which courses an intern should take next.

## Files
- courses.csv – Contains information about courses.
- interactions.csv – Contains data on how interns interacted with courses.
- learning_path_recommender.ipynb – Main notebook containing code for data processing, model training, and recommendations.
- requirements.txt – Python libraries needed to run the project.

## How to Run
1. Install required libraries:
   ```bash
   pip install -r requirements.txt
