# 🖼️ CIFAR-100 Image Classification From Scratch

A deep learning-based image classification system trained completely from scratch on the **CIFAR-100 dataset** using PyTorch.

The project focuses on building an optimized CNN architecture with:
- high classification accuracy,
- low latency,
- pruning,
- quantization,
- and mobile deployment support.

The trained model was also deployed on an **Android application using Android Studio** for real-time inference.

---

# 🚀 Key Features

- 🧠 Custom CNN architecture built from scratch
- 🎯 CIFAR-100 image classification
- ⚡ Optimized for fast inference
- ✂️ Model pruning support
- 📦 Quantization for lightweight deployment
- 📱 Android deployment support
- 📊 Detailed evaluation metrics
- 🔥 Top-1 and Top-5 accuracy tracking

---

# 🛠️ Tech Stack

| Component | Technology |
|-----------|-------------|
| Deep Learning | PyTorch |
| Dataset | CIFAR-100 |
| Visualization | Matplotlib |
| Optimization | Pruning + Quantization |
| Deployment | Android Studio |
| Hardware Support | GPU / CUDA |

---

# 🧠 Model Architecture

The model consists of:
- Convolutional layers
- Batch Normalization
- ReLU activations
- MaxPooling
- Dropout regularization
- Fully Connected layers

Additional optimizations:
- Label smoothing
- Learning rate scheduling
- Weight pruning
- Quantization-aware optimization

---

# 📊 Final Performance Metrics

| Metric | Value |
|--------|-------|
| Best Train Loss | 1.0503 |
| Best Test Loss | 1.7044 |
| Best Train Accuracy | 94.55% |
| Best Test Accuracy | 72.06% |
| Top-5 Test Accuracy | 91.66% |
| Accuracy GAP | 22.49 |
| Loss GAP | 0.6541 |
| Lowest Class Accuracy | 44.00% |
| Highest Class Accuracy | 95.00% |
| Trainable Parameters | 4,846,244 |
| FLOPs | 210,037,760 |
| Model Size | 18.52 MB |
| Latency (Batch = 1) | 1.597 ms |
| Latency (Batch = 32) | 4.145 ms |

---

# 📂 Project Structure

```bash
CIFAR100-Image-Classification/
│
├── dataset/
├── models/
├── checkpoints/
├── android_app/
├── results/
├── notebooks/
│   └── training.ipynb
├── model.pth
├── requirements.txt
└── README.md
```

---

# ⚙️ Training Features

- Data Augmentation
- Random Cropping
- Horizontal Flipping
- Learning Rate Warmup
- SGD + Momentum
- Cosine Annealing Scheduler
- Label Smoothing
- Pruning
- Quantization

---

# 📱 Android Deployment

The trained model was integrated into an Android application using **Android Studio** for mobile inference.

### Mobile Features
- Real-time image prediction
- Lightweight optimized model
- Fast inference
- Offline support

---

# 📈 Training Visualizations

Include screenshots of:
- Accuracy vs Epoch
- Loss vs Epoch
- Confusion Matrix
- Sample Predictions

Add them inside:
```bash
results/
```

---

# ▶️ Installation

```bash
pip install torch torchvision matplotlib fvcore torchinfo
```

---

# ▶️ Run Training

```bash
python train.py
```

---

# 🧪 Dataset

Dataset used:
- CIFAR-100
- 100 image classes
- 32×32 RGB images

Official Dataset:
https://www.cs.toronto.edu/~kriz/cifar.html

---

# 🔥 Future Improvements

- Vision Transformer implementation
- Knowledge Distillation
- TensorRT optimization
- ONNX export
- Edge AI deployment
- Real-time camera classification

---

# 📌 Conclusion

This project demonstrates an end-to-end deep learning pipeline for efficient image classification, model optimization, and mobile deployment.

The system achieves:
- strong classification accuracy,
- low latency,
- optimized model size,
- and practical deployment readiness.

---

# 👨‍💻 Author

Developed using Deep Learning, Computer Vision, and Mobile AI Deployment.
