# My Meeting — Ready Meeting MVP

This version integrates Jitsi Meet for actual video/audio meetings.

## What is already set up
- My Meeting UI
- Create/join meeting flow
- Real Jitsi video/audio meeting integration
- Microphone/camera controls through the video service
- Android/iOS configuration notes
- Firebase service layer remains available for a future account system

## Build requirements
A computer with Flutter and Android/iOS build tools is required to compile the APK/IPA.

Run:
flutter pub get
flutter build apk --release

The Jitsi SDK currently supports Android and iOS; Android requires API 24+ and iOS 15.1+.
