# 2048 PRO MAX

A premium 2048 puzzle game — built as a single-file web app wrapped in Capacitor for Android.

## Project structure

```
index.html                  ← Source game file (edit this)
www/index.html              ← Capacitor web root (auto-synced from index.html)
android/                    ← Android project (Capacitor-generated)
capacitor.config.json       ← Capacitor configuration
```

## Development workflow

1. Edit `index.html` (the root file)
2. Run `npx cap copy android` to sync changes to the Android app
3. Open `android/` in Android Studio and run on device

## Package info

- **App ID**: com.poweressien.promax2048
- **Min Android**: API 24 (Android 7.0)
- **Target Android**: API 36
- **Capacitor**: 8.x
