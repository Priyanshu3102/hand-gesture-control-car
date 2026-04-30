
# 🚗 Hand Gesture Control Car

## 📌 Overview

This project controls a robotic car using hand gestures detected via a camera.

## ⚙️ Technologies Used

* Arduino / ESP8266
* Python (OpenCV, MediaPipe)
* L298N Motor Driver

## 🔧 Features

* Real-time gesture detection
* Wireless control
* Low-cost implementation

## 🖼️ Project Demo

<img width="1536" height="1024" alt="Hand Gesture" src="https://github.com/user-attachments/assets/e52d247a-6773-44ef-b185-7b1d1a0c63ba" />


## 🔌 Circuit Diagram

<img width="1589" height="887" alt="Hand Gesture Circuit" src="https://github.com/user-attachments/assets/05fddb0c-526e-4723-812a-6959ffc673ea" />


## ▶️ How to Run

1. Upload Arduino code to microcontroller
2. Run Python script
3. Perform gestures to control the car
   
## 🧠 Working Principle

The system uses a camera to capture hand gestures. 
OpenCV and MediaPipe detect hand landmarks and calculate movement direction.
These gestures are converted into commands (Forward, Left, Right, Backward) 
and sent wirelessly to ESP8266, which controls the motors via L298N driver.

## 📚 Future Improvements

* Add AI-based gesture recognition
* Improve latency
