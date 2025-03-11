# 📝 VAE & GAN for Signature Generation  

This project implements a **Variational Autoencoder (VAE)** and a **Generative Adversarial Network (GAN)** to generate fake signatures. 
The models are trained separately to learn meaningful latent representations and generate new signatures that closely resemble real ones.  

---

## 🚀 **Features**  
✔ Loads and preprocesses **signature dataset**  
✔ Implements **Variational Autoencoder (VAE)** for signature generation  
✔ Implements a **Simple GAN** to generate fake signatures  
✔ Uses **data augmentation** (scaling, rotation, noise addition) to enhance dataset diversity  
✔ Trains models separately and evaluates using **reconstruction loss**  
✔ Compares generated images with real signatures to analyze performance  

---

## 🔧 **Requirements**  
- Python  
- Jupyter Notebook  
- Pytorch
- OpenCV  
- Matplotlib & Seaborn  
- Numpy & Pandas  

---

## 📊 **Results & Evaluation**  
The models were trained on a dataset of signatures, with performance measured using:  
✔ **Reconstruction Loss** (for VAE)  
✔ **Discriminator & Generator Loss** (for GAN)  
✔ **Comparison of Real vs. Generated Signatures**  

Hyperparameter tuning was performed to analyze improvements in signature generation quality.  
