# Smart Pet-Behavior Monitoring & Notification System ("Pet E-keeper")

**Award-winning Full-stack IoT ecosystem for pet safety and real-time activity tracking.**
*National Finalist & "Young Innovator" title recipient.*

## 📋 Project Overview
"Pet E-keeper" is an intelligent notification system designed to track pet movements and provide owners with real-time data. The system identifies specific animals using RFID and notifies owners about events such as pets escaping the property, returning home, or occupying designated areas (e.g., porches, windowsills, or pet beds).

## 🚀 Key Features
- **Dual-Sensor Identification:** - **RFID Tags:** Precision tracking for individual pets via unique collar-mounted tags.
  - **Contact Sensors:** Presence detection on specific platforms (e.g., mats or windowsills) to complement RFID data.
- **Advanced Notifications:** - Real-time text alerts and **voice notifications**.
  - Background operation: receiving alerts even when the phone is in sleep mode.
- **Remote Monitoring:** Global access to pet status via Firebase Cloud integration.
- **Multi-Location Support:** Ability to distinguish messages based on which sensor was triggered (e.g., "Front Door" vs. "Garden Gate").

## 🛠 Tech Stack
- **Hardware:** ESP32 (Wi-Fi/Bluetooth SoC), RFID RC522 Reader, Contact Sensors.
- **Mobile App:** Native Android Application (Java) built in Android Studio.
- **Cloud & Backend:** Firebase Realtime Database & Firebase Authentication.
- **Communication:** HTTP/JSON protocols.

## 🏗 System Components
1. **The Tag:** A programmed RFID key fob mounted on the animal's collar.
2. **The Hub (ESP32):** An electronic controller that bridges hardware sensors with the Internet. It handles Wi-Fi connectivity and processes data logic.
3. **The Mobile App:** A dedicated Android interface for user authorization and event logging. It allows for receiving notifications 24/7, even in sleep mode.

---
*Note: This repository contains technical documentation and project overview. The full source code is private due to contest regulations and academic policies.*

## 📱 Mobile Application Interface

The Android application serves as the central hub for the Pet E-keeper system. It features a native UI built with **Java** in Android Studio, integrated with **Firebase Authentication** for secure access and **Firebase Realtime Database** for instant pet status updates.

<p align="center">
  <img src="images/Zrzut%20ekranu%202026-04-22%20172127.png" width="22%" style="margin: 5px;" alt="App Interface 1" />
  <img src="images/Zrzut%20ekranu%202026-04-22%20172152.png" width="10%%" style="margin: 5px;" alt="App Interface 2" />
  <img src="images/Zrzut%20ekranu%202026-04-22%20172203.png" width="22%" style="margin: 5px;" alt="App Interface 3" />
  <img src="images/Zrzut%20ekranu%202026-04-22%20172222.png" width="22%" style="margin: 5px;" alt="App Interface 4" />
</p>
<p align="center">
  <img src="images/Zrzut%20ekranu%202026-04-22%20172232.png" width="22%" style="margin: 5px;" alt="App Interface 5" />
  <img src="images/Zrzut%20ekranu%202026-04-22%20172302.png" width="22%" style="margin: 5px;" alt="App Interface 6" />
  <img src="images/Zrzut%20ekranu%202026-04-22%20172308.png" width="22%" style="margin: 5px;" alt="App Interface 7" />
</p>

*Above: Comprehensive views of the mobile interface, including user authorization flow (Log In & Register) and notification logs.*
