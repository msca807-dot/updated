GARMENT QUALITY CHECKLIST - APK READY PROJECT

This package wraps the completed touch-signature checklist as a native Android app.

FEATURES
- Fixed read-only checklist template
- Before Lunch / After Lunch
- Editable inspection results
- Touch signature in Remarks area
- Local data saving
- Print / PDF support through Android WebView

BUILDING THE APK WITHOUT INSTALLING SOFTWARE
Recommended: upload this project to a GitHub repository, then use GitHub Actions or another cloud Android build service.

A developer/cloud build environment should run:
./gradlew assembleDebug

Expected output:
app/build/outputs/apk/debug/app-debug.apk

IMPORTANT
The package uses a WebView wrapper and the full app is included in:
app/src/main/assets/
