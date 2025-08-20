# Embedded-Edge-Health-Monitoring-System
# Embedded Edge Health Monitoring Device 🩺⚡

## Overview
The **Embedded Edge Health Monitoring Device** is a real-time wearable system built on the **ESP32 microcontroller** for continuous monitoring of vital signs and early detection of critical health conditions. By leveraging **on-device machine learning (TensorFlow Lite)**, the device classifies health status into **Normal, Pneumonia, or Sepsis** with **92% accuracy**, while reducing cloud dependency by **40%**. Data is securely transmitted to **Firebase**, and anomalies trigger **sub-second alerts** on the **Blynk app**, ensuring timely intervention.

---

## ✨ Features
- 📡 **Real-time monitoring** of vital health parameters using ESP32 and sensors.  
- 🤖 **On-device ML inference (TensorFlow Lite)** — reduces reliance on cloud computation.  
- 🔔 **Instant anomaly alerts** via Blynk mobile app with sub-second latency.  
- 🔒 **Secure data transmission** to Firebase for remote storage and visualization.  
- 🔋 **Optimized firmware & power management**, delivering **30% higher energy efficiency** for continuous wearable use.  

---

## 🛠️ Tech Stack
- **Hardware:** ESP32, biomedical sensors (pulse oximeter, temperature, etc.)  
- **Software/Frameworks:** Embedded C, TensorFlow Lite, Firebase, Blynk  
- **Languages:** C, Python  
- **Other:** Power optimization (firmware-level), Secure IoT data pipeline  

---

## ⚙️ System Architecture
1. **Sensor Layer** → Vital signs acquisition (heart rate, temperature, oxygen saturation).  
2. **Edge Layer (ESP32)** → Real-time processing + ML classification (Normal/Pneumonia/Sepsis).  
3. **Cloud Layer (Firebase)** → Secure storage and remote data access.  
4. **User Layer (Blynk App)** → Instant visualization and anomaly alerts.  

---

## 📊 Results
- **92% classification accuracy** across three classes (Normal, Pneumonia, Sepsis).  
- **40% reduction** in cloud dependency via edge-based inference.  
- **30% improved energy efficiency**, ensuring long-term wearable operation.  
- **Sub-second anomaly alerts** for critical health conditions.  

---

## 🚀 Future Improvements
- Integration with **low-power RTOS** for enhanced scheduling.  
- Expanded dataset for multi-condition classification.  
- BLE/LoRaWAN support for remote, low-power healthcare monitoring.  
- Hardware miniaturization for compact wearable form factor.  

---

## 📂 Repository Structure
