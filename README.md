# NLP Playground: From Text to Insights

## Unveiling the Magic of Language Models

### Summary:
This notebook is a journey through the realm of Natural Language Processing (NLP), where we explore the power of language models to understand and analyze text data.

### Part 1: Predicting Answer Scores 📚
- **Objective**: Predict scores of short answers using regression techniques.
- **Dataset**: [Answers Dataset](https://github.com/dbbrandt/short_answer_granding_capstone_project/blob/master/data/sag/answers.csv)
- **Key Steps**:
  - Preprocessed text data: normalized, tokenized, and removed stopwords.
  - Extracted features using Bag-of-Words (BoW), TF-IDF, and Word2Vec embeddings.
  - Trained regression models (Linear Regression, Decision Tree, SVR).
  - Evaluated models based on MSE, RMSE, and MAE.
- **Outcome**: SVM emerges as the top performer, offering the most accurate predictions.

### Part 2: Sentiment Analysis on Twitter 🐦
- **Objective**: Classify sentiments in tweets using various classification algorithms.
- **Dataset**: [Twitter Entity Sentiment Dataset](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)
- **Key Steps**:
  - Preprocessed tweets: removed URLs, punctuation, and emojis, and tokenized text.
  - Extracted features using TF-IDF, BoW, and Word2Vec embeddings.
  - Trained classification models (Decision Tree, SVM, Logistic Regression, Random Forest).
  - Evaluated models based on accuracy, F1 score, precision, and recall.
- **Outcome**: Decision Tree steals the show with stellar performance across metrics.

### Get Started:
1. Download the [Word2Vec embeddings](https://www.kaggle.com/datasets/leadbest/googlenewsvectorsnegative300).
2. Access the datasets:
   - Answers Dataset: [Link](https://github.com/dbbrandt/short_answer_granding_capstone_project/blob/master/data/sag/answers.csv)
   - Twitter Sentiment Dataset: [Link](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)

### Ready to Dive In?
Fire up your favorite Python environment and embark on a journey through the fascinating world of Natural Language Processing!

Happy Analyzing! 🚀✨
