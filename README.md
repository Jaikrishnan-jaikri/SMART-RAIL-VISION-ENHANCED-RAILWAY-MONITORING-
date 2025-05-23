# SMART-RAIL-VISION-ENHANCED-RAILWAY-MONITORING-
A YOLOv8-powered real-time safety monitoring system for railway stations

# 🚨 Crime and Emergency Alert Detection Using YOLOv8

A real-time object detection system designed to identify humans, emergency gestures, and crime alerts in public places like railway stations using a custom-trained YOLOv8 model.

---

## 📌 Problem Statement

Railway stations in India face security challenges due to growing passenger volumes and limited real-time monitoring. Traditional CCTV surveillance lacks automation and quick response capabilities. This project addresses this gap by building an AI-powered alerting system using sign gesture recognition.

---

## ✅ Proposed Solution

We implemented a lightweight YOLOv8-based solution that detects humans and hand gestures corresponding to emergencies or crimes in real-time video feeds. The system is trained on a custom dataset and provides alerts using audio and visual cues for quick response.

---

## 🔍 Features

- 🎯 Real-time detection of:
  - Human presence
  - Emergency gestures
  - Crime-indicating gestures (e.g., 'X' sign from sign language)
- 📦 YOLOv8 custom model trained on Roboflow-annotated dataset
- 🔊 Audio alert system for real-time response
- 💻 Runs in Google Colab (training) and local machine (inference)
- 📊 Evaluation metrics: Precision, Recall, F1-score, mAP@0.5, mAP@0.5:0.95

---

## 🧠 Technologies Used

- Python 3.10
- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- OpenCV
- Google Colab (for training)
- Flask (optional for deployment)
- Roboflow (for dataset creation and augmentation)

---

## 🖼️ Sample Output

![image](https://github.com/user-attachments/assets/b16c356c-f4f0-4d57-af40-8ee1460beb12)

