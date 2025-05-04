## News Article Categorization using Sentence Transformers

This project applies unsupervised machine learning to automatically cluster news articles based on their content. Using sentence embeddings and KMeans clustering, it groups articles from domains like politics, sports, tech, etc., without any labeled data.

#### 📌 Features

-   Sentence embeddings using sentence-transformers
-   Clustering using KMeans
-   Visualizations: PCA cluster plot and Elbow Curve
-   Dimensionality reduction with PCA

#### 📁 Project Structure

-   article_modeling_project.ipynb: Main script for data processing, modeling, and visualization.
-   data: Directory containing the dataset (not included in the repository).
-   requirements.txt: List of required Python libraries.
-   README.md: The project instructions.

#### 📦 Dataset

-   Source: BBC News Summary dataset
-   Download: Download the dataset from Kaggle: [Kaggle: BBC News Summary](https://www.kaggle.com/datasets/pariza/bbc-news-summary), unzip it, and place it in the project data directory.
-   Structure: Articles are organized in subdirectories by category (e.g., business, entertainment, politics, sport, tech).
-   Size: Approximately 2225 articles

#### ⚙️ Setup Instructions

1. Clone the repository
   git clone https://github.com/rvalani-ms/news-article-categorization-clustering
2. Install dependencies
   pip install -r requirements.txt
