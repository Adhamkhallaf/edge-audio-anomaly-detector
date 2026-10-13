# Edge-Optimized Audio Anomaly Detector 🎧🔍

An unsupervised acoustic anomaly detection pipeline built for industrial machinery (using the MIMII dataset), optimized for edge deployment using PyTorch and ONNX.

## 🚀 Overview
Industrial machinery monitoring requires detecting abnormal sounds (like failing fans) without relying on pre-existing failure data. This project uses a **Convolutional Autoencoder** trained exclusively on normal audio spectrograms.

## 🗂️ Project Structure
- `models/`: Contains the trained PyTorch weights and exported ONNX model (`.onnx`).
- `requirements.txt`: Project dependencies.
- `Dockerfile`: Container configuration for edge environments.
- `LICENSE`: MIT open-source license.

## 📦 Installation & Usage
1. Install dependencies: `pip install -r requirements.txt`
2. Run ONNX inference using `onnxruntime`.

## 📄 License
Licensed under the MIT License.
