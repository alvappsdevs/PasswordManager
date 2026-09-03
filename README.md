# 🔐 Password Manager

> 🔐 **Password Manager** is a modern, private-by-design offline password manager for Android. Built with Kotlin, Jetpack Compose, Room, and Hilt, it keeps your credentials encrypted directly on your device. Zero cloud sync, zero tracking, zero internet permissions—just ultra-secure, fast local credential management with a sleek Material 3 interface.

---

## ✨ Features

* **100% Offline & Private:** Zero internet permissions required. Your sensitive data never leaves your device.
* **Secure Local Storage:** Encrypted local persistence powered by Room.
* **Modern UI/UX:** Clean, intuitive interface designed with Jetpack Compose and Material 3 guidelines.
* **Password Generator:** Built-in tool to create custom, ultra-strong passwords instantly.
* **Fast Search:** Effortlessly find and manage saved credentials.

---

## 🛠 Tech Stack & Architecture

This application follows **Android Design & Architecture Guidelines** with a focus on **Clean Architecture**, multi-module friendliness, and Unidirectional Data Flow (UDF).

* **Language:** [Kotlin](https://kotlinlang.org/)
* **UI:** [Jetpack Compose](https://developer.android.com/jetpack/compose) + Material Design 3
* **Local Database:** [Room](https://developer.android.com/training/data-storage/room)
* **Dependency Injection:** [Hilt](https://developer.android.com/training/dependency-injection/hilt-android)
* **Asynchronous Execution:** Kotlin Coroutines & Flow
* **Architecture Pattern:** Clean Architecture (UI, Domain, Data layers) + MVVM

---

## 🚀 Getting Started

### Prerequisites

* Android Studio Ladybug (or newer)
* JDK 17 or higher
* Min SDK: 24 (Android 7.0)

### Building the project

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/PasswordManager.git](https://github.com/YOUR_USERNAME/PasswordManager.git)