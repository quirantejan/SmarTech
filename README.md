# SmarTech

SmarTech is a native Android accessibility assistant designed to support visually impaired users through voice-guided navigation, emergency support, task planning, and camera-based object recognition.

## Features

- Email/password registration and login
- Emergency-contact management for up to five contacts
- Voice-command navigation with spoken feedback
- Daily planner with reminders, priorities, and repeat schedules
- Emergency SMS and location sharing
- Help workflow for sending spoken messages to selected contacts
- Camera-based object recognition with voice feedback
- Color-coded assistant modes and Lottie animations

## Tech Stack

- **Language:** Java
- **Platform:** Android
- **UI:** XML, Material Components, ConstraintLayout, CardView, Lottie
- **Authentication & Data:** Firebase Authentication, Cloud Firestore, Firebase Realtime Database
- **Voice Interaction:** Android SpeechRecognizer, Text-to-Speech API
- **Object Recognition:** Google ML Kit Object Detection, CameraX
- **Device Services:** Android Location APIs, Sensor APIs
- **Testing:** JUnit, AndroidX Test, Espresso
- **Build & Version Control:** Gradle (Kotlin DSL), Git, GitHub

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/quirantejan/SmarTech.git
   cd SmarTech
   ```

2. Open the project in Android Studio.

3. Add a Firebase configuration file named `google-services.json` to the `app/` directory.

4. Enable Firebase Authentication, Cloud Firestore, and Firebase Realtime Database in your Firebase project.

5. Sync Gradle and run the app on an Android device or emulator.

## Project Context

SmarTech was developed as an academic native Android application project.

## Contributors

- **Chelsea Rose Pimentel** — User registration and authentication, emergency-contact management, voice-assistant navigation, and color-coded assistant modes
- **Pia Lorraine Tantay** — Emergency assistance, help-command workflow, SMS messaging, and location-sharing features
- **John Clement Quirante** — Camera-based object recognition using CameraX and Google ML Kit
- **James Cheong** — Daily planner, voice reminders, task priorities, and repeat scheduling
- **Mark Calderon Gabieta** — Audio notifications, vibration feedback, and planner-notification support
