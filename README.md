# 🤖 Hand Gesture-Controlled Car  

A smart car project that can be controlled using **hand gestures** instead of traditional remote controls. By using an **accelerometer sensor and Arduino**, the car responds to hand tilts and moves **forward, backward, left, right, or stop** in real-time.  

---

## 🚀 Features  
- Wireless gesture-based control using an **Accelerometer + Arduino**  
- Simple and low-cost hardware setup  
- Real-time car movement in **five directions (F, B, L, R, Stop)**  
- Uses **serial communication protocols** (Bluetooth / RF)  
- Beginner-friendly robotics project  

---

## 🛠️ Tech Stack & Components  
- **Arduino Uno / Nano**  
- **Accelerometer sensor (ADXL335 / MPU6050)**  
- **Motor driver (L293D / L298N)**  
- **DC motors with chassis**  
- **Wireless module (HC-05 Bluetooth / RF Tx-Rx)**  
- Programming Language: **Embedded C / C++ (Arduino IDE)**  

---

## ⚙️ Working Principle  
1. The **accelerometer sensor** is mounted on a glove/hand.  
2. Hand movements (tilts) are detected as **X, Y axis values**.  
3. These values are sent wirelessly to the Arduino on the car.  
4. Arduino processes the signals and drives the **motor driver IC**.  
5. The car moves in the direction corresponding to the gesture.  

---

## 📌 Circuit Diagram  
![Gesture-Controlled Car  ](https://github.com/user-attachments/assets/6121c04e-1284-48c4-9b17-3866063197c0)



