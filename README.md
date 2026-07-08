# Diabetic-retinopthy-detectioin-using-fundus-images-with-Deep-learning-Algorithms
# Diabetic Retinopathy Detection using Deep Learning Algorithms

## Overview

This project presents an automated diabetic retinopathy detection system using retinal fundus images. Multiple deep learning architectures were developed and evaluated, including Hybrid CNN + Vision Transformer, ResNet152V2, and Ordinal ResNet50. Image preprocessing techniques were applied to improve retinal feature extraction and enhance classification performance.

---

## Features

- Automated diabetic retinopathy grading
- Green channel extraction
- CLAHE image enhancement
- Median filtering
- CNN + Vision Transformer (ViT)
- ResNet152V2
- Ordinal Regression based ResNet50
- Hybrid CNN + XGBoost experiments
- Quadratic Weighted Kappa (QWK): **0.88**

---

## Repository Structure

```
Diabetic-Retinopathy-Detection
│
├── Dataset/
│   └── README.md
│
├── Models/
│   ├── HybridCNN+XGB Results/
│   ├── Ordinal_ResNet50Model/
│   ├── Hybrid_CNN+Vit colab.ipynb
│   └── ResNet152V2.ipynb
│
├── Preprocessing/
│   └── 7_preprocessing_code.ipynb
│
├── Published paper/
│   └── Published Paper.pdf
│
├── README.md
└── 284_CRC.pdf
```

---

## Dataset

This project uses the **APTOS 2019 Blindness Detection** dataset.

Dataset Link:

https://www.kaggle.com/competitions/aptos2019-blindness-detection

---

## Image Preprocessing

The preprocessing pipeline includes:

- Green Channel Extraction
- CLAHE
- Median Filtering
- Image Resizing
- Image Normalization

---

## Deep Learning Models

### Hybrid CNN + Vision Transformer
A hybrid architecture combining convolutional neural networks with Vision Transformers for robust feature extraction and classification.

### ResNet152V2
A deep residual network used as a baseline for diabetic retinopathy grading.

### Ordinal ResNet50
An ordinal regression-based approach for predicting diabetic retinopathy severity.

### Hybrid CNN + XGBoost
Experimental model combining CNN-based feature extraction with XGBoost classification.

---

## Performance

| Metric | Score |
|---------|------:|
| Quadratic Weighted Kappa (QWK) | **0.88** |

---

## Research Paper

The published research paper is available inside the **Published paper** folder.

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- OpenCV
- Pandas
- Matplotlib
- Scikit-learn
- Vision Transformer (ViT)
- CNN
- ResNet models
- Deep Learning Models

---

## Future Improvements

- Streamlit Web Application
- Real-time prediction
- Grad-CAM visualization
- Docker deployment
- REST API using FastAPI

---

## Author

**Adithya DS**

B.Tech Artificial Intelligence Engineering

Amrita Vishwa Vidyapeetham

---

## License

This project is intended for educational and research purposes.
