# Stock-Price-Prediction-LSTM

LSTMs for stock price prediction using PyTorch

## Introduction

This is a simple LSTM model for stock price prediction using PyTorch and Tensorflow. The model is trained on a historical data of Amazon and tested on the last 10% of the data. The model is trained on the closing price and the previous 7 days of closing prices as input features. The model is trained for 10 epochs and the loss is plotted. The model is then tested on the test data and the predicted prices are plotted against the actual prices.

## Installation

PyTorch for macbook needs to be installed using the following command:
`pip3 install torch torchvision torchaudio`

Verify PyTorch using the following code:

```python
import torch
x = torch.rand(5, 3)
print(x)
```

Check GPU availability:

```python
import torch
print(torch.backends.mps.is_available())
```

This uses the metal gpu support for macbook and will return True if the GPU is available.

### Usage

Run the jupyter notebook and the model will be trained and tested on the data. The loss will be plotted and the predicted prices will be plotted against the actual prices.
