Paste your rich text content her

# Cryptocurrency Price Prediction

## Overview

This project develops a modular machine learning pipeline to predict cryptocurrency prices (e.g., BTC-USD, ETH-USD) using Long Short-Term Memory (LSTM) neural networks. The pipeline achieves a Mean Absolute Percentage Error (MAPE) of 12% across 1, 7, and 30-day forecasts. Key features include Relative Strength Index (RSI), Moving Average Convergence Divergence (MACD), and Bollinger Bands, which improve prediction accuracy over baseline models. An exploratory data analysis (EDA) with candlestick charts uncovers market trends, and an interactive Streamlit web application, deployed on Heroku, enables user-driven predictions with dynamic Plotly visualizations.

## Features

* *   **Modular Pipeline**: A scalable, reusable pipeline for data preprocessing, feature engineering, model training, and evaluation.
* *   **LSTM Model**: Predicts cryptocurrency prices with a 12% MAPE for short- and long-term forecasts.
* *   **Feature Engineering**: Incorporates RSI, MACD, and Bollinger Bands to enhance model performance.
* *   **EDA**: Visualizes market trends using candlestick charts with Plotly.
* *   **Interactive App**: A Streamlit-based web app for user-defined predictions, deployed on Heroku.

## Technologies Used

* *   **Programming Language**: Python
* *   **Libraries**: TensorFlow (LSTM), Pandas, NumPy, Scikit-learn, Plotly, Streamlit, TA-Lib (technical indicators)
* *   **Deployment**: Heroku
* *   **Version Control**: Git/GitHub

## Installation

To run the project locally, follow these steps:

1. 1.  **Clone the Repository**:
1.     
1.     ```bash
1.     git clone https://github.com/your-username/crypto-price-prediction.git
1.     cd crypto-price-prediction
1.     ```
1.     
1. 2.  **Set Up a Virtual Environment** (optional but recommended):
1.     
1.     ```bash
1.     python -m venv venv
1.     source venv/bin/activate  # On Windows: venv\Scripts\activate
1.     ```
1.     
1. 3.  **Install Dependencies**:
1.     
1.     ```bash
1.     pip install -r requirements.txt
1.     ```
1.     
1. 4.  **Install TA-Lib** (for technical indicators):
1.     
1.     * *   Follow the [TA-Lib installation guide](https://github.com/mrjbq7/ta-lib) for your operating system.
1.     * *   Alternatively, use a precompiled wheel if available:
1.     *     
1.     *     ```bash
1.     *     pip install TA-Lib
1.     *     ```
1.     *     
1. 5.  **Download Data**:
1.     
1.     * *   The project uses historical cryptocurrency data (e.g., BTC-USD, ETH-USD). You can fetch data from sources like Yahoo Finance or CoinGecko.
1.     * *   Place the data in the `data/` directory as CSV files (e.g., `BTC-USD.csv`).

## Usage

1. 1.  **Run the Pipeline**:
1.     
1.     * *   Execute the main script to train the LSTM model and generate predictions:
1.     *     
1.     *     ```bash
1.     *     python src/main.py
1.     *     ```
1.     *     
1.     * *   The script processes data, engineers features, trains the model, and saves predictions to `outputs/predictions.csv`.
1. 2.  **Perform EDA**:
1.     
1.     * *   Run the EDA script to generate candlestick charts and analyze trends:
1.     *     
1.     *     ```bash
1.     *     python src/eda.py
1.     *     ```
1.     *     
1.     * *   Visualizations are saved in the `outputs/visuals/` directory.
1. 3.  **Launch the Streamlit App**:
1.     
1.     * *   Start the Streamlit app locally:
1.     *     
1.     *     ```bash
1.     *     streamlit run src/app.py
1.     *     ```
1.     *     
1.     * *   Open your browser to `http://localhost:8501` to interact with the app.
1. 4.  **Access the Deployed App**:
1.     
1.     * *   Visit the Heroku-hosted app at: [https://your-app-name.herokuapp.com](https://grok.com/chat/a7a2faa6-91e0-4931-b46b-434bc708facd#) (replace with actual URL).
1.     * *   Use the interface to select a cryptocurrency, forecast horizon, and view predictions with Plotly charts.

## Project Structure

```
crypto-price-prediction/
├── data/                   # Historical cryptocurrency data (e.g., BTC-USD.csv)
├── outputs/                # Model predictions and EDA visualizations
│   ├── predictions.csv     # Predicted prices
│   └── visuals/            # Candlestick charts and plots
├── src/                    # Source code
│   ├── main.py             # Main pipeline script
│   ├── eda.py              # EDA and visualization script
│   ├── app.py              # Streamlit app script
│   └── utils.py            # Helper functions for preprocessing and features
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

## Results

* *   **Model Performance**: The LSTM model achieves a 12% MAPE across 1, 7, and 30-day forecasts, outperforming baseline models (e.g., ARIMA, simple RNN).
* *   **Feature Impact**: RSI, MACD, and Bollinger Bands reduced prediction error by capturing market trends and volatility.
* *   **EDA Insights**: Candlestick charts revealed recurring patterns, such as bullish reversals, aiding feature selection.
* *   **User Experience**: The Streamlit app provides an intuitive interface for non-technical users to explore predictions.

## Future Improvements

* *   Incorporate additional features, such as sentiment analysis from social media (e.g., X posts) or on-chain metrics.
* *   Experiment with Transformer-based models for improved long-term forecasting.
* *   Optimize the pipeline for real-time data streaming.
* *   Enhance the Streamlit app with more interactive features, like custom feature selection.

## License

This project is licensed under the MIT License. See the [LICENSE](https://grok.com/chat/LICENSE) file for details.

## Contact

For questions or feedback, reach out via:

* *   Email: [srijanbahal10@gmail.com](mailto:your-email@example.com)
* *   GitHub: [srijanbahal](https://github.com/your-username). You can paste directly from Word or other rich text sources.
