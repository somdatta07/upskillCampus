# upskillCampus

## 🎯 Project: Emotion Recognition from Speech

**Domain:** Data Science & AI/ML
**Internship:** upskillCampus

---

## 📌 Objective

Recognize human emotions (happy, sad, angry, neutral, etc.) from speech audio using Deep Learning and Speech Signal Processing.

---

## 📋 Short Summary of Implementation

This project implements a Speech Emotion Recognition (SER) system that classifies human emotions — happy, sad, angry, fearful, neutral, calm, disgust, and surprised — from speech audio using deep learning. Audio recordings from the RAVDESS dataset were processed to extract MFCC (Mel-Frequency Cepstral Coefficient) features, capturing the key spectral characteristics of speech. These features were fed into an LSTM neural network, built using TensorFlow/Keras, to model the sequential nature of speech and learn patterns associated with different emotional states. The trained model was evaluated on unseen audio samples to predict emotions, with the complete pipeline implemented in Python on Google Colab. The system has applications in human-computer interaction, virtual assistants, customer support, and mental health monitoring.

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook / Google Colab
- TensorFlow / Keras
- Librosa
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

---

## 📂 Dataset

**Recommended:** [RAVDESS Dataset](https://zenodo.org/record/1188976)

Contains emotions like:
- Happy
- Sad
- Angry
- Fearful
- Neutral
- Calm
- Disgust
- Surprised

---

## 📦 Install Required Libraries

```bash
pip install librosa tensorflow numpy pandas matplotlib scikit-learn
```

---

## 📁 Repository Structure

```
├── dataset/
│   └── audio files
│
├── emotion_recognition.ipynb      # Final code (Jupyter/Colab notebook)
├── model.h5                       # Trained model
├── Final_Project_Report.pdf       # Final project report (as per provided sample)
└── README.md
```

> ✅ This repository contains **both the final code** (`emotion_recognition.ipynb`, `model.h5`) **and the final project report** (`Final_Project_Report.pdf`), as required for submission.

---

## 📖 Introduction

Speech Emotion Recognition (SER) is a system that identifies human emotions from voice signals using machine learning and deep learning techniques.

---

## 🔬 Methodology

1. **Data Collection** — Used the RAVDESS dataset containing emotional speech recordings.
2. **Feature Extraction** — MFCC (Mel-Frequency Cepstral Coefficients) features extracted from audio signals.
3. **Model Used** — LSTM neural network for sequential speech analysis.
4. **Training** — Model trained using TensorFlow/Keras.
5. **Prediction** — Model predicts emotion from unseen audio files.

---

## 📌 Advantages

- Improves human-computer interaction
- Supports mental health analysis
- Enables call center monitoring
- Enhances virtual assistants

---

## 📌 Applications

- AI Assistants
- Customer Support
- Smart Healthcare
- Emotion-based recommendation systems

---

## 📌 Future Improvements

- Real-time emotion detection
- Better accuracy using CNN + LSTM hybrid models
- Noise reduction techniques
- Training on more diverse datasets

---

## 📑 Final Project Report

The final project report (`Final_Project_Report.pdf`) is included in this repository and follows the provided sample format, with all required fields populated, including:

- Cover Page (Project Title, Name, Institution details)
- Table of Contents
- Introduction & Objective
- Methodology
- Implementation Details
- Results & Screenshots
- Advantages, Applications & Future Scope
- Conclusion
- References

> **Note on Table of Contents:** The Table of Contents in the report has been generated using Word's automatic TOC feature and can be refreshed anytime by **right-clicking on the Table of Contents and selecting "Update Field" → "Update entire table"**, so page numbers and headings stay in sync with the document.

---

## 🔗 Project Links

- **Full Colab Code:** [Open in Colab](https://colab.research.google.com/drive/1k4LJjg7OYd9uEhWY8zpG7TgMCWKsbemx?usp=sharing)
- **Final Report:** See `Final_Project_Report.pdf` in this repository
