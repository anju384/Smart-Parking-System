# 🚗 Smart Parking Management System

This project is a software-based indoor smart parking system that allows users
to view available parking slots, reserve a slot using a QR-based interface, and
simulate automated entry and exit validation.

The project was developed as part of a college course to demonstrate how
real-world parking systems can be modeled using software instead of expensive
hardware.

---

## 📌 Project Overview

Traditional parking systems rely on manual processes and lack real-time
visibility of parking availability. This leads to delays, congestion, and poor
user experience.

This project addresses these issues by providing:
- A real-time digital parking layout
- QR-based slot reservation and exit verification
- A centralized backend to track users and slots
- A system that is scalable toward AI-based vehicle detection in the future

---

## 🛠️ Technologies Used

- Python
- Flask (backend web server)
- OpenCV (planned for object detection extension)
- QRCode library
- HTML, CSS, JavaScript (frontend)
- SQLite / MySQL (database)

---

## ⚙️ How the system works

1. User scans an entry QR code and opens the parking interface on their phone  
2. User registers and selects an available parking slot  
3. The system generates a unique exit QR / exit code  
4. Slot status is updated in real-time (Vacant → Occupied)  
5. At exit, the user enters the exit code to free the slot  

The admin interface and user interface stay synchronized through the backend.

---

## 📂 Main Features

- QR-based slot selection using a mobile interface  
- Real-time parking slot visualization  
- Unique exit QR generation for validation  
- Centralized backend for slot and user tracking  
- Modular design for future integration with object detection (YOLO / OpenCV)

---



## 🚀 How to Run (Basic)

```bash
pip install -r requirements.txt
python app.py
