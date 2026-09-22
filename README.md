# 🚗 U-Net Image Segmentation — Carvana Masking Challenge

A PyTorch implementation of the **U-Net** architecture for pixel-level image segmentation, trained on the [Carvana Image Masking Challenge](https://www.kaggle.com/c/carvana-image-masking-challenge) dataset to automatically separate cars from their backgrounds.

## ✨ Features

- Full U-Net architecture implemented from scratch in PyTorch
- Custom `Dataset` / `DataLoader` pipeline for the Carvana dataset
- Data augmentation for improved generalization
- Training and evaluation scripts with checkpointing
- Saved prediction masks for visual inspection

## 🧰 Tech Stack

- Python
- PyTorch
- NumPy
- Matplotlib

## 📁 Project Structure

```
├── model.py            # U-Net architecture definition
├── datasetLoad.py       # Dataset loading and preprocessing
├── train.py             # Training loop
├── train_test.py        # Training + evaluation utilities
├── utils.py              # Helper functions (metrics, checkpoints, etc.)
└── saved_images/         # Model output masks
```

## 🚀 Getting Started

```bash
pip install torch torchvision numpy matplotlib
```

```bash
python train.py
```

Predicted segmentation masks will be saved to `saved_images/` during training/evaluation.

## 📊 Dataset

This project uses the [Carvana Image Masking Challenge](https://www.kaggle.com/c/carvana-image-masking-challenge) dataset — high-resolution car photos paired with binary masks isolating the vehicle from the background.

## 📬 Contact

Questions or suggestions? Reach out at **yaltay556@gmail.com**.
