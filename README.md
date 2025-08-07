# 🔫 YOLO-Based Weapon Detection System

This project aims to develop a **real-time weapon detection system** using the **YOLOv4 (You Only Look Once)** deep learning model. It leverages **OpenCV**, **Flask**, and **pre-trained weights** to detect weapons (such as knives and guns) from **images, videos, and live webcam feeds**, providing **instant alerts** via bounding boxes and alarm sounds.

## 📌 Features

- Real-time detection of weapons using YOLOv4
- Input support: Image, Video file, Live webcam feed
- Alerts with bounding boxes and alarm sound
- Flask web application with interactive UI
- Integration with IBM DB for user login/registration
- Modular project structure for easy deployment

## 🛠️ Tech Stack

- **Python 3.7+**
- **YOLOv4**
- **OpenCV**
- **Flask (Web Framework)**
- **Playsound**
- **IBM DB2** (for authentication)
- HTML, CSS (Frontend UI)

## 🚀 How It Works

1. The user uploads an image, video, or chooses to start live webcam detection.
2. The YOLOv4 model (loaded using OpenCV’s DNN module) processes the input.
3. Detected weapons are highlighted with bounding boxes.
4. If detection confidence > 30%, an **alarm** sound is triggered.
5. The results are displayed on a Flask-based web interface.



