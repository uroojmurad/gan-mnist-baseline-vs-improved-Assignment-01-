# MNIST GAN (PyTorch)

Description: 
This project implements a Generative Adversarial Network (GAN) on the MNIST dataset using PyTorch. 
It includes a baseline model and an improved version, with analysis of training behavior and generated outputs.

Features:
- Baseline GAN implementation (fully connected)
- Improved GAN with stability enhancements
- Training loss analysis
- Generated image visualization

Dataset:
- MNIST handwritten digits
- 28x28 grayscale images
- Normalized to [-1, 1]

How to Run: 
pip install torch torchvision matplotlib
python gan_baseline.py
python gan_improved.py

Results:
- Baseline model produces noisy outputs
- Improved model generates clearer digit-like images

Project Structure:
├── gan_baseline.py
├── gan_improved.py
├── samples/
├── plots/
└── README.md


