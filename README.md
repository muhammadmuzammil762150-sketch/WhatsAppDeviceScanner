# WhatsApp Device Scanner

Android Studio project using Kotlin, Jetpack Compose, CameraX, and Google ML Kit Barcode Scanning.

## Features
- Camera-based QR scanning
- Displays scanned text or URL
- Opens HTTP/HTTPS links only after tapping Open Link
- In-memory scan history (clears when app process is removed)
- Official WhatsApp Web shortcut
- Camera permission requested at runtime

## Build APK
1. Install Android Studio (current stable) with Android SDK Platform 35 and JDK 17.
2. Open this folder in Android Studio.
3. Let Gradle sync and download dependencies.
4. Use **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. APK output is usually `app/build/outputs/apk/debug/app-debug.apk`.

This source project has not been compiled in this environment because Android SDK and Gradle are not installed here. Verify the build in Android Studio before installing.
