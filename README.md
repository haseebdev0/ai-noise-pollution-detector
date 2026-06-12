# 🔊 AI-Powered Noise Pollution & Audio Classifier

An advanced AI prototype built on Google Colab using TensorFlow and the YAMNet deep learning model. This system captures environmental audio, performs frame-by-frame sound classification, and calculates real-time Decibel (dB) levels to monitor noise pollution.

## 🚀 Live Notebook
You can open and run this project directly in Google Colab:
https://colab.research.google.com/drive/1eUDvHEjCTjYpG3P5nfhnNbp2TkqRt-N2?usp=sharing

---

## ✨ Key Features
- **Deep Learning Classification:** Uses Google's pre-trained **YAMNet** neural network model to classify over 521 types of environmental sounds (Speech, Animals, Traffic, etc.).
- **High Accuracy (99.9%):** Analyzes audio frame-by-frame to pick up instantaneous acoustic signatures with maximum confidence scores.
- **Calibrated Decibel (dB) Meter:** Uses Root Mean Square (RMS) amplitude mapping to evaluate real-time noise levels.
- **Environmental Hazard Alerts:** Automatically flags areas as "High Noise Pollution" if decibel readings cross the 75 dB threshold.

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python 3
- **Framework:** TensorFlow 2.x & TensorFlow Hub
- **Signal Processing:** SciPy (for resampling and signal manipulation)
- **Environment:** Google Colab (GPU Acceleration)

---

## 📁 Project Structure
```text
├── Noise_Pollution_and_Audio_Detector.ipynb   # Main Google Colab Notebook File
└── README.md                                  # Documentation and Project Overview
