# 🌿 FloraCare – AI-Powered Plant Identifier & Care App

FloraCare is a mobile application that helps users **identify plants using photos** and provides **clear, actionable care instructions** such as watering, sunlight, soil, and temperature needs. The app is designed as a fast, modern MVP using **React Native + Expo**, and runs seamlessly on real Android devices via **Expo Go**.

---

## 🚀 Features

* 📸 **Plant Identification**
  Upload or capture a photo of a plant and identify it using an AI-powered image recognition API.

* 🌱 **Actionable Plant Care Guidance**
  Easy-to-understand care instructions including:

  * Watering frequency
  * Sunlight requirements
  * Temperature range
  * Soil recommendations
  * Fertilizer guidance

* 📱 **Real Device Testing**
  Built with Expo for rapid iteration and tested on a real Android device using Expo Go.

* 🧱 **Clean Architecture**

  * Expo Router (file-based navigation)
  * TypeScript
  * Separated API & care-logic layers

---

## 🛠️ Tech Stack

* **Frontend:** React Native, Expo, Expo Router
* **Language:** TypeScript
* **AI API:** Plant.id (image-based plant identification)
* **State & Logic:** React Hooks
* **Platform:** Android (Expo Go)

---

## 📂 Project Structure (Simplified)

```
FloraCare/
├── app/                # Expo Router screens
│   ├── (tabs)/         # Tab navigation
│   ├── modal.tsx       # Identification & care result screen
│   └── _layout.tsx
├── services/           # API integration layer
├── utils/              # Plant care logic & mappers
├── components/         # Reusable UI components
├── assets/             # Images & static assets
├── app.json            # Expo configuration
└── README.md
```

---

## ▶️ Running the App Locally

### Prerequisites

* Node.js (v18+ recommended)
* Expo CLI
* Expo Go app installed on Android device

### Steps

```bash
npm install
npx expo start
```

1. Open **Expo Go** on your phone
2. Scan the QR code shown in the terminal or browser
3. App loads instantly on your device

---

## 🔑 Environment Configuration

The Plant Identification API key is configured via Expo config:

```json
"extra": {
  "PLANT_ID_API_KEY": "YOUR_API_KEY"
}
```

> ⚠️ For production, API keys should be moved to a secure backend.

---

## 🏷️ Versioning

* **Current stable version:** `floracare-mvp-v1`
* Tagged using Git for clean version control and rollback safety.

---

## 🧠 Design Philosophy

FloraCare focuses on:

* **Clarity over complexity** – simple care instructions for beginners
* **Fast MVP iteration** – real device testing from day one
* **Extensibility** – easy to replace APIs or add new intelligence layers

---

## 🔮 Future Enhancements

* 💾 Save identified plants to "My Plants"
* ⏰ Watering & care reminders
* 🦠 Disease detection
* 🤖 AI-generated personalized care plans
* 📦 APK / Play Store release

---

## 👤 Author

**Shravankumar P**
AI / ML Engineer | Product Builder

---

## 📜 License

This project is currently for learning, experimentation, and portfolio use. Licensing can be added as the project evolves.

---

🌱 *FloraCare – helping plants (and people) thrive.*
