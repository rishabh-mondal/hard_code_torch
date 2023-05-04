# hard_code_torch
Make different versions of a simple (1, 2, 1 - Input, Hidden, Output Layers RELU Activation for the Hidden Layer) Neural Network for linear regression using PyTorch.

x = t.arange(0, 10, 0.1, dtype=t.float32).reshape(100, 1) y = 4 + 3 * x + t.randn((len(x), 1))
