# Predicting-minimum-daily-temperatures-in-Melbourne

# 🌡️ Melbourne Minimum Daily Temperature Prediction

This project focuses on predicting the **minimum daily temperatures in Melbourne, Australia**, using historical time series data and machine learning techniques. The goal is to build and evaluate models that can forecast future minimum temperatures based on past observations.

## 📈 Project Overview

- **Problem**: Time series forecasting of minimum daily temperatures.
- **Location**: Melbourne, Australia.
- **Data**: Daily minimum temperatures from 1981 to 1990.
- **Techniques**: Time series analysis, feature engineering, machine learning (e.g., Linear Regression, Random Forest), and deep learning (e.g., LSTM).

## 📊 Dataset

- **Source**:https://www.kaggle.com/datasets/paulbrabban/daily-minimum-temperatures-in-melbourne
- **File**: `daily-min-temperatures.csv`
- **Columns**:
  - `Date`: Date in `yyyy-mm-dd` format
  - `Temp`: Minimum temperature in degrees Celsius

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/melbourne-temperature-prediction.git
   cd melbourne-temperature-prediction
   ```

2. Create and activate a virtual environment (optional):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Usage

1. **Preprocess the data**:
   ```bash
   python preprocess.py
   ```

2. **Train a model**:
   ```bash
   python train.py
   ```

3. **Evaluate and plot results**:
   ```bash
   python evaluate.py
   ```

4. **Predict future temperatures**:
   ```bash
   python predict.py
   ```

## 📌 Features

- Visualizes temperature trends and seasonality
- Implements time-based train-test split
- Supports classical ML models and LSTM-based neural networks
- Saves trained models for reuse


## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo, open issues, and submit pull requests.

## 📜 License

This project is licensed under the [MIT License](LICENSE).

## ✨ Acknowledgements

- UCI Machine Learning Repository
- Matplotlib, Scikit-learn, TensorFlow, Pandas

---

```
