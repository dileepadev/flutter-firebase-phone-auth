# Flutter Firebase Phone Auth

![GitHub repo size](https://img.shields.io/github/repo-size/dileepadev/flutter-firebase-phone-auth?color=red&label=repository%20size)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/dileepadev/flutter-firebase-phone-auth?color=red)
![GitHub language count](https://img.shields.io/github/languages/count/dileepadev/flutter-firebase-phone-auth)
![GitHub top language](https://img.shields.io/github/languages/top/dileepadev/flutter-firebase-phone-auth)
![GitHub](https://img.shields.io/github/license/dileepadev/flutter-firebase-phone-auth?color=yellow)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/dileepadev/flutter-firebase-phone-auth?color=brightgreen&label=commits)

## ✨ About

The **Flutter Firebase Phone Auth** application has been developed as an authentication method for authenticating the user's mobile phone. Users can verify the phone with a validation process enhanced with Firebase Authentication. This sample release does not include the complete requirements and interface. **This project has been developed as an open source for educational purposes.**

![Preview Image](https://dileepadev.github.io/images/flutter-firebase-phone-auth/preview.png)

## 🎞️ Demo Videos

Click the link or image below to view the demo video on YouTube.

🔗 <https://youtu.be/205O8dKtwOA>

[![Watch the demo video](https://img.youtube.com/vi/205O8dKtwOA/0.jpg)](https://youtu.be/205O8dKtwOA)

## 📦 Release Details

Release Version - 1.0.0  
Initial release date - July 9, 2021

> [!NOTE]
> This repository is a clean re-upload to my new GitHub account. No new features or functionality have been added. Minor compatibility fixes may have been applied to ensure the project runs correctly in the current environment. Please note that the original commit history from the previous account is not preserved. This update is primarily for migration purposes.
>
> **Initial release date:** July 9, 2021  
> **Migration date:** December 29, 2025

## 💡 Deployment

Deployment is not currently in use

## 💻 Built with

- Flutter
- Dart
- Android Studio
- Firebase

## 📌 Prerequisites

Before you get started, follow these requirements

### Original (Legacy) Versions

- Firebase project
- Dart SDK >=2.7.0 <3.0.0
- Flutter SDK >=2.0.0
- Android Gradle Plugin Version = 7.0.4
- Gradle Version = 7.0.2

### Upgraded Versions

| Component                       | Version Used |
| ------------------------------- | ------------ |
| **Flutter SDK**                 | 2.10.0       |
| **Dart SDK**                    | 2.16.0       |
| **Java (JDK)**                  | 11.0.x       |
| **Gradle Wrapper**              | 7.6.1        |
| **Android Gradle Plugin (AGP)** | 7.0.4        |

## 🍃 How to Setup

- Download or clone the repository
- Move the project to the selected directory
- Open it with a code editor (Android Studio, Visual Studio Code)
- Add firebase config file
  - iOS - GoogleService-Info.plist
  - Android - google-services.json
  - Web - Follow the instructions
- Run flutter clean and pub get commands
- Do not update / upgrade gradle and other versions until the app is up and running with built versions

## 🚀 Flutter Android Setup

### Prerequisites Installation

#### 1. Flutter SDK

Download and extract the Flutter SDK for Windows to a location like `C:\flutter\flutter_windows_2.10.0-stable`, then add it to your PATH:

```powershell
$env:PATH = "C:\flutter\flutter_windows_2.10.0-stable\flutter\bin;" + $env:PATH
flutter --version
```

#### 2. Java JDK 11

Install **Java JDK 11** (not just JRE) and set the environment variables:

```powershell
$env:JAVA_HOME = "C:\Program Files\Java\jdk-11.0.x"
$env:PATH = "$env:JAVA_HOME\bin;" + $env:PATH
java --version
```

#### 3. Verify Your Environment

Run this to check that everything is set up correctly:

```bash
flutter doctor -v
flutter devices
```

Accept any Android licenses if prompted.

### Project Configuration

#### Update Gradle

Edit `android/gradle/wrapper/gradle-wrapper.properties` and update:

```properties
distributionUrl=https\://services.gradle.org/distributions/gradle-7.6.1-all.zip
```

Update the Gradle wrapper by running:

```powershell
cd android
./gradlew wrapper --gradle-version 7.6.1
cd ..
```

#### Update Kotlin (if needed)

If you encounter Kotlin errors, ensure `android/build.gradle` has:

```gradle
ext.kotlin_version = '1.6.10'
```

### Run Your App

```bash
flutter clean
flutter pub get
flutter run
```

To target a specific device: `flutter run -d <device-id>`

### Troubleshooting

**Gradle/Java Incompatibility Issues:

If you see errors about **Gradle↔Java incompatibility** (like “Unsupported class file major version…”), then:

- Ensure **Gradle wrapper is updated to 7.6.1**
- Ensure `JAVA_HOME` points to Java 11
- If needed, add this to `android/gradle.properties`:

```properties
org.gradle.java.home=C:\\Program Files\\Java\\jdk-11.0.x
```

This forces Gradle to use the correct JDK.

### 8) Run on a Specific Device

List devices:

```bash
flutter devices
```

Run on a chosen device:

```bash
flutter run -d emulator-5554
```

Replace `emulator-5554` with your device ID.

## 📸 Icons and Images

- Icons8 - <https://icons8.com>
- Freepik - <https://www.freepik.com>

## 💎 Dependencies

- Flutter - <https://flutter.dev>
- Firebase Core - <https://pub.dev/packages/firebase_core>
- Firebase Auth - <https://pub.dev/packages/firebase_auth>

## ❤️ Thanks

Thanks to everyone who supported

## 👨‍💻 Developed By

Dileepa Bandara  
[@dileepadev](https://github.com/dileepadev)  
<https://dileepa.dev>

> [!NOTE]
> This repository may contain references to my former GitHub username (`dileepabandara`) and domain (`dileepabandara.dev`), which I no longer use. These identifiers may now belong to other parties. All current development and maintenance are conducted under my new GitHub account [dileepadev](https://github.com/dileepadev) and domain [dileepa.dev](https://dileepa.dev).

## 💬 Contact

If you want to contact me, leave a message via email.

- Email - <contact@dileepa.dev>

## 📜 License

This project is licensed under the MIT License.  
See the license file for more details [LICENSE.md](./LICENSE)
