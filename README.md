# Time-Series-Forcasting-in-Bitcoin
# Time Series Forecasting in TensorFlow (BitPredict 💰📈)

This project explores **time series forecasting** using TensorFlow, focusing on predicting Bitcoin prices. The goal is to understand working with time series data, preprocess it, and build machine learning models for forecasting.

🚨 **Note:** This is not financial advice. Predicting stock/crypto prices using time series forecasting is highly challenging and often unreliable.

## 📂 Dataset

We use historical Bitcoin price data from **01 October 2013 to 18 May 2021**, sourced from **Coindesk**. You can download the dataset from [Coindesk Bitcoin Prices](https://www.coindesk.com/price/bitcoin).

Alternatively, find the dataset on GitHub: [BTC_USD_2013-10-01_2021-05-18-CoinDesk.csv](https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/extras/BTC_USD_2013-10-01_2021-05-18-CoinDesk.csv).

## 🚀 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo

2. **Install dependencies You can use ```pip``` to install required packages**
 ```
pip install -r requirements.txt
 ```
If you're using a Jupyter Notebook, you can install packages directly:
```
!pip install numpy pandas matplotlib tensorflow scikit-learn
```
3. Run the notebook Open Jupyter Notebook and execute ```10_time_series_forecasting_in_tensorflow.ipynb step by step.```

## 🔑 Key Features
Load and visualize time series data using Pandas & Matplotlib.
Preprocess the dataset for forecasting models.
Build and evaluate deep learning models using TensorFlow/Keras.
Experiment with different forecasting techniques.

## 📦 Libraries Used
This project primarily uses:

TensorFlow – Deep learning framework
Pandas – Data manipulation
NumPy – Numerical computations
Matplotlib – Data visualization
Scikit-Learn – Data preprocessing

## 🎯 Results & Learnings
The project demonstrates how time series forecasting can be approached using machine learning. However, predicting financial prices remains highly uncertain due to market fluctuations.

## 📌 Future Enhancements
Try different neural network architectures (e.g., LSTMs, Transformers).
Explore external features like market sentiment or trading volume.
Improve hyperparameter tuning for better accuracy.
