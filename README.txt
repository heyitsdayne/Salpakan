Build the APK:
1. Install Android Studio and open this Salpakan folder (File > Open).
2. Wait for Gradle sync to finish.
3. Build > Build APK(s). Find it in app/build/outputs/apk/debug/app-debug.apk
4. Copy to your phone and tap it (allow "install unknown apps").
Or plug in the phone with USB debugging and press Run.

Build in the cloud (no Android Studio):
1. Create a GitHub repo and push this folder to its main branch.
2. Open the Actions tab. "Build APK" runs automatically (or press Run workflow).
3. When it finishes, open the run and download Salpakan-debug-apk from Artifacts.
4. Unzip it and install app-debug.apk on your phone.
