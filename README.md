# MIT 6.S191 — Introduction to Deep Learning (PyTorch)

My work through [MIT's Introduction to Deep Learning](http://introtodeeplearning.com) course, implemented in PyTorch.

## Lab 1: Intro to PyTorch & Music Generation with RNNs

### Part 1 — PyTorch Fundamentals
Core PyTorch concepts hands-on:
- Tensors: creation, shapes, slicing, and operations
- Building neural networks with `nn.Module` and the Sequential API
- Automatic differentiation with `torch.autograd`
- Gradient descent from scratch to minimize a loss function

### Part 2 — Music Generation with LSTMs
End-to-end sequence modeling project:
- Text vectorization: mapping characters to indices
- Batching sequential data for RNN training
- LSTM model built from scratch using `nn.Module` (Embedding → LSTM → Linear)
- Custom training loop with cross-entropy loss and Adam optimizer
- Character-level music generation by sampling from a softmax distribution
- Trained on ABC notation songs; model learns song structure from raw text

## Structure

```
lab1/
├── PT_Part1_Intro.ipynb
└── PT_Part2_Music_Generation.ipynb
```

## Course

MIT 6.S191 · 2026 · [introtodeeplearning.com](http://introtodeeplearning.com)