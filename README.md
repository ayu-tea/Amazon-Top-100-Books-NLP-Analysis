# Amazon-Top-100-Books-NLP-Analysis

## Project Objective
Build an NLP-powered analytics dashboard and classifier that extracts insights from Amazon’s Top 100 Bestselling Books and their customer reviews. The goal is to analyze reader sentiment, genre trends, and potentially auto-tag books based on review text or descriptions.

## Project Goals
* Perform exploratory data analysis (EDA) on bestseller trends, pricing, ratings, etc.
* Apply Natural Language Processing (NLP) techniques to analyze customer reviews.
* Build a genre classification model from book descriptions.
* Explore review sentiment (positive, negative, neutral) using NLP.
* Generate actionable reader and market insights.

## Techniques Used
* Text Preprocessing (Tokenization, Stopword Removal, Lemmatization)
* Sentiment Analysis (VADER / TextBlob / custom models)
* TF-IDF / Word2Vec / BERT embeddings
* Supervised Classification (MultinomialNB, Logistic Regression, SVM, etc.)
* Data Visualization (Matplotlib, Seaborn, Plotly)

Colab Link: [Code](https://colab.research.google.com/drive/1e-2H9CjntpVPy2zFibnXa0QzSY6HLzb1#scrollTo=aHCkYCWkQnpH)

## Dataset Overview: Amazon Top 100 Bestselling Books with Reviews
The datasets offers a comprehensive view of Amazon’s Top 100 Bestselling Books, along with detailed customer reviews, ratings, pricing, and metadata. Whether for analyzing reader sentiment, exploring genre trends, or building NLP models, this dataset provides a strong foundation for extracting meaningful insights from real-world literary data.

Kaggle link: [Datasets](https://www.kaggle.com/datasets/anshtanwar/top-200-trending-books-with-reviews)

| Feature                 | Description                                         |
| ----------------------- | --------------------------------------------------- |
| **Book Rank**           | Position in the Top 100 bestseller list             |
| **Book Title**          | Title of the book                                   |
| **Author**              | Name of the author                                  |
| **Price**               | Listed price (USD)                                  |
| **Rating**              | Average customer rating (1–5 scale)                 |
| **Year of Publication** | When the book was published                         |
| **Genre**               | Primary genre/category                              |
| **URL**                 | Link to Amazon listing                              |
| **Review Title**        | Headline of each customer review                    |
| **Reviewer**            | Name of the person reviewing                        |
| **Reviewer Rating**     | Individual rating (1–5 scale)                       |
| **Review Description**  | Full review text                                    |
| **Is_verified**         | Indicates if the review is from a verified purchase |
| **Date & Timestamp**    | When the review was posted                          |
| **ASIN**                | Unique Amazon product ID                            |
