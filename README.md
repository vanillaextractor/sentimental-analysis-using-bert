# Sentiment Analysis using BERT

This project performs sentiment analysis on user reviews scraped from a Yelp page using the `nlptown/bert-base-multilingual-uncased-sentiment` model via Hugging Face Transformers. The model predicts sentiment scores ranging from 1 to 5.

---

## 🚀 Features

- Uses a pre-trained BERT model to analyze sentiment.
- Scrapes reviews from a live Yelp page.
- Applies sentiment classification to each review.
- Displays results in a structured pandas DataFrame.

---

## 🛠️ Installation

Install the required Python libraries:

```bash
pip install torch torchvision torchaudio
pip install transformers requests beautifulsoup4 pandas numpy
