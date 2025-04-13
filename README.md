# GRU-Based Forecasting App for Market Clearing Price (MCP)

This project is a forecasting web application built using a GRU (Gated Recurrent Unit) deep learning model.  
It predicts the Market Clearing Price (MCP) for the Indian Energy Exchange (IEX) Day-Ahead Market.

The application is deployed using **Flask** and can be hosted using platforms like **Render** or **AWS EC2**.

---

## 🔍 Project Overview

- 🎯 **Goal**: Real-time demand-supply balancing for power trading
- 📈 **Target Variable**: Market Clearing Price (MCP)
- 🧠 **Best Model**: GRU (Gated Recurrent Unit)
- ⏱️ **Forecast Interval**: 15-minute intervals
- 📆 **Forecast Horizon**: January 2025 (1 month)

---

## 🗂️ Files Included

| File Name           | Description                                      |
|---------------------|--------------------------------------------------|
| `app.py`            | Flask web app to serve GRU predictions           |
| `best_model_gru.h5` | Trained GRU model file                           |
| `DAM__IND.csv`      | Input dataset used by the model                  |
| `requirements.txt`  | Python dependencies for the app                  |
| `render.yaml`       | Configuration file for Render deployment         |

---

## 🚀 Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/gru-forecasting-app.git
   cd gru-forecasting-app
