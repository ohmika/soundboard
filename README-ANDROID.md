# OhMika Soundboard for Android

This Android app packages the existing Dutch soundboard as a local WebView app.
The complete original `index.html` is included in `app/src/main/assets/`, so
the sounds, thumbnails, search, sorting, favorites, volume, playback modes and
stop control work without an internet connection.

## Build

Requires JDK 17, Android SDK Platform 35, and Gradle 8.9.

```sh
gradle --no-daemon assembleDebug
```

APK output: `app/build/outputs/apk/debug/app-debug.apk`.

GitHub Actions also builds the APK and uploads it as the
`OhMika-Soundboard-debug` workflow artifact.
