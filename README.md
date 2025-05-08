# ☀️ Solar Sentiment & Price Prediction

**Solar_Sentiment_Price_Prediction** is a machine learning pipeline designed to:

- **Classify** the sentiment (positive or negative) of solar energy-related news articles.
- **Predict** the estimated price of solar commodities based on the article's content and publication date.

This project combines Natural Language Processing (NLP) and regression models to analyze textual news data and forecast pricing trends.

---

## 🧠 Features

- **Sentiment Analysis**: Classifies article sentiment using TextBlob and NLTK.
- **Price Prediction**: Uses article sentiment and date to predict solar commodity prices.
- **End-to-End ML Workflow**: Covers preprocessing, modeling, evaluation, and visualization.

---

## 🛠️ Tech Stack

- **Language**: Python 3.x
- **Libraries**:
  - pandas
  - numpy
  - scikit-learn
  - nltk
  - textblob
  - matplotlib
  - seaborn
- **Notebook Environment**: Jupyter Notebook

---

## 📁 Project Structure
<pre>
├── Solar_sentiment_price_prediction.ipynb # Main notebook with full pipeline
├── README.md # Project documentation
</pre>
---

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- pip

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/kalluri14/Solar_Sentiment_Price_Prediction.git
cd Solar_Sentiment_Price_Prediction
pip install pandas numpy scikit-learn nltk textblob matplotlib seaborn
import nltk
nltk.download('punkt')
nltk.download('vader_lexicon')
jupyter notebook Solar_sentiment_price_prediction.ipynb
```
## Follow the notebook cells to:

- Load and clean the data
- Perform sentiment analysis on news articles
- Train models to predict price based on sentiment and date
- Visualize performance and interpret results
