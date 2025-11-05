# Smart Parking Management System

A JavaFX-based desktop application integrated with Arduino hardware for real-time parking slot monitoring and RFID-based access control. This system provides automated parking management by detecting vehicle presence, authenticating entry, and maintaining activity logs.

---

## 🚀 Features

- **Real-time Parking Slot Monitoring** with visual availability indicators  
- **RFID-based Secure Access Control** for entry authorization  
- **Interactive JavaFX Dashboard** with dynamic UI components  
- **Serial Communication** with Arduino using jSerialComm  
- **Automated Access Logging** with timestamps and status updates  
- **Reservation Management Module** with extensible payment support  

---

## 🖼️ Screenshots

| Dashboard UI | Slot Status Display | Access Log Screen |
|-------------|--------------------|------------------|
| ![Dashboard Screenshot](https://github.com/JainDikshaa/iot-smart-parking-system/blob/main/Screenshot%202025-11-03%20231305.png) | ![Slot UI](https://github.com/JainDikshaa/iot-smart-parking-system/blob/main/Screenshot%202025-11-03%20234956.png) | ![Log UI](https://github.com/JainDikshaa/iot-smart-parking-system/blob/main/Screenshot%202025-11-04%20132236.png) |

> Replace the above images with real screenshot links once added to `/docs/screenshots/` or uploaded to GitHub.

---

## 🛠️ Technology Stack

| Layer        | Technologies Used |
|-------------|------------------|
| Frontend    | JavaFX, FXML, CSS |
| Backend     | Java (JDK 8+), MVC Architecture |
| Database    | MySQL + JDBC |
| Hardware    | Arduino Uno, IR Sensors, RFID RC522, LEDs |
| Build Tool  | Maven |
| Communication | Serial Port (jSerialComm) |

---

## 📋 Prerequisites

- Java JDK 8 or higher  
- MySQL Server  
- Arduino IDE  
- Maven  
- jSerialComm Library  

---

## 🔧 Hardware Setup

| Component | Pins / Connection |
|----------|-------------------|
| IR Sensors | Analog Pins A0, A1 |
| RFID RC522 Module | Digital Pins 9 & 10 |
| LEDs (Slot Indicators) | Digital Pins 2, 3, 4, 5 |
| Arduino to PC | USB Serial Connection |

---

## 🚀 Running the Application

### 1. Clone the Repository
```bash
git clone https://github.com/JainDikshaa/smart-parking-system.git
