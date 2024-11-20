# COS781 Project - Steam Data Analysis and Recommendation System

This GitHub repository hosts the code and resources for a project that analyzes Steam user behavior data and builds a recommendation system using various techniques. The project is designed to explore and visualize the dataset, generate recommendations, and evaluate the effectiveness of different recommendation methods.

## Features
### 1. Data Cleaning and Exploration
* Loads and preprocesses a dataset of Steam user behaviors.
* Cleans missing values and removes irrelevant columns.
* Provides summary statistics and insights.
### 2. Data Visualization
Bar plots of:
* The top 10 most played games.
* Games with the highest average playtime.
### 3. Recommendation Systems
Implements three recommendation approaches:

* Collaborative Filtering: Recommends games based on cosine similarity of user behaviors.
* Association Rule Mining: Identifies frequent itemsets using Apriori and computes association rules.
* Matrix Factorization: Applies Singular Value Decomposition (SVD) to recommend games.
  
### 4. Evaluation
Evaluates recommendation methods using:
* Precision
* Recall
* Mean Average Precision (MAP)

## Installation
### Prerequisites
* Python 3.12.4 or higher.
* Jupyter Notebook for running the .ipynb file.


## Dataset
The project uses the steam-200k.csv dataset, which contains Steam user behavior data, including user interactions such as purchases and playtime for various games. The dataset is loaded using pandas.

Dataset File: steam-200k.csv

Delimiter: ;

## Usage
### Running the Code
#### 1. Ensure the dataset is in the repository directory or adjust the file path in the code.
#### 2. Open the notebook Project.ipynb and execute cells sequentially to:
  * Clean and explore the data.
  * Visualize game statistics.
  * Build and evaluate recommendation systems.

## Outputs
Visualizations:
* Top 10 most played games.
* Top 10 games with the highest average playtime.
  
Recommendations for users and games using three techniques.

Evaluation metrics (Precision, Recall, MAP) for all methods.
