# Hello World Android App

A simple "Hello World" Android application that builds automatically using GitHub Actions.

## What This App Does

Displays "Hello World!" in the center of the screen with a simple, clean interface.

## How to Get Your APK

### Step 1: Upload to GitHub
1. Create a new repository on GitHub (make it public or private)
2. Upload all these files to your repository
3. Make sure the files are in the main/master branch

### Step 2: Let GitHub Actions Build
1. Go to the "Actions" tab in your GitHub repository
2. You should see a workflow running automatically
3. Wait for it to complete (usually takes 2-5 minutes)

### Step 3: Download Your APK
1. Click on the completed workflow run
2. Scroll down to "Artifacts"
3. Download "app-release"
4. Extract the ZIP file to get your APK

### Step 4: Install on Android
1. Transfer the APK to your Android device
2. Enable "Install from Unknown Sources" in your device settings
3. Open the APK file and install

## Manual Build (Optional)

If you want to build locally instead:

```bash
./gradlew assembleRelease
```

The APK will be in: `app/build/outputs/apk/release/`

## Requirements

- Android 5.0 (API 21) or higher
- Built with Android SDK 34

## Notes

- The APK will be unsigned, so you'll need to allow installation from unknown sources
- For production apps, you'd want to sign the APK with a keystore
