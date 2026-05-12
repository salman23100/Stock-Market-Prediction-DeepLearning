# Stock Market Direction Prediction Using Deep Learning

## Project Overview
This project predicts whether the Apple (AAPL) stock price will go **UP or DOWN** the next day using deep learning models combined with news sentiment analysis. Three recurrent neural network models were built and compared: Simple RNN, LSTM, and GRU.

---

## Group Members
|------|--------|
| [Salman Shafique] 
| [Shahzad Ahmad] 


---

## Models Used
| Model | Accuracy | F1 Score |
|-------|----------|----------|
| Simple RNN | 60.20% | 0.75 |
| LSTM | 60.20% | 0.75 |
| GRU | 60.20% | 0.75 |

---

## Dataset
- **Stock Data:** Apple Inc. (AAPL) from January 2023 to January 2025
- **Source:** Yahoo Finance via `yfinance` library
- **News Data:** 20 headlines from Yahoo Finance RSS Feed
- **Sentiment Tool:** VADER (Valence Aware Dictionary and Sentiment Reasoner)
- **Total Trading Days:** ~502
- **Training Samples:** 392 sequences
- **Testing Samples:** 98 sequences

---

## How It Works
1. Download AAPL stock price data using `yfinance`
2. Scrape news headlines using Yahoo Finance RSS feed
3. Run VADER sentiment analysis on each headline
4. Attach average sentiment score to stock data
5. Create sequences of 10 days as model input
6. Train RNN, LSTM, and GRU models
7. Evaluate and compare results
8. Make final market direction prediction

---

## Tech Stack
- Python
- TensorFlow / Keras
- scikit-learn
- yfinance
- feedparser
- vaderSentiment
- pandas, numpy, matplotlib

---

## How to Run
1. Open `Project1.ipynb` in Google Colab or Jupyter Notebook
2. Install dependencies:
3. and run each cell
