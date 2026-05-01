# ⚡ Autonomous Edge Node for Inductive AC Loads  
### Embedded Intelligence + Hardware Protection using TinyML

## 🚀 Overview
This project presents an intelligent edge-based protection system for high-power inductive AC loads such as motors and pumps.

It leverages an ESP32 microcontroller combined with TinyML to detect anomalous current patterns (e.g., dry-run conditions) and perform real-time autonomous shutdown — ensuring hardware safety without relying on cloud processing.

---

## 🎯 Key Features

- 🔌 Real-time monitoring of inductive AC loads
- 🧠 TinyML-based anomaly detection on-device
- ⚡ Instant emergency shutdown via relay module
- 📡 MQTT-based remote monitoring & control
- 📱 Mobile-friendly backend for alerts & configuration
- 🛡️ Fault-tolerant design (works even without internet)

---

## 🧱 System Architecture

![Architecture](docs/architecture_diagram.png)

---

## ⚙️ Hardware Components

- ESP32 Microcontroller
- ACS712 Current Sensor
- 30A Relay Module
- Inductive Load (Motor/Pump)

---

## 🧠 TinyML Model

- Trained on current waveform patterns
- Detects:
  - Low-load anomalies (dry run)
  - Irregular current signatures
- Deployed using TensorFlow Lite for Microcontrollers

---

## 🔄 Workflow

1. Current data captured via ACS712
2. Signal processed on ESP32
3. TinyML model performs inference
4. If anomaly detected:
   - Relay triggers shutdown ⚡
5. Data sent via MQTT for monitoring

---

## 📡 MQTT Integration

- Real-time status updates
- Remote timer configuration
- Alert notifications

---

## 🛠️ Tech Stack

- Embedded C / Arduino
- ESP32
- TensorFlow Lite (TinyML)
- MQTT Protocol
- Python (Model Training)

---

## 📊 Use Cases

- Industrial motor protection
- Agricultural pump monitoring
- Smart energy systems
- Edge AI in safety-critical environments

---

## 🎥 Demo

## [Demo Video](demo/demo_video_link.md)

---

## 📌 Future Improvements

- Edge-to-cloud analytics dashboard
- Multi-sensor fusion (temperature + vibration)
- Predictive maintenance using time-series ML
- OTA firmware updates

---

## 👨‍💻 Author

**Anshu Aditya**  
DevOps Engineer | Embedded Systems Enthusiast  
