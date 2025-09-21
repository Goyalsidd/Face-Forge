# FaceForge

**FaceForge** is a Deep Convolutional Generative Adversarial Network (DCGAN) designed to generate realistic human-like faces. The model was trained on a dataset of over 25,000 images, leveraging the power of deep learning to create high-quality synthetic images. This project demonstrates the capability of AI in generating human facial features and can be extended for various applications such as synthetic data generation, creative content, and more. 

---

## Overview
FaceForge is built using TensorFlow and trained for over 8 hours on an NVIDIA Tesla P100 GPU. The model focuses on creating human-like faces with high accuracy and precision, employing a stable architecture with optimized discriminator and generator losses.

---

## Features
- Trained on a dataset of **25,000 human face images**.  
- High-quality **synthetic human face generation**.  
- Stable model performance with **Discriminator losses < 0.018** and **Generator losses < 6.282**.  
- **Real-time image generation and classification**.  

---

## Dataset
The dataset consists of **25,000 labeled human face images** used to train the DCGAN model.  
Data augmentation techniques were applied to improve model robustness and performance.

---

## Model Details
FaceForge uses a **DCGAN architecture**, where:

- **Generator**: Creates synthetic human-like face images.  
- **Discriminator**: Distinguishes between real and generated faces, helping the generator improve over time.  

**Key Parameters:**  
- **Losses**: Discriminator loss < 0.018, Generator loss < 6.282.  
- **Training Time**: 8+ hours on NVIDIA Tesla P100 GPU.  

---

## Training Process
- Trained using **25,000 images** over 8+ hours.  
- Data augmentation applied to improve generalization.  
- Optimization of Discriminator and Generator losses for stable performance.  

---

## Results
- Achieved **92% accuracy** in generating realistic human-like faces.  
- Generated images exhibit **fine details and clear facial features**.  
