# Sushi Camera

An experimental lightweight Camera2 Android camera app using no advertising, analytics, or network SDKs. Features include photo/video capture, zoom, manual controls where device capabilities permit, and a compact dark pro-camera interface.

## Build

GitHub Actions builds a debug APK on changes to `main` and through a manual `workflow_dispatch` run. After a successful run, open Actions → Build Sushi Camera APK → Artifacts → `SushiCamera-debug-APK`.

## Device support

Android 10+; hardware support varies. Third-party apps cannot reliably become the default system camera for all capture flows on modern Android, even when relevant camera intent filters are declared. This software is an untested prototype, not a replacement for OEM camera processing.
