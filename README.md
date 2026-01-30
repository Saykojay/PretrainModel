# PretrainModel
# PV Power Output Prediction using Deep Learning Models
Comparison of different deep learning models for **Photovoltaic (PV) power output prediction** using DKASC dataset. This project is part of my thesis research on **E-Methanol production simulation** with solar power uncertainty prediction.
---
## Project Overview
This repository contains implementations of various deep learning architectures for time-series forecasting of solar PV power output. The goal is to compare model performance and identify the best approach for handling solar power uncertainty in downstream chemical process optimization.
### Models Implemented:
| Model | Description | Notebook |
|-------|-------------|----------|
| **RNN** | Vanilla Recurrent Neural Network | [RNN_Pretrain_Pipeline.ipynb](RNN_Pretrain_Pipeline.ipynb) |
| **LSTM** | Long Short-Term Memory | [LSTM_Pretrain_Pipeline.ipynb](LSTM_Pretrain_Pipeline.ipynb) |
| **GRU** | Gated Recurrent Unit | [GRU_Pretrain_Pipeline.ipynb](GRU_Pretrain_Pipeline.ipynb) |
| **PatchTST** | Patch Time Series Transformer | [PatchTST_Pretrain_Pipeline.ipynb](PatchTST_Pretrain_Pipeline.ipynb) |
| **TimePerceiver** | Perceiver-based Time Series Model | [TimePerceiver_Pretrain_Pipeline.ipynb](TimePerceiver_Pretrain_Pipeline.ipynb) |
| **TimeTracker** | Custom Time Series Tracker | [TimeTracker_Pretrain_Pipeline.ipynb](TimeTracker_Pretrain_Pipeline.ipynb) |
---
## 📊 Dataset
**DKASC (Desert Knowledge Australia Solar Centre) Dataset**
- Real-world solar PV generation data from Alice Springs, Australia
- Features: Irradiance, Temperature, Humidity, Wind Speed, PV Power Output
- Used for training and evaluating time-series prediction models
---
## 🛠️ Tech Stack
- **Python 3.10 -  3.12**
- **TensorFlow / Keras** - Deep learning framework
- **Pandas & NumPy** - Data manipulation
- **Matplotlib & Seaborn** - Visualization
- **Scikit-learn** - Preprocessing & metrics
- **Optuna** - Hyperparameter optimization
- **MLflow** - Experiment tracking
---
## 🚀 Getting Started
### Prerequisites
```bash
pip install tensorflow pandas numpy matplotlib scikit-learn optuna mlflow
