# MovieLens Recommender System

This project demonstrates the process of building, training, and deploying a collaborative filtering recommender system using Apache Spark and ALS (Alternating Least Squares). The system uses the MovieLens dataset to recommend movies based on user ratings.

## Key Features

- Data preprocessing with Spark DataFrames
- ALS model training and evaluation for collaborative filtering
- Hyperparameter tuning for the best performance
- Model persistence and deployment using Flask and Docker
- Integration with Jupyter Lab for interactive development

## Project Components

1. **Data Loading**: Loads ratings and movie metadata using Spark.
2. **Model Training**: Trains an ALS model to make movie recommendations based on user ratings.
3. **Model Evaluation**: Evaluates the model using Root Mean Squared Error (RMSE).
4. **Model Deployment**: Deploys the trained model using Flask and Docker containers.

