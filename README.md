# Hello World - React Native App

A simple Hello World app built with React Native 0.76.

## How to Build the APK

### Option 1: Expo EAS (Recommended — No local setup needed)

1. Install EAS CLI:
   ```
   npm install -g eas-cli
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Login to Expo:
   ```
   eas login
   ```

4. Build:
   ```
   eas build -p android --profile preview
   ```

5. Download the APK from the Expo dashboard link.

---

### Option 2: Local Build

Requirements: Node 18+, JDK 17, Android Studio + SDK

```bash
npm install
cd android
./gradlew assembleDebug
```

APK output: `android/app/build/outputs/apk/debug/app-debug.apk`

---

### Option 3: Online — Appetize.io / Buildozer / CodeMagic

Upload this project folder to any React Native CI/CD service.

## App Details
- React Native: 0.76.5
- Min Android SDK: 24 (Android 7.0+)
- Package: com.helloworld
# HelloWorld
