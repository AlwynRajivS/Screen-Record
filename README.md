# NanJoni Screen Recorder (Android)

Get the single APK (no Android Studio needed):
1. Create a new GitHub repo and upload this whole folder.
2. Open the repo -> Actions -> "Build APK" (runs on push) -> download artifact `NanJoni-ScreenRecorder-APK` -> app-debug.apk
Or in Android Studio: Build > Build APK(s).

Touch display: enable Developer options > "Show taps", OR once run:
adb shell pm grant com.nanjoni.screenrecorder android.permission.WRITE_SECURE_SETTINGS
