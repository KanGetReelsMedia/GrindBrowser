# Grind Browser Mobile

This is your SAME Grind Browser, but for Android/iPhone.

## To build Android APK:

1. Open PowerShell in this folder:
   npm.cmd install
   npm.cmd exec cap add android

2. Then:
   npm.cmd run android

This opens Android Studio. Click Run -> builds APK onto phone or emulator.

## For quick test without Android Studio:
Your src folder is already a PWA - you can just open src/index.html on your phone browser, Add to Home Screen.

## iOS:
Need a Mac: npx cap add ios, then npx cap open ios
