# 🧠 Aggressive Behavior Detection

This project detects **aggressive human behavior** in video streams using deep learning. 💥 By combining **CNN** and **LSTM** models, it analyzes video sequences to identify signs of aggression — useful for security 🎥, surveillance 🛡️, and behavior analysis 🔬.

---

## 📂 Table of Contents

* [📌 Overview](#-overview)
* [🗂️ Project Structure](#️-project-structure)
* [⚙️ Installation](#️-installation)
* [🚀 Usage](#-usage)
* [🧬 Model Architecture](#-model-architecture)
* [📈 Results](#-results)
* [🤝 Contributing](#-contributing)
* [📝 License](#-license)

---

## 📌 Overview

🎯 Goal: Detect aggression in real-time video feeds.

🔧 Steps:

* Convert videos into NumPy arrays.
* Train a **MobileNet + LSTM** model.
* Run detection on videos or webcam streams.

---

## 🗂️ Project Structure

```bash
📁 01_video-to-numpy-save.ipynb       # Convert videos to NumPy arrays
📁 02_MobileNet.ipynb                 # Feature extraction using MobileNet
📁 03_MobileNet+LSTM_model_training   # Train CNN + LSTM model
📁 04_Apply-model-to-Video.ipynb      # Run model on new video input
📁 05_labtop_webcam_streaming.ipynb   # Real-time webcam aggression detection
```

---

## ⚙️ Installation

1. 📥 Clone the repo:

```bash
git clone https://github.com/mohamedsalama677/-Aggressive-behavior-detection-.git
cd -Aggressive-behavior-detection-
```

2. 🧪 Create virtual environment (optional):

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. 📦 Install dependencies:

```bash
pip install -r requirements.txt
```

> 📝 *If `requirements.txt` is missing, install key packages manually (TensorFlow, OpenCV, NumPy, etc.).*

---

## 🚀 Usage

🔹 **Step 1** – Preprocess videos
➡️ Run `01_video-to-numpy-save.ipynb`

🔹 **Step 2** – Train model
➡️ Run `03_MobileNet+LSTM_model_training.ipynb`

🔹 **Step 3** – Evaluate predictions
➡️ Run `04_Apply-model-to-Video.ipynb`

🔹 **Step 4** – Real-time detection
➡️ Run `05_labtop_webcam_streaming.ipynb`

---

## 🧬 Model Architecture

* 📸 **MobileNet** for fast & lightweight frame-level feature extraction
* 🔁 **LSTM** layers to capture motion across time

🧠 Together, they create a powerful system for spatial-temporal aggression recognition.

---

## 📈 Results

📊 *Add your results here!*
Include:

* Accuracy
* Confusion matrix
* Prediction samples (screenshots/GIFs)

---

## 🤝 Contributing

Got an idea or found a bug? Contributions are welcome! 🎉

1. Fork this repo 🍴
2. Create a feature branch 🌿
3. Submit a pull request 🔁

📬 **Contact:** [mohamedsalama152019@gmail.com](mailto:mohamedsalama152019@gmail.com)


