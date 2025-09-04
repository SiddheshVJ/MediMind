# 📱 Smart Medicine Reminder App

A **mobile application** that helps users, especially elderly people, remember to take their medicines on time. The app sends **push notifications, voice alerts, and WhatsApp reminders**, and supports **prescription scanning (OCR)** for auto-scheduling medicines.

---

## 🚀 Installation

### **Backend (Flask API)**

```bash
cd backend_api
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

### **Frontend (React Native App)**

```bash
cd mobile_app
npm install
npx react-native run-android   # or run-ios
```

> Make sure to set up **Firebase** for push notifications and configure **Twilio API** for WhatsApp reminders.

---

## ✅ Features

* User Authentication (Register/Login)
* Add Medicine Schedule (Name, Dosage, Time, Repeat)
* Prescription OCR (Scan and auto-fill medicines)
* Push Notifications via Firebase Cloud Messaging (FCM)
* Voice Alerts for reminders
* WhatsApp Reminders via Twilio API

---

## 👨‍💻 Developed by

**Siddhesh Jadhav**
