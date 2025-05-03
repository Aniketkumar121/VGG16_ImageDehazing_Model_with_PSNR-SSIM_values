# 🌫️ VGG16 Deep Learning Image Dehazing Model

A deep learning-based project for dehazing images using advanced feature extraction techniques and CNN architectures such as VGG16, ResNet, DenseNet, and AlexNet. This project aims to improve visibility and quality of images captured in hazy environments using enhanced preprocessing and model-driven techniques.

---

## 📌 Project Overview

**Title:** Monochromatic Image Dehazing Using Enhanced Feature Extraction Techniques in Deep Learning

**Objective:**  
Improve visibility and recover important visual information from hazy images using preprocessing techniques and deep learning models.

**Techniques Used:**
- Airlight Estimation
- Boundary Constraint
- Contextual Regularization

**CNN Models Tested:**
- VGG16

**Dataset:** RESIDE SOTS Dataset (Outdoor Training Set)

---

## 🧠 Key Features

✅ Dehazing using Airlight Estimation, Boundary Constraint and Contextual Regularization  
✅ Custom CNN models implemented for image dehazing  
✅ Dataset loader and data preprocessing pipeline  
✅ Metrics calculation for PSNR and SSIM  
✅ Comparison of various CNN architectures for performance evaluation

---

## 🚀 Model Performance

| Model    | Average SSIM | Average PSNR |
|----------|--------------|--------------|
| VGG16    | 0.813        | 28.35        |
| AlexNet  | 0.791        | 28.20        |
| DenseNet | 0.825        | 28.03        |
| ResNet   | 0.785        | 27.90        |

---

## 📈 Installation and Setup

### Clone the repository

```bash
git clone <your-repo-link>
cd image-dehazing
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the project

```bash
python main.py
```

You can modify `main.py` to select different models and preprocessing combinations.

---

## 📊 Evaluation Metrics

- **PSNR (Peak Signal-to-Noise Ratio)** - Measures the ratio between maximum possible power and corrupting noise.
- **SSIM (Structural Similarity Index)** - Measures similarity between two images.

Higher PSNR and SSIM indicate better dehazing results.

---

## 📌 Future Work

- Extend the dehazing solution to indoor images.
- Implement advanced deep learning models like GANs for realistic dehazing.
- Build a web interface for uploading and dehazing images.
- Combine different preprocessing techniques dynamically for best results.

---
