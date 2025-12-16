# 📱 Guia Pocket – Vale do Sol

## 📋 Project Description
**Guia Pocket – Vale do Sol** is an Android mobile application developed to promote small local businesses and services from the Vale do Sol neighborhood in Araraquara-SP.

The application connects residents to nearby establishments through a clean, intuitive, and efficient interface.  
This second version of the project focuses on **performance optimization**, **local data persistence**, and **user-driven service registration**, based on community feedback.

---

## 🎯 Features
- 📋 List of services using **RecyclerView**
- 🔍 Real-time search filter by service name
- ➕ Register new services directly in the app
- 🖼️ Select images from the device gallery
- 📞 Direct phone call
- 🌐 Access websites and social media
- 🗺️ Open location in Google Maps
- 📤 Share service information
- 🌙 Automatic light/dark mode
- 🌎 Portuguese and English support

---

## 🏪 Initial Services Included
1. **Abelhinha Uniformes** – Seamstress  
2. **Supermercado Real 1** – Market  
3. **Moto Center** – Motorcycle Workshop  
4. **BM Barbearia & Tattoo** – Barbershop  
5. **Panificadora Vale do Sol** – Bakery  
6. **Fabinho Lanches** – Snack Bar  

> New services can be dynamically added by users through the application.

---

## 📸 Screenshots

### Light Mode – Portuguese / English
<p align="center">
  <img src="screenshots/Captura de tela 2025-11-03 234034.png" width="30%" alt="Main Screen - Light Mode"/>
  <img src="screenshots/Captura de tela 2025-11-03 234046.png" width="30%" alt="Details Screen - Light Mode"/>
</p>

### Dark Mode – English
<p align="center">
  <img src="screenshots/Captura de tela 2025-11-03 234319.png" width="30%" alt="Main Screen - Dark Mode"/>
  <img src="screenshots/Captura de tela 2025-11-03 234329.png" width="30%" alt="Details Screen - Dark Mode"/>
</p>

---

## 🎥 Demo Videos

### 🔹 Short Demo (30 seconds)
This short video presents the general functionality of the application:
- Navigation between screens
- Action buttons (call, website, maps, share)
- Light and dark mode
- Language switching

👉  
https://github.com/user-attachments/assets/b3b9119f-fc9c-4d32-a63a-d23fd8b9b6ef

---

### 🔹 Full Explanation Video (6 minutes)
This video provides a detailed explanation of the main technical aspects of the project, including:
- RecyclerView and Adapter implementation
- Explicit and implicit Intents
- Activity Result API
- Real-time search filter
- Room Database and local persistence
- Architectural and design decisions

👉 **Google Drive link:**  
https://drive.google.com/file/d/1BnrQIWPi7Wbj0ypuifZ_uAL2GS0XCdkg/view?usp=sharing

> ℹ️ The full explanation video is hosted on Google Drive to avoid GitHub repository size limitations and to ensure easy access without affecting repository performance.

---

## 🛠️ Technologies Used
- **Language:** Kotlin  
- **IDE:** Android Studio  
- **SDK:** Android 14 (API 34)  
- **UI:** ConstraintLayout + ViewBinding  
- **Lists:** RecyclerView  
- **Database:** Room (SQLite abstraction)  
- **Asynchronous:** Kotlin Coroutines & Flow  
- **Image Loading:** Glide  
- **Navigation:** Intents & Activity Result API  

---

## ⚙️ Technical Features
- ✅ RecyclerView with custom Adapter
- ✅ Explicit Intents (screen navigation)
- ✅ Implicit Intents (call, maps, browser, share)
- ✅ Activity Result API for image selection
- ✅ Local persistence with Room
- ✅ Image storage via URI (String)
- ✅ Real-time filtering
- ✅ Repository pattern for data access
- ✅ ViewBinding in all screens
- ✅ Internationalization (pt-BR / en)
- ✅ Automatic Day/Night mode

---

## 📄 Project Structure
