# 🧠# 🔤 Real-Time Sign Language Translator

A deep learning-based system that translates hand gestures into text across 6 Indian languages — Hindi, Marathi, Tamil, Telugu, Malayalam, and Bengali — using a webcam and a trained CNN model for inclusive communication.

[![Build Status](https://github.com/Sukalevinit/Real-Time-Sign-Language-Translator/actions/workflows/python-app.yml/badge.svg)](https://github.com/Sukalevinit/Real-Time-Sign-Language-Translator/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/Sukalevinit/Real-Time-Sign-Language-Translator)](https://github.com/Sukalevinit/Real-Time-Sign-Language-Translator/commits/main)
[![Stars](https://img.shields.io/github/stars/Sukalevinit/Real-Time-Sign-Language-Translator.svg?style=social)](https://github.com/Sukalevinit/Real-Time-Sign-Language-Translator/stargazers)
[![Forks](https://img.shields.io/github/forks/Sukalevinit/Real-Time-Sign-Language-Translator.svg?style=social)](https://github.com/Sukalevinit/Real-Time-Sign-Language-Translator/network/members)
[![Issues](https://img.shields.io/github/issues/Sukalevinit/Real-Time-Sign-Language-Translator.svg)](https://github.com/Sukalevinit/Real-Time-Sign-Language-Translator/issues)

This project is a real-time sign language recognition system that uses a Convolutional Neural Network (CNN) to detect hand gestures via webcam and translate them into text. It supports multiple Indian languages, making it a valuable tool for inclusive communication.

---

## 🌐 Multi-Indian Language Support

One of the standout features of this project is its ability to display recognized signs in multiple Indian languages, including:

* 🇮🇳 Hindi
* 🇮🇳 Marathi
* 🇮🇳 Tamil
* 🇮🇳 Telugu
* 🇮🇳 Malayalam
* 🇮🇳 Bengali
* 🇮🇳 Kannada
* 🇮🇳 Gujarati
* 🇮🇳 Punjabi

Users can select their preferred language, making the system accessible to a broader audience.

---

## 📁 Project Structure

* `data_collection_binary.py`: Collects training data in binary form.
* `data_collection_final.py`: Extended version for flexible data gathering.
* `final_pred.py`: Main script for real-time prediction and multilingual display.
* `cnn8grps_rad1_model.h5`: Pre-trained model used for gesture classification.
* `requirements.txt`: Python libraries required to run the project.
* `white.jpg`: Utility or placeholder image.
* `.idea/`: IDE-specific files (for PyCharm users).

---

## 🛠️ Installation

```bash
git clone <repo-url>
cd Real-Time-Sign-Language-Translator-main
pip install -r requirements.txt
```

Make sure your system has a functional webcam.

---

## 🚀 How to Use

Run the prediction interface:

```bash
python final_pred.py
```

You will be prompted to choose a language before the translation begins.

---

## 🎯 Features

* Real-time hand sign recognition.
* Multi-language support for Indian regional languages.
* Custom training via data collection scripts.
* Easy deployment with minimal setup.

---

## 💡 Future Enhancements

* Add audio output in selected language.
* Expand sign vocabulary (words/phrases).
* Integrate with mobile devices or web apps.
