# 📱 Sleep Stage Classification - Mobile App

This repository contains a **Flutter-based mobile application** developed for a scientific research project (NCKH) on **Sleep Stage Classification using AI**.

The app allows users to interact with trained models and visualize sleep stage predictions from EEG data.

---

## 🚀 Features

* 📂 Process EEG-related input data
* 🤖 Integrate AI models (CNN, LSTM, Random Forest)
* 📊 Predict sleep stages:

  * Wake (W)
  * N1
  * N2
  * N3
  * REM
* 📱 Mobile-friendly UI built with Flutter

---

## 🧩 Project Structure

```bash
Model_App/
│
├── NCKHFIX/                # Flutter application
│   ├── lib/                # UI & logic
│   ├── android/            # Android config
│   ├── assets/             # App assets
│   ├── server/             # Backend/API (if used)
│   └── pubspec.yaml
│
├── .gitignore
├── README.md
```

---

## ⚙️ Installation

### 1. Clone repository

```bash
git clone https://github.com/HoangKhai1911/nckh-model-app.git
cd nckh-model-app/NCKHFIX
```

---

### 2. Install dependencies

```bash
flutter pub get
```

---

### 3. Run application

```bash
flutter run
```

---

## 🧠 AI Model

The application is designed to work with trained models from the main research project.

📥 Download model & dataset here:

* Dataset: https://drive.google.com/drive/folders/1L6v5g6bjPmWasZPxk1TjTrGdMc41Wr8U?usp=drive_link

---

## 🔗 Related Repository

👉 Main research project:
https://github.com/HoangKhai1911/nckh

---

## 📊 Technologies Used

* Flutter (Dart)
* Python (AI Model - external)
* TensorFlow / Keras
* REST API (if backend used)

---

## 📌 Notes

* Large files (models, datasets, videos) are excluded from this repository
* Make sure to download required files before running the app
* Backend/API (if used) must be running for full functionality

---

## 👨‍💻 Author

* Hoang Khai
* GitHub: https://github.com/HoangKhai1911

---

## ⭐ About

This project is part of a **scientific research (NCKH)** focusing on applying **Artificial Intelligence in healthcare**, specifically sleep stage classification using EEG signals.

---
