# 🧠 Neural Networks from Scratch

This repository contains a complete implementation of a **feedforward neural network** using only **NumPy**, without relying on any deep learning libraries like TensorFlow or PyTorch. The goal is to build neural networks from the ground up to understand the core mechanics of forward and backward propagation, gradient descent, and parameter updates.

## 🚀 Architecture

The model supports:
- ✅ Two-layer neural network: `LINEAR -> RELU -> LINEAR -> SIGMOID`
- ✅ Deep neural networks with any number of layers
- ✅ Modular code for forward & backward propagation
- ✅ Cross-entropy cost function

  
## 🔧 Features Implemented

- `initialize_parameters` / `initialize_parameters_deep`
- `linear_forward` & `linear_activation_forward`
- `compute_cost` (cross-entropy)
- `linear_backward` & `linear_activation_backward`
- `L_model_forward` / `L_model_backward`
- `update_parameters`


## 📊 Training Example

You can train a simple two-layer network as follows:

```python
parameters, costs = two_layer_model(X_train, Y_train, layers_dims=(n_x, n_h, n_y), num_iterations=3000, print_cost=True)
