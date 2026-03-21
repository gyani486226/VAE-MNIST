# 🚀 VAE-MNIST

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-VAE-green)
![Dataset](https://img.shields.io/badge/Dataset-MNIST-orange)

---

## 📌 Overview  
- This project implements a **Variational Autoencoder (VAE)** on the MNIST dataset to learn latent representations and generate handwritten digit images.
- Variational autoencoders extend the capability of traditional Autoencoders by incoporating probabilistic elements into the encoding process.
- 
---

## 🧠 Model Architecture  
- Encoder :-Compresses input data into a lower-dimensional latent space by learning mean (μ) and variance (σ²).
- Latent Space (Mean + Variance) :- Instead of a single point, VAE represents each input as a probability distribution (Gaussian) defined by mean (μ) and variance (σ²).
- Decoder  :- Decoder is also a neural network which is used to reconstruct original data but because of probability distribution decoder allows VAEs to generate new data.
---

## 🚀 Features  
✔ **Image Reconstruction** of MNIST digits.
✔ **Digit Generation** by sampling the latent space.
✔ **Latent Space Visualization**for understanding learned representations. 

---

## 📂 Dataset  
- MNIST (0–9 handwritten digits)

---

## ⚙️ Installation  
- MNIST data
- README.md
- Deep learning library >> Pytorch
- Dependies 

## 📸 Results  

### Input vs Reconstruction  vs Generative Image
![Reconstruction](output.png)
