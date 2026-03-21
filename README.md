# AI Image Authenticity Detector

A machine learning-based forensic system that detects whether an image is **real (camera-captured)**, **AI-generated**, or **AI-edited** by analyzing hidden statistical patterns, frequency artifacts, and noise inconsistencies.

---

## 🚀 Project Overview

With the rise of AI tools like diffusion models, distinguishing between real and synthetic images has become increasingly difficult.

This project aims to build a **digital forensic system** that can:

* Detect AI-generated images
* Identify signs of image manipulation
* Provide confidence scores
* (Optional) Highlight suspicious regions

---

## 🎯 Objectives

* Classify images as:

  * Real
  * AI Generated
  * AI Edited
* Analyze image authenticity using:

  * Deep learning models (CNN)
  * Frequency domain analysis
  * Noise pattern detection
* Build a simple interface for user interaction

---

## 🧪 Methodology

### 1. Dataset

* Real images (camera-captured datasets)
* AI-generated images (diffusion models, GANs)
* Edited/manipulated images

---

### 2. Preprocessing

* Image resizing and normalization
* Data augmentation
* Train-test split

---

### 3. Feature Extraction

* Spatial features (CNN)
* Frequency features (FFT / DCT)
* Noise patterns (sensor vs synthetic)

---

### 4. Model

* Convolutional Neural Network (CNN)
* (Optional) EfficientNet / ResNet

---

### 5. Output

```text
AI Probability: 82%
Real Probability: 15%
Edited Probability: 3%
```

---

## 🛠 Tech Stack

* Python
* TensorFlow / PyTorch
* OpenCV
* NumPy, Pandas
* Matplotlib / Seaborn
* Streamlit (for UI)

---

## 📊 Features

* ✅ AI vs Real classification
* ✅ Detection of editing artifacts
* ✅ Confidence scoring
* 🔄 Explainable results (future scope)
* 🔄 Heatmap visualization (future scope)

---

## 📂 Project Structure

```bash
AI-Image-Detector/
│
├── data/
│   ├── real/
│   ├── ai_generated/
│   └── edited/
│
├── models/
│   └── cnn_model.h5
│
├── notebooks/
│   └── training.ipynb
│
├── app/
│   └── streamlit_app.py
│
├── utils/
│   └── preprocessing.py
│
├── requirements.txt
└── README.md
```

---

## 💻 Installation

```bash
git clone https://github.com/your-username/AI-Image-Detector.git
cd AI-Image-Detector
pip install -r requirements.txt
```

---

## ▶️ Usage

```bash
streamlit run app/streamlit_app.py
```

Upload an image and get authenticity predictions.

---

## 📈 Future Improvements

* 🔍 Region-based fake detection (heatmaps)
* 🧠 Explainable AI (reason-based outputs)
* 🌐 Web deployment
* 📊 Better datasets for higher accuracy

---

## 📚 Research Scope

This project lies at the intersection of:

* Machine Learning
* Computer Vision
* Digital Image Forensics

It can be extended into a **research paper on synthetic media detection**.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork and improve the project.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👤 Author

Your Name
BTech Computer Science Student

---

## ⭐ Acknowledgment

Inspired by ongoing research in AI-generated media detection and digital forensics.
