# Facial-Recognition-Rating-System

Resource Requirements 

Hardware: 

ESP32 Microcontroller 

ESP32 Camera 

Ultrasonic Sensor 

I2C LCD Display 

OLED Display 

Servo Motor 

Battery 

Button 


Software: 

Arduino IDE – ESP32 Firmware 

Image Processing Library - OpenCV, Tensorflow keras, Deepface – Facial Analysis 

Web Framework - Flask, Python to SQL database connector 

Database – Xampp, SQL 


# 🎯 Facial Recognition Rating System

An embedded **AI + IoT computer vision system** that detects faces, performs real-time facial analysis, and outputs ratings or identity results through a physical microcontroller interface.

This project connects **hardware + AI + backend + database** into one complete pipeline.

> Camera → AI → Server → Database → Physical Feedback

---

## 📌 Overview

This system integrates:

- 🔌 Embedded hardware (ESP32 + sensors)
- 🧠 Computer vision (OpenCV + Deep Learning)
- 🌐 Backend API (Flask)
- 🗄️ SQL database storage
- ⚙️ Physical outputs (LCD / OLED / Servo)

The goal was to design a **full end-to-end system**, not just a model — from sensing the real world to producing physical responses.

---

## 📸 System Preview

<p align="center">
  <img width="697" src="https://github.com/user-attachments/assets/f500e6eb-2cd4-4125-9242-9c47cfa825df" />
  <br><br>
  <img width="1115" src="https://github.com/user-attachments/assets/51737c96-d0da-4c74-b7d0-02dc20b7e377" />
  <br><br>
  <img width="1025" src="https://github.com/user-attachments/assets/ae26f28f-a0bf-48de-8637-54a427c24979" />
</p>

---

## ✨ Features

- 📷 Real-time face capture via ESP32 Camera  
- 🧠 Face detection with OpenCV  
- 🤖 Facial analysis using DeepFace / TensorFlow / Keras  
- ⭐ Custom rating / scoring logic  
- 🖥️ Results shown on LCD & OLED displays  
- 🌐 Flask server for processing & logging  
- 🗄️ SQL database storage  
- ⚙️ Button + servo motor for physical interaction  

---

## 🧩 System Architecture

```text
ESP32 Camera
     ↓
Image Capture
     ↓
Flask Server (Python)
     ↓
OpenCV + DeepFace Processing
     ↓
Rating / Recognition Result
     ↓
SQL Database Storage
     ↓
ESP32 → LCD / OLED / Servo Feedback
```

---

## 🔌 Hardware Components

| Component | Purpose |
|-----------|-----------|
| **ESP32 Microcontroller** | Main controller |
| **ESP32 Camera** | Image capture |
| **Ultrasonic Sensor** | Distance-based trigger |
| **I2C LCD Display** | Text output |
| **OLED Display** | Status / visual feedback |
| **Servo Motor** | Physical response mechanism |
| **Button** | Manual trigger input |
| **Battery** | Portable power supply |

---

## 💻 Software Stack

### 🧠 AI / Computer Vision
- **OpenCV**
- **TensorFlow**
- **Keras**
- **DeepFace**

### 🌐 Backend
- **Python**
- **Flask API**

### 🗄️ Database
- **MySQL (XAMPP)**
- **Python SQL Connector**

### 🔧 Firmware
- **Arduino IDE**
- **ESP32 firmware**

---

## ⚙️ How It Works

### Flow

1. User approaches device  
2. Ultrasonic sensor detects presence  
3. ESP32 camera captures image  
4. Image sent to Flask server  
5. OpenCV + DeepFace performs analysis  
6. Rating/identity computed  
7. Result stored in SQL database  
8. LCD/OLED/servo provides feedback  

---
