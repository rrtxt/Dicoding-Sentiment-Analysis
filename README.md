# 📊 Duolingo Review Sentiment Classification
This project performs sentiment classification on user reviews of the Duolingo app scraped from the Google Play Store. The reviews are labeled using lexicon-based sentiment analysis and categorized into positive, neutral, and negative sentiments.

### 📌 Project Goals
Scrape user reviews of the Duolingo app from the Google Play Store.

Label each review's sentiment using a lexicon-based approach.

Build and evaluate sentiment classification models (e.g., Naive Bayes, SVM, etc.).

Analyze review trends and user feedback to uncover common sentiment themes.

### 📥 Data Collection
Reviews were scraped using the Google Play Scraper tool, focusing on recent and relevant user feedback.

### 🏷️ Sentiment Labeling
Reviews were labeled using lexicon-based sentiment analysis, which assigns sentiment scores to words and phrases and aggregates them to classify the overall tone of the review:

Positive: Strongly favorable tone

Neutral: Mixed or no strong sentiment

Negative: Unfavorable tone

### ⚙️ Methods
Preprocessing: Cleaning text, tokenization, stopword removal, etc.

Feature Extraction: TF-IDF or word embeddings

Modeling: Traditional ML models (Logistic Regression, Naive Bayes, etc.)

Evaluation: Accuracy, precision, recall, F1-score, confusion matrix

### 📈 Results
Include summary of key results here once available, such as:

Best model: Logistic Regression

Accuracy: XX%

Common issues: sarcasm, short reviews, etc.

### 🛠️ Tech Stack
Python

scikit-learn

pandas, NumPy

NLTK / spaCy

Jupyter Notebook

### ✅ Future Work
- Incorporate deep learning (e.g., LSTM or BERT)

- Improve labeling using hybrid (lexicon + ML) methods

- Expand dataset across languages or time periods
