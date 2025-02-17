# Recommendation System Project
## Overview

This project demonstrates how to build a recommendation system using collaborative filtering with the Singular Value Decomposition (SVD) algorithm. The system recommends movies to users based on their previous ratings from the MovieLens dataset.

Dataset

The project uses the MovieLens 100k dataset, which contains 100,000 ratings from 943 users on 1,682 movies. The dataset is widely used for benchmarking recommendation systems.

Prerequisites

numpy

pandas

scikit-learn

surprise

matplotlib

### Setup

Clone the Repository

https://github.com/Komal-prajapati/recommendation_system.git

cd recommendation-system

The dataset is included in the surprise library. You don't need to download it separately.

Run the Project

Execute the script to build and evaluate the recommendation system:

python recommendation_system.ipynb

Project Structure

recommendation_system.ipynb: Main script to build and evaluate the recommendation system.
README.md: This file.
Usage

Load the Dataset: The MovieLens dataset is loaded using the surprise library.

Build the Model: The SVD algorithm is used to build the recommendation model.

Evaluate the Model: The Root Mean Squared Error (RMSE) is calculated to assess the model's performance.

Make Recommendations: The system generates top movie recommendations for users based on estimated ratings.

Visualize Results: Optionally, the distribution of estimated ratings is plotted.
