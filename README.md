# Android Hello World App

A simple Android application that displays "Hello World" on the screen.

## Project Structure

This is a standard Android project with the following key components:

- **MainActivity.kt**: The main activity that displays the Hello World message
- **activity_main.xml**: Layout file containing a TextView with "Hello World" text
- **AndroidManifest.xml**: App configuration and permissions
- **build.gradle**: Project and app-level build configurations
- **Resources**: Icons, strings, colors, and themes

## Features

- Displays "Hello World" text centered on the screen
- Uses Material Design components
- Compatible with Android API 26+ (Android 8.0 Oreo and above)
- Targets Android 14 (API 34) for latest features and security
- Written in Kotlin

## Building the App

To build this Android app, you need:

1. Android Studio or Android SDK
2. Gradle 6.0+ (for modern Android development)
3. Java 8 or higher

### Build Commands

```bash
# Build the app
./gradlew build

# Build debug APK
./gradlew assembleDebug

# Build release APK
./gradlew assembleRelease
```

## Installation

1. Open the project in Android Studio
2. Connect an Android device or start an emulator
3. Click "Run" or use `./gradlew installDebug`

## App Details

- **Package Name**: com.example.helloworld
- **Min SDK**: 26 (Android 8.0)
- **Target SDK**: 34 (Android 14)
- **Compile SDK**: 34 (Android 14)
- **Language**: Kotlin
- **Android Gradle Plugin**: 8.1.2
- **Kotlin Version**: 1.9.10
