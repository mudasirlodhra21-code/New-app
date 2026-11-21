# YouTube Mobile Player (starter Android project)

This starter app opens the official YouTube mobile website inside Android WebView.
It supports browsing/searching YouTube and standard web playback where YouTube permits
playback in WebView. Full-screen web video is handled by the app.

## Important limitation
This app does NOT mirror the phone screen to a TV and does NOT create HDMI video output.
Your Infinix Hot 30 Play (X6835) has no confirmed USB-C DisplayPort/HDMI video-out support.
A USB cable alone cannot send video to a normal TV unless the phone hardware supports it.

## Build APK using GitHub Actions
1. Create a new GitHub repository.
2. Upload all files and folders from this project to the repository root.
3. Open the repository's **Actions** tab.
4. Run **Build Android APK** (or push to the `main` branch).
5. Open the completed workflow run and download the artifact named
   `YouTube-Mobile-Player-APK`.
6. Extract the ZIP artifact and install `app-debug.apk` on your Android phone.
   Allow installation from that source if Android asks.

## Build locally
Requires Android SDK (API 35), JDK 17, and Gradle 8.7 or newer:
`gradle assembleDebug`

Package: `com.example.youtubemobileplayer`
