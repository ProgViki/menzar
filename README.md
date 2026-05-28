# ChatApp Mobile Application

A modern real-time mobile chatting application built with Kotlin and Android Studio. The application delivers seamless one-to-one and group messaging, media sharing, notifications, authentication, and modern user experiences using the latest Android development technologies.

---

# Features

- Secure Authentication
- Real-Time Messaging
- One-to-One Chats
- Group Chats
- Image and Video Sharing
- Voice Notes
- Push Notifications
- Online and Offline Presence
- Typing Indicators
- Message Reactions
- Dark and Light Mode
- Chat Search
- Offline Caching
- Cloud Synchronization
- Responsive UI Design

---

# Tech Stack

## Language
- Kotlin

## IDE
- Android Studio

## Architecture
- MVVM Architecture
- Clean Architecture
- Repository Pattern

---

# Modern Libraries and Technologies

## UI and Design
- Jetpack Compose
- Material Design 3
- Lottie Animations

## Dependency Injection
- Hilt

## Networking
- Retrofit
- OkHttp
- Gson
- Kotlinx Serialization

## Firebase Services
- Firebase Authentication
- Firebase Firestore
- Firebase Cloud Messaging
- Firebase Storage

## Local Storage
- Room Database
- DataStore Preferences

## Asynchronous Programming
- Kotlin Coroutines
- Flow
- StateFlow

## Image Loading
- Coil
- Glide

## Navigation
- Jetpack Navigation Component

## Security
- Android Keystore
- Encrypted SharedPreferences

## Testing
- JUnit
- Mockito
- Espresso

## CI/CD
- GitHub Actions

---

# Project Structure

```bash
app/
│
├── data/
│   ├── local/
│   ├── remote/
│   ├── repository/
│
├── domain/
│   ├── model/
│   ├── usecase/
│
├── presentation/
│   ├── auth/
│   ├── chat/
│   ├── profile/
│   ├── settings/
│
├── di/
├── utils/
└── MainActivity.kt
