# Stock Prediction System

This project is a stock price prediction system built using Long Short-Term Memory (LSTM) networks. The system predicts stock prices based on historical stock data and sentiment analysis from news and Twitter data. Initially developed as a University project, this system demonstrates fundamental applications of deep learning for stock prediction.

**Disclaimer:** This project is a prototype for educational purposes and should not be used for actual trading or financial advice.

---

## Features

- **Stock Price Prediction with LSTM:** Uses LSTM models trained with stock price data.
- **Sentiment Analysis:** Analyzes news and Twitter sentiment to factor emotional data into stock predictions.
- **User Interface:** Built using Streamlit for an interactive and intuitive GUI.
- **Models Used:** Four different LSTM models created (`FMODEL.h5`, `Mfinalmodel.h5`, `ModelNew.h5`, `NewMod.h5`), with `FMODEL.h5` providing the best accuracy.

## Built With

- **Python**
- **LSTM (Long Short-Term Memory Networks)** for time-series prediction
- **Streamlit** for GUI
- **TIINGO API** for stock data
- **Krish Naik’s Tutorials** for LSTM insights

---

## Project Structure

- **`app2.py`**: Main file to launch the GUI and execute stock predictions.
- **`FMODEL.h5`, `Mfinalmodel.h5`, `ModelNew.h5`, `NewMod.h5`**: Pre-trained LSTM models used for stock price prediction.
- **`NewsAnalyzer.py`, `SentimentAnalyzer.py`**: Scripts for processing and performing sentiment analysis on news and Twitter data.

---

## Setup & Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/alexmathew2009/SentimentStocks.git
   cd Stock-Prediction

2. **Install dependencies**:
   Install the required Python packages using:
   ```bash
   pip install -r requirements.txt
   
3. **Run the application**:
   To launch the Streamlit GUI, execute:
   ```bash
   streamlit run app2.py

4. **Network Access Required**:  
   The system requires an active internet connection to fetch stock data through the TIINGO API.

## Usage Notes

- **Models**: The project contains four pre-trained models (`FMODEL.h5`, `Mfinalmodel.h5`, `ModelNew.h5`, `NewMod.h5`). `FMODEL.h5` has shown the highest accuracy in predictions.
- **Sentiment Analysis**: Uses data from Twitter and news sources to factor public sentiment into stock prediction.

---

## Limitations

This system is a learning project and is not intended for real-world stock trading applications. Further accuracy improvements can be made by implementing additional algorithms and more sophisticated machine learning techniques.

---

## Acknowledgments

Special thanks to [Krish Naik](https://www.youtube.com/user/krishnaik06) for tutorials on LSTM, which provided valuable guidance on the model implementation.

