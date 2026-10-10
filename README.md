# Tamil Panchangam — GitHub APK Build

1. Create a GitHub repository and upload all files from this folder.
2. Open **Actions** and enable workflows if prompted.
3. Run **Build Android APK** from Actions, or push to `main`.
4. Download the `tamil-panchangam-debug-apk` artifact from the completed run.
5. Unzip the artifact and install `app-debug.apk` on your Android phone.

This is a debug/testing APK. A Play Store release requires a separately signed release build.

The app tries to load Panchangam data from the public Shastra Panchangam API. API availability and response fields may change. When data is unavailable, it says so instead of inventing values. Verified planetary positions and horoscope predictions are not included.
