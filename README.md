# Predicting Airbnb Listing Status Using NLP Models

## Project Overview
This project aims to predict the status of Airbnb listings using various Natural Language Processing (NLP) models. The project is divided into several key stages, ranging from initial data exploration to advanced NLP model building.

## Project Structure

### 1. Data Exploration
In this stage, we perform an initial exploration of the dataset to understand its structure and content. Key tasks include:
- Loading the data
- Visualizing basic statistics
- Identifying the multiple languages present in the text data

### 2. Translation
Given the multilingual nature of Airbnb listings, this stage involves translating non-English text into English to maintain consistency across the dataset.

### 3. Data Exploration and Preprocessing (after translation)
After translating the text, we revisit the data exploration phase to:
- Re-examine the translated data
- Perform additional preprocessing steps such as tokenization, stopword removal, and text normalization

### 5. Models Using Only Description and Host Information
In this stage, we build models using only the description of the listing and host information. The following approaches are employed:
- **TF-IDF (Term Frequency-Inverse Document Frequency):**
  - K-Nearest Neighbors (KNN)
  - Logistic Regression (LR)
  - Random Forest (RF)
- **Doc2Vec:**
  - K-Nearest Neighbors (KNN)
  - Logistic Regression (LR)
  - Random Forest (RF)
- **GloVe (Global Vectors for Word Representation):**
  - K-Nearest Neighbors (KNN)
  - Logistic Regression (LR)
  - Random Forest (RF)

### 7. Models Combining Description, Host Information, and Reviews
In this final stage, we enhance our models by incorporating reviews in addition to the listing description and host information:
- **Description + Host (TF-IDF) + Reviews (embeddings)**
- **Description + Host + Reviews (embeddings)**

## Files in the Repository

- `Predicting Airbnb listing status using NLP models.ipynb`: The Jupyter Notebook containing the code and analysis for the entire project.
- `README.md`: This file, providing an overview and structure of the project.
- `Data.txt`: Contains a link to the CSV file with the dataset used in this project.

This structure ensures a comprehensive approach to predicting the status of Airbnb listings using advanced NLP techniques, combining textual analysis with host and review data for improved accuracy.
