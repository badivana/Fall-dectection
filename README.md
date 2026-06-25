<h1 align="center">
🚨 Fall Detection System
</h1>

<p align="center">
AI-powered Fall Detection using Arduino, MPU6050 and TinyML
</p>

<p align="center">
<img src="https://img.shields.io/badge/Arduino-Embedded-blue">
<img src="https://img.shields.io/badge/TinyML-Machine%20Learning-green">
<img src="https://img.shields.io/badge/Python-3.x-yellow">
<img src="https://img.shields.io/badge/License-MIT-success">
<img src="https://img.shields.io/badge/Status-Completed-brightgreen">
</p>
# 🚨 Fall Detection System

An AI-powered Fall Detection System built using Arduino and motion sensors to detect accidental falls in real time. The project uses a trained machine learning model to classify sensor data and identify fall events.

---

## 📌 Features

* 📈 Real-time fall detection
* 🤖 Machine learning-based classification
* ⚡ Runs on Arduino-compatible hardware
* 📊 Motion sensor data processing
* 🔍 Lightweight and efficient inference

---

## 📂 Project Structure

```
Fall-dectection/
│
├── fall_detection/
│   ├── config.h
│   ├── fall_classifier.h
│   ├── fall_detection.ino
│   └── model.h
│
├── python_tools/
│
└── README.md
```

---

## 🛠 Hardware Requirements

* Arduino-compatible board
* MPU6050 Accelerometer & Gyroscope
* USB Cable
* Computer with Arduino IDE

---

## 💻 Software Requirements

* Arduino IDE
* Required Arduino libraries
* Python 3.x (for data preprocessing and model tools)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/badivana/Fall-Detection-System.git
```

### 2. Open the Arduino project

Open:

```
Fall-Detection-System//fall_detection.ino
```

using the Arduino IDE.

### 3. Install required libraries

Install the libraries required by the project using the Arduino Library Manager.

### 4. Upload the code

* Select your board.
* Select the correct COM port.
* Upload the sketch.

---

## ⚙ How It Works

1. Motion data is collected from the MPU6050 sensor.
2. The sensor readings are processed.
3. The embedded machine learning model classifies the motion.
4. If a fall is detected, the system triggers an alert or detection event.

## Work Flow
```text
MPU6050
    │
    ▼
Acceleration + Gyroscope
    │
    ▼
Feature Extraction
    │
    ▼
Embedded TinyML Model
    │
    ▼
Fall Classification
    │
    ▼
Alert Generation
```
---
## Hardware Workflow

MPU6050
     │
     ▼
Arduino
     │
     ▼
TinyML Model
     │
     ▼
Decision
---

## 📁 Files

| File                 | Description                            |
| -------------------- | -------------------------------------- |
| `fall_detection.ino` | Main Arduino program                   |
| `config.h`           | Configuration settings                 |
| `model.h`            | Embedded ML model                      |
| `fall_classifier.h`  | Classification logic                   |
| `python_tools/`      | Python utilities for model preparation |

---

## 🎯 Applications

* Elderly care
* Patient monitoring
* Smart healthcare
* Home safety systems
* Wearable devices

---
## ⚠️ Limitations

- Requires proper sensor calibration
- Performance depends on model quality
- Tested with MPU6050 sensor
- Does not include emergency communication

---

## 📈 Future Improvements

* Mobile app notifications
* IoT cloud integration
* GPS-based emergency alerts
* Higher accuracy ML model
* Battery optimization

---

## 👨‍💻 Author

**Prajwal B T**

Information Science Engineering Student


---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
