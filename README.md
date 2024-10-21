# 📱 FitnessApp: End-Sem Lab Project 💪

Welcome to **FitnessApp**, an Android application that helps users track their fitness activities! This app allows users to log workout details, including exercises, sets, reps, and provides a seamless way to monitor progress. The project implements key Android components such as **SQLite** and **Firebase** to ensure reliable data storage and user authentication.

## 🚀 Features

- **User Authentication** 🔑: Sign-up and login functionality with **Firebase**.
- **Exercise Tracker** 🏋️‍♂️: Add exercises, track sets, reps, and weights.
- **Push-up Activity** 🤸‍♀️: Includes a timer, calorie calculation, and tracking.
- **SQLite Integration** 🗄️: Stores workout details in a local database.
- **Data Visualization** 📊: Real-time visualization of exercise data.
- **Personal Dashboard** 🏅: Displays user name, roll number, and profile picture.

## 🛠️ Tech Stack

- **Android Studio**: IDE for developing Android applications.
- **Java**: Primary language for Android development.
- **SQLite**: Used for local storage of fitness data.
- **Firebase**: For secure user authentication and cloud storage.

## 📂 Project Structure

```bash
FitnessApp/
│
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/com/example/endsem/
│   │       │   ├── MainActivity.java   # Main app logic
│   │       │   ├── PushUpActivity.java # Handles push-up tracking
│   │       │   ├── DatabaseHelper.java # SQLite database helper class
│   │       │   └── UserAuth.java       # Firebase authentication logic
│   │       └── res/
│   │           └── layout/
│   │               ├── activity_main.xml # UI for main screen
│   │               ├── activity_pushup.xml # UI for push-up tracking
│   └── AndroidManifest.xml
│
└── README.md  # Project documentation
