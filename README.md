# 🎙️ Bangla Speech Emotion Recognition

A Deep Learning-based system to classify emotions from Bangla speech audio.

---

## 🚀 Features

* 🎧 Emotion detection from `.wav` audio
* 🧠 Deep Neural Network (DNN) model
* 📊 59-dimension audio feature extraction (MFCC + Chroma + Spectral Contrast)
* 🔁 Data augmentation support
* ⚡ Real-time prediction

---

## 📂 Dataset

🔗 https://drive.google.com/drive/folders/1wLOnVxhYmOTD7RtOKARQ0tsd8P1cXLKw

**Classes:**

* Angry
* Happy
* Natural
* Sad
* Surprised

> Place the dataset inside your project directory like this:

```
dataset/
 ├── Angry/
 ├── Happy/
 ├── Natural/
 ├── Sad/
 └── Surprised/
```

---

## 🧠 Model

* Input: 59 features
* Dense (256) → Dropout
* Dense (128) → Dropout
* Output (5 classes - Softmax)

---

## 📈 Performance

* Accuracy: **~98%**
* Fast inference (~50ms)

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/bangla-ser.git
cd bangla-ser
pip install -r requirements.txt
```

---

## ▶️ Usage

### Train Model

```bash
python train.py
```

### Predict Emotion

```bash
python predict.py --file test.wav
```

---

## 🛠️ Tech Stack

* Python
* Librosa
* Scikit-learn
* TensorFlow / Keras

---

## 👨‍💻 Authors

* Sajjad Hosen Emon
* Sobuj Gupta

---

## ⭐ Notes

* Make sure dataset is downloaded before running
* Works best with clean audio input

---
