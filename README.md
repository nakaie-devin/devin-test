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
- Compatible with Android API 21+ (Android 5.0 Lollipop and above)
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
- **Min SDK**: 21 (Android 5.0)
- **Target SDK**: 28 (Android 9.0)
- **Language**: Kotlin
