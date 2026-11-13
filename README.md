# HabitPulse — Android APK Builder & Offline App

## Option 1: Instant Phone Install (Zero Compiling Required)
1. Download `HabitPulse_Mobile_App.html` directly to your phone.
2. Open it in **Chrome** (Android) or **Safari** (iOS).
3. Tap the browser menu (`⋮`) -> **"Add to Home screen"**.
4. You now have a full-screen, offline-capable HabitPulse app on your home screen with automatic local storage!

---

## Option 2: Compile a Native `.apk` in the Cloud (No PC or Android Studio Needed!)
This ZIP already includes an automated **GitHub Actions APK Builder** (`.github/workflows/build-apk.yml`):
1. Create a free repository on [github.com](https://github.com) and upload the contents of this ZIP file.
2. Click the **Actions** tab in your GitHub repository and run **Build Android APK**.
3. In ~90 seconds, download **`HabitPulse-Android-APK` (`app-debug.apk`)** from the Artifacts section and install it on your Android phone!

---

## Option 3: Compile Locally in Android Studio
1. Extract this ZIP folder and open it in **Android Studio**.
2. Wait for Gradle Sync to finish, then click **Build -> Build Bundle(s) / APK(s) -> Build APK(s)**.
3. Your installable `.apk` will be generated at `app/build/outputs/apk/debug/app-debug.apk`.
