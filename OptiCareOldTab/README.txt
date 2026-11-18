1. Install Android Studio (free) on your PC.
2. File > Open > choose this OptiCareOldTab folder. Wait for "Gradle sync" to finish (needs internet).
3. Menu: Build > Build Bundle(s) / APK(s) > Build APK(s).
4. Click "locate" in the popup: app-debug.apk is your app.
5. Copy it to the tablet (USB/WhatsApp), allow "Unknown sources", tap the file to install.

PARSING ERROR FIX (Galaxy Note 10.1 GT-N8013 runs Android 4.1/4.2/4.3/4.4):
minSdk is now 16 so the APK installs on Android 4.1+. (It was 19 = Android 4.4 only.)
Rebuild the APK after this change. Do NOT use an "app-release-unsigned.apk" - use app-debug.apk.
