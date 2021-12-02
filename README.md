<!-- Add banner here -->

# Restaurant-Review-Sentiment-Analysis

<!-- Add buttons here -->
![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/ridhed/Weather-Dataset-Analysis?include_prereleases)
![GitHub last commit](https://img.shields.io/github/last-commit/ridhed/Weather-Dataset-Analysis)
![GitHub issues](https://img.shields.io/github/issues-raw/ridhed/Weather-Dataset-Analysis)
![GitHub pull requests](https://img.shields.io/github/issues-pr/ridhed/Weather-Dataset-Analysis)
![GitHub](https://img.shields.io/github/license/ridhed/Weather-Dataset-Analysis)

<!-- Described the project in brief -->
Sentiment Analysis using Naive bayes  classifier on Restaurant reviews.


# Table of contents

- [Project Title](#project-title)
- [DataSet](#kaggle-dataset-link)
- [How I Did The Weather Dataset Analysis](#how-i-did-the-restaurent-review-dataset-analysis)

# Kaggle Dataset Link
https://www.kaggle.com/akram24/restaurant-reviews

[(Back to top)](#table-of-contents)

# How I Did The Restaurent Review Dataset Analysis
1. Data Cleaning and Preprocessing
   * Used PorterStemmer library to find the root word and Stemming the words and removing the stopwords.
   * Creating a corpus to store collection of words.
   * Create Bag of words model A bag-of-words model, or BoW for short, is a way of extracting features from text for use in modeling.

3. Training Model
   * Train and fitted model based on MultinomialNB Naïve Bayes algorithm .
   * Calculated the Accuracy, Precision and Recall Scores of the Model.
   * Made the confusion matrix and plotted it.

5. Hyperparameter Tuning 
   * Hypertuned the alpha parameter which by default is 1.0 and is known for Additive (Laplace/Lidstone) smoothing parameter (0 for no smoothing).
       
[(Back to top)](#table-of-contents)

[GNU General Public License version 3](https://opensource.org/licenses/GPL-3.0)
