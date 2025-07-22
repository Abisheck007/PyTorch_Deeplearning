# 🧠 Deep Learning with PyTorch

A clean and modular deep learning project built using [PyTorch](https://pytorch.org/). This repo is designed to be beginner-friendly and scalable for more complex tasks in the future.

---

## 🚀 Features

- Modular PyTorch pipeline
- Dataset loaders and transformations
- Custom model architectures
- Training and validation loops
- Checkpoint saving & loading
- Logging with tqdm
- GPU support

---

## 🗂️ Project Structure

deep-learning-pytorch/
│
├── data/ # Datasets or data loading scripts
├── models/ # Custom model architectures
├── utils/ # Helper functions (metrics, plotting, etc.)
├── checkpoints/ # Saved model weights
├── train.py # Training loop
├── evaluate.py # Evaluation script
├── config.py # Configuration (hyperparameters, paths)
└── requirements.txt # All dependencies


---

## 📊 Models Included

| Model          | Description                   |
|----------------|-------------------------------|
| CNN            | Simple convolutional network  |
| MLP            | Multi-layer perceptron        |
| ResNet (custom)| Residual block architecture   |

---

## 🏁 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/deep-learning-pytorch.git
cd deep-learning-pytorch

Hyper parameteres tuning
python train.py --lr 0.001 --epochs 20 --model mlp
