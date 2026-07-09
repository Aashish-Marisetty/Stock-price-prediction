<div align="center">

# 📈 Stock Price Prediction using LSTM

### Deep Learning-based Time Series Forecasting with TensorFlow & Streamlit

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00?style=for-the-badge&logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?style=for-the-badge&logo=streamlit)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

An end-to-end **Deep Learning application** that predicts future stock prices using **Long Short-Term Memory (LSTM)** networks trained on historical financial data from Yahoo Finance. The project includes an interactive **Streamlit dashboard** for real-time visualization and prediction.

</div>

---

# 🚀 Overview

Financial markets generate highly volatile time-series data that are difficult to model using traditional statistical techniques.

This project leverages **Long Short-Term Memory (LSTM)** neural networks to learn long-term temporal dependencies in stock prices and forecast future closing prices.

The application allows users to:

- 📊 Fetch historical stock data
- 🤖 Generate predictions using a trained LSTM model
- 📈 Visualize actual vs predicted prices
- 💻 Interact through a clean Streamlit web application

---

# ✨ Features

- 📥 Automatic stock data retrieval from Yahoo Finance
- 🧹 Data preprocessing and normalization
- 🧠 Deep Learning model using LSTM
- 📈 Interactive prediction visualization
- ⚡ Streamlit-based web interface
- 📊 Actual vs Predicted comparison graphs
- 🔄 Scalable architecture for additional stocks
- 🧩 Modular and easy-to-maintain codebase

---

# 🏗️ Tech Stack

| Category | Technologies |
|-----------|-------------|
| Programming | Python |
| Deep Learning | TensorFlow, Keras |
| Data Processing | Pandas, NumPy |
| Data Source | Yahoo Finance API (yfinance) |
| Visualization | Matplotlib |
| Web Framework | Streamlit |
| Model | LSTM Neural Network |

---

# 📂 Project Structure

```
Stock-Price-Prediction/
│
├── app.py                      # Streamlit application
├── keras_model.h5              # Trained LSTM model
├── Stock_Price_Prediction.ipynb
├── requirements.txt
├── README.md
└── LICENSE
```

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Stock-Price-Prediction.git

cd Stock-Price-Prediction
```

Create a virtual environment

```bash
python -m venv venv
```

Activate

Windows

```bash
venv\Scripts\activate
```

Linux / Mac

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Application

Launch Streamlit

```bash
streamlit run app.py
```

The application opens automatically in your browser.

---

# 📊 Workflow

```
Yahoo Finance
      │
      ▼
Historical Stock Data
      │
      ▼
Data Cleaning
      │
      ▼
Normalization
      │
      ▼
Sequence Generation
      │
      ▼
LSTM Model
      │
      ▼
Prediction
      │
      ▼
Visualization
      │
      ▼
Streamlit Dashboard
```

---

# 🧠 Model Pipeline

1. Download historical stock prices
2. Clean missing values
3. Normalize using MinMaxScaler
4. Generate sliding window sequences
5. Train LSTM model
6. Predict future prices
7. Reverse scaling
8. Display predictions and graphs

---

# 📸 Application Preview

> Replace these placeholders with screenshots after deployment.

```
📈 Home Dashboard

📉 Historical Price Graph

🤖 Predicted vs Actual Graph

📊 Stock Information
```

---

# 📚 Libraries Used

```text
numpy
pandas
matplotlib
tensorflow
keras
streamlit
yfinance
pandas_datareader
scikit-learn
```

---

# 📈 Results

The trained LSTM model demonstrates strong capability in learning long-term trends from historical stock data.

### Achievements

- Accurate trend prediction
- Stable convergence during training
- Smooth forecasting
- Effective time-series learning

Although sudden market crashes and news-driven volatility remain difficult to predict, the model successfully captures medium and long-term market behavior.

---

# 🔮 Future Improvements

- Multi-step forecasting
- Transformer-based forecasting models
- Attention Mechanisms
- Technical Indicators (RSI, EMA, MACD)
- Sentiment Analysis from Financial News
- Real-time deployment on Streamlit Cloud
- Docker containerization
- CI/CD with GitHub Actions

---

# 📖 Learning Outcomes

This project demonstrates practical experience with:

- Deep Learning
- Time Series Forecasting
- LSTM Networks
- Data Engineering
- Model Deployment
- Streamlit Development
- Financial Data Analysis
- Machine Learning Pipeline Design

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository

2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add feature"
```

4. Push

```bash
git push origin feature-name
```

5. Open a Pull Request

---


# 👨‍💻 Author

**Aashish Marisetty**

B.Tech Computer Science Engineering

AI & Machine Learning Enthusiast

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourprofile

---

<div align="center">

⭐ If you found this project useful, consider giving it a star!

</div>
