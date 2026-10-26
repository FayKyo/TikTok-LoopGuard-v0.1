# Building the APK

## Option A – Android Studio
1. File > Open this folder, wait for Gradle sync.
2. Build > Build Bundle(s) / APK(s) > Build APK(s).
3. APK: app/build/outputs/apk/debug/app-debug.apk

## Option B – GitHub Actions (no local setup)
1. Create a new GitHub repo and push this folder to it.
2. Open the Actions tab > "Build APK" (runs on push, or click "Run workflow").
3. Download the artifact "TikTok-LoopGuard-debug-apk" (a zip containing app-debug.apk).

## Installing
Copy app-debug.apk to the phone, open it, allow "install unknown apps" for your file manager/browser.
Then enable the accessibility service (see in-app guide).
