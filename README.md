<div align="center">

# 🛡️ Sentriq

### **A Real-Time Personal Safety Platform Built with Flutter**

**Stay connected. Stay protected. Stay in control.**

Sentriq is a cross-platform personal safety application that empowers users to share their live location with trusted guardians, create intelligent geofenced safety zones, and instantly notify emergency contacts through one-tap SOS alerts. Powered by Firebase and Google Maps, Sentriq delivers secure, real-time communication designed to protect the people who matter most.

---

![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-Backend-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Google Maps](https://img.shields.io/badge/Google%20Maps-Integrated-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-success?style=for-the-badge)

</div>

---

# 🌍 Overview

Every second matters during an emergency.

Sentriq transforms your smartphone into a smart personal safety companion capable of continuously sharing your location, monitoring predefined safety zones, and instantly notifying trusted guardians whenever assistance is needed.

Whether you're traveling alone, commuting late at night, or ensuring the safety of loved ones, Sentriq provides peace of mind through reliable real-time technology.

---

# ✨ Features

## 📍 Live Location Sharing

Share your real-time location securely with trusted guardians using Firebase Realtime Database.

---

## 🛡 Guardian Network

Build your trusted safety circle by sending and accepting guardian requests.

---

## 🗺 Real-Time Google Maps

Track yourself and your guardians using an interactive Google Maps interface.

---

## 🚧 Geofenced Safety Zones

Create custom safe zones and receive automatic alerts whenever someone enters or exits those boundaries.

---

## 🆘 One-Tap SOS

Immediately notify guardians during emergencies with your latest live location.

---

## 🔐 Secure Authentication

- Email & Password Authentication
- Google Sign-In
- Firebase Authentication

---

## ☁ Real-Time Cloud Synchronization

All user locations, friends, alerts, and zones synchronize instantly using Firebase.

---

## 🔄 Background Location Tracking

Sentriq continues updating your live location even when the application is running in the background.

---

# 🏗 Technology Stack

## Frontend

- Flutter
- Dart
- Material Design

---

## Backend

- Firebase Authentication
- Firebase Realtime Database

---

## Maps & Location

- Google Maps
- Geolocator
- Geocoding
- Google Play Services

---

## Development Tools

- Flutter SDK
- Android Studio
- Xcode
- CocoaPods
- Git
- GitHub

---

# 📂 Project Structure

```
Sentriq/
│
├── android/
├── ios/
├── lib/
├── assets/
├── web/
├── linux/
├── windows/
├── macos/
├── test/
│
├── pubspec.yaml
├── pubspec.lock
├── README.md
└── .gitignore
```

---

# 💻 System Requirements

## macOS

- macOS Sonoma or later
- Xcode 15+
- Flutter SDK
- CocoaPods
- Git

---

## Windows

- Windows 10/11
- Android Studio
- Flutter SDK
- Git

---

# 🚀 Installation Guide

This guide walks you through everything required to run Sentriq.

---

# Step 1 — Install Git

### macOS

```bash
brew install git
```

Verify

```bash
git --version
```

---

### Windows

Download Git

https://git-scm.com/downloads

Verify

```bash
git --version
```

---

# Step 2 — Install Flutter

Download Flutter SDK

https://docs.flutter.dev/get-started/install

Extract Flutter.

Add Flutter to PATH.

Verify

```bash
flutter --version
```

---

# Step 3 — Install Android Studio

Download

https://developer.android.com/studio

Install

- Android SDK
- Android SDK Platform
- Android Emulator

Verify

```bash
flutter doctor
```

---

# Step 4 — Install Xcode (macOS)

Download Xcode from the App Store.

After installation

```bash
sudo xcode-select --switch /Applications/Xcode.app
```

Run

```bash
sudo xcodebuild -runFirstLaunch
```

Accept License

```bash
sudo xcodebuild -license
```

---

# Step 5 — Install CocoaPods

Install

```bash
brew install cocoapods
```

Verify

```bash
pod --version
```

Update Repository

```bash
pod repo update
```

---

# Step 6 — Verify Flutter Installation

Run

```bash
flutter doctor
```

Every section should display a green check mark before continuing.

---

# 📥 Clone the Repository

Clone Sentriq

```bash
git clone https://github.com/LakshmanDev12/Sentriq-IoS.git
```

Go inside the project

```bash
cd Sentriq-IoS
```

---

# 📦 Install Flutter Packages

```bash
flutter pub get
```

---

# 🍎 Install iOS Dependencies

Move into iOS folder

```bash
cd ios
```

Install CocoaPods

```bash
pod install
```

Return

```bash
cd ..
```

---

# 🔥 Firebase Configuration

This project requires Firebase.

The following files should already exist inside the project.

Android

```
android/app/google-services.json
```

iOS

```
ios/Runner/GoogleService-Info.plist
```

If these files are missing, contact the repository owner.

---

# 📱 Running on an iPhone

---

## Step 1

Connect your iPhone using a USB cable.

Tap

```
Trust This Computer
```

---

## Step 2

Enable Developer Mode.

Open

```
Settings

↓

Privacy & Security

↓

Developer Mode

↓

Enable
```

Restart the device.

Confirm

```
Enable Developer Mode
```

---

## Step 3

Open Xcode.

Navigate to

```
Xcode

↓

Settings

↓

Accounts
```

Sign in with your Apple ID.

A free Apple ID works for development.

---

## Step 4

Open

```bash
open ios/Runner.xcworkspace
```

---

## Step 5

Inside Xcode

Select

```
Runner
```

Open

```
Signing & Capabilities
```

Choose your Apple ID as Team.

If signing fails

Change Bundle Identifier

Example

```
com.yourname.sentriq
```

---

## Step 6

Select your iPhone

instead of

```
iPhone Simulator
```

---

## Step 7

Press

```
▶ Run
```

Wait for the first build.

---

## Step 8

If the application cannot open

Go to

```
Settings

↓

General

↓

VPN & Device Management

↓

Developer App

↓

Trust
```

Return to the Home Screen.

Launch Sentriq.

---

# 📱 Running on iOS Simulator

Open Simulator

```bash
open -a Simulator
```

Run

```bash
flutter run
```

or

```bash
flutter run -d ios
```

---

# 🤖 Running on Android

Connect an Android phone

Enable

```
Developer Options

↓

USB Debugging
```

Verify

```bash
flutter devices
```

Run

```bash
flutter run
```

---

# 📦 Build Release Versions

Android APK

```bash
flutter build apk --release
```

Android App Bundle

```bash
flutter build appbundle
```

iOS Release

```bash
flutter build ios --release
```

---

# 🔄 Updating the Project

Pull latest changes

```bash
git pull origin main
```

Install packages

```bash
flutter pub get
```

Update Pods

```bash
cd ios

pod install

cd ..
```

---

# 🛠 Common Fixes

## Flutter Clean

```bash
flutter clean
flutter pub get
```

---

## Reinstall CocoaPods

```bash
cd ios

rm -rf Pods

rm Podfile.lock

pod install

cd ..
```

---

## Update CocoaPods

```bash
brew upgrade cocoapods

pod repo update
```

---

## Check Flutter Environment

```bash
flutter doctor -v
```

---

# 🤝 Git Workflow

Clone

```bash
git clone https://github.com/LakshmanDev12/Sentriq-IoS.git
```

Check Status

```bash
git status
```

Create New Branch

```bash
git checkout -b feature/new-feature
```

Stage Changes

```bash
git add .
```

Commit

```bash
git commit -m "Describe your changes"
```

Push

```bash
git push origin feature/new-feature
```

Update Main

```bash
git checkout main

git pull origin main
```

---

# 📋 Useful Flutter Commands

```
flutter doctor

flutter pub get

flutter clean

flutter run

flutter build apk

flutter build ios

flutter build appbundle

flutter devices
```

---

# 🔐 Security

This repository is private.

The Firebase configuration files included in this repository are intended only for authorized collaborators.

Do not redistribute project files, Firebase credentials, or application assets without explicit permission from the repository owner.

---

# 👨‍💻 Author

**Lakshman Dev V K**

Flutter Developer • Android Developer • Firebase Developer

Passionate about building secure, scalable, and impactful applications that solve real-world problems.

---

<div align="center">

## 🛡️ Sentriq

### **Because safety should always travel with you.**

Built with ❤️ using Flutter & Firebase.

</div>
