
# Simple PyTorch Neural Network Model

This repository contains a basic PyTorch neural network implemented using `torch.nn.Sequential`.  
It demonstrates a minimal feedforward neural network with one hidden layer

##  Model Architecture

The model consists of:

  Input Layer: 2 features  
  Hidden Layer: 4 neurons with ReLU activation  
  Output Layer: 1 neuron (suitable for regression or binary classification)

  
---
Output Layer
## 🧾 Model Implementation

```python
import torch
import torch.nn as nn

model = nn.Sequential(
    nn.Linear(2, 4),
    nn.ReLU(),
    nn.Linear(4, 1)
)

Requirements:
Python 3.7 or higher
PyTorch

Install PyTorch
pip install torch

How To Run:

import torch

# Sample input
x = torch.tensor([[1.0, 2.0]])

# Forward pass
output = model(x)
print(output)


Applications:
Learning PyTorch fundamentals
Understanding neural network layers
Simple regression tasks
Base model for machine learning projects
Educational and academic use

