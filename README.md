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


🎯 Facial Recognition Rating System

An embedded AI + IoT computer vision system that detects faces, performs real-time facial analysis, and outputs ratings/identity results through a physical microcontroller interface.

This project integrates:

Embedded hardware (ESP32 + sensors)

Computer vision (OpenCV + Deep Learning)

Backend server (Flask API)

SQL database storage

Physical feedback (LCD/OLED/Servo)

The goal was to build a complete end-to-end pipeline from camera → AI → server → database → hardware response.

---

📸 System Preview

<img width="697" height="573" alt="image" src="https://github.com/user-attachments/assets/f500e6eb-2cd4-4125-9242-9c47cfa825df" />
<img width="1115" height="497" alt="image" src="https://github.com/user-attachments/assets/51737c96-d0da-4c74-b7d0-02dc20b7e377" />
<img width="1025" height="696" alt="image" src="https://github.com/user-attachments/assets/ae26f28f-a0bf-48de-8637-54a427c24979" />

---

✨ Features

📷 Real-time face capture via ESP32 Camera

🧠 Face detection using OpenCV

🤖 Facial analysis using DeepFace / TensorFlow / Keras

⭐ Rating or scoring logic

🖥️ Results displayed on LCD & OLED

🌐 Flask web server for processing & logging

🗄️ SQL database storage

⚙️ Physical interaction via button + servo motor

---

🧩 Architecture
ESP32 Camera
     ↓
Capture Image
     ↓
Flask Server (Python)
     ↓
OpenCV + DeepFace Processing
     ↓
Rating / Recognition Result
     ↓
SQL Database Storage
     ↓
ESP32 → LCD/OLED/Servo Feedback

---

🔌 Hardware Components
| Component             | Purpose                    |
| --------------------- | -------------------------- |
| ESP32 Microcontroller | Main controller            |
| ESP32 Camera          | Image capture              |
| Ultrasonic Sensor     | Distance/trigger detection |
| I2C LCD Display       | Text output                |
| OLED Display          | Status/visual feedback     |
| Servo Motor           | Physical response          |
| Button                | Manual trigger             |
| Battery               | Portable power supply      |

---

💻 Software Stack
AI / Computer Vision

OpenCV

TensorFlow

Keras

DeepFace

Backend

Python

Flask

Database

MySQL (XAMPP)

Python SQL connector

Firmware

Arduino IDE (ESP32 firmware)

---

