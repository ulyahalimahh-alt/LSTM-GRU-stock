# LSTM-GRU-stock

# Stock Price Prediction Using LSTM and GRU

## Overview

This repository contains implementations of Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU) models for stock price prediction using historical financial time-series data.

The objective of this project is to compare the performance of LSTM and GRU architectures in forecasting stock market behavior and evaluating their ability to capture temporal dependencies in sequential data.

## Repository Structure

```text
.
├── LSTM_Global.ipynb
└── GRU_Global.ipynb
```

- `LSTM_Global.ipynb` – Complete workflow for stock price prediction using an LSTM network.
- `GRU_Global.ipynb` – Complete workflow for stock price prediction using a GRU network.

## Methodology

The notebooks follow a typical deep learning workflow for time-series forecasting:

1. Data Loading and Preprocessing
2. Feature Engineering
3. Data Normalization
4. Sequence Generation
5. Model Construction
6. Model Training
7. Performance Evaluation
8. Prediction and Visualization

## Model Architectures

### Long Short-Term Memory (LSTM)

LSTM is a recurrent neural network architecture designed to learn long-term dependencies in sequential data through memory cells and gating mechanisms.

Main components:

- Input Gate
- Forget Gate
- Output Gate
- Cell State

### Gated Recurrent Unit (GRU)

GRU is a simplified variant of LSTM that reduces computational complexity while maintaining strong predictive performance.

Main components:

- Update Gate
- Reset Gate

## Evaluation

The models are evaluated using standard regression metrics, including:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)
- R² Score

Performance comparisons between LSTM and GRU are provided within the notebooks.

## Requirements

The project is implemented in Python and requires the following libraries:

```bash
pip install numpy pandas matplotlib scikit-learn torch jupyter
```

## Running the Project

Start Jupyter Notebook:

```bash
jupyter notebook
```

Then open one of the notebooks:

```text
LSTM_Global.ipynb
```

or

```text
GRU_Global.ipynb
```

and run all cells sequentially.

## Research Objective

This project aims to:

- Develop stock price forecasting models using LSTM and GRU.
- Compare the predictive capabilities of both architectures.
- Analyze the effectiveness of recurrent neural networks for financial time-series forecasting.
- Evaluate model performance on unseen data.

## Authors

This project was developed by:

- Christina Dewi
- Ulya Halimah
- Susi Komalasari
- Ilmania Syakira

## License

This repository is intended for academic and research purposes.
