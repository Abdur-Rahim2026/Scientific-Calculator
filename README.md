# Scientific Calculator — Android project

This is an Android Studio project wrapping the supplied `calculator.html` in a native Android WebView.
The calculator HTML is bundled in `app/src/main/assets`, so the app does not need an internet connection.

## Build the APK

1. Install Android Studio on Windows, macOS, or Linux.
2. Open this project folder (`ScientificCalculatorAndroid`) in Android Studio.
3. Allow Gradle sync and install the Android SDK Platform 35 if Android Studio requests it.
4. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. When the build finishes, click **locate** in the notification.

The debug APK is normally created at:
`app/build/outputs/apk/debug/app-debug.apk`

## Install on Android

Transfer the APK to your phone, open it, and allow installation from that source if Android asks.
For sharing publicly, create a signed release APK from **Build > Generate Signed Bundle / APK**.

Package: `com.realmax.scientificcalculator`
App label: `Scientific Calculator`
Minimum Android: Android 6.0 (API 23)

Note: This project package is prepared, but an APK has not been compiled or device-tested in this environment.
