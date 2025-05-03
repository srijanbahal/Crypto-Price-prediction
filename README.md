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
* *   **Libraries**: TensorFlow (LSTM), Pandas, NumPy, Scikit-learn, Plotly, Streamlit
* *   **Deployment**: Heroku
* *   **Version Control**: Git/GitHub

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
