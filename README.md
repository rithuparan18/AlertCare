🩺 AlertCare – Real-Time Health & Fall Monitoring System
AlertCare is an ML-powered wearable healthcare monitoring system designed to detect real-time physiological anomalies and accidental falls among elderly individuals. The system combines biomedical sensors, machine learning models, and mobile connectivity to ensure timely alerts and remote caregiver support.

📌 Features
⏱️ Real-time monitoring of SpO₂, heart rate, body temperature, and motion data

🧠 Machine learning–based anomaly detection (Isolation Forest)

🤕 Fall detection using accelerometer and insole pressure sensors with Decision Tree classifier

⚡ Edge–cloud hybrid architecture for low-latency processing and extended battery life

📲 Bluetooth Low Energy (BLE) communication with Android mobile app

📡 Cloud-based alerting and caregiver notification via Firebase

🧾 View past vital spikes and health logs through mobile dashboard

🛠️ Technologies Used
ESP32-S3 microcontroller (hardware interface)

Android Studio + Jetpack Compose (mobile app)

Firebase (cloud backend)

Python + Scikit-learn (ML model training)

Kotlin (mobile frontend)

C++ (firmware for sensor data acquisition)

🚀 Getting Started
Clone this repository:

bash
Copy
Edit
git clone https://github.com/your-username/AlertCare.git
Navigate into the project folders:

/firmware: ESP32 sensor and ML integration code

/mobile-app: Android app for real-time dashboard and alerts

/models: Trained ML models and preprocessing scripts

Upload firmware to ESP32-S3 using Arduino IDE or PlatformIO

Launch the Android app in emulator or physical device

Link to Firebase project via the google-services.json file

📸 Screenshots
Splash screen with branding

User profile setup

Live vitals dashboard

Past logs and alert history

Fall detection emergency alert screen

🎯 Roadmap
 Real-time vitals simulation with Firebase

 ML model integration for anomaly and fall detection

 Hardware pilot testing with clinics

 Regulatory certification for deployment

 Personalized prediction models using extended data
