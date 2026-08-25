# VELORA Wellness — GitHub-ready Android build

This repository builds the VELORA Wellness app into an Android APK using GitHub Actions.

## What to do
1. Create/open a GitHub repository.
2. Upload the contents of this folder to the repository root.
3. Commit to the `main` branch.
4. Open the repository's **Actions** tab.
5. Select **Build VELORA Wellness Android APK**.
6. Open the successful workflow run.
7. Under **Artifacts**, download `VELORA-Wellness-debug-apk`.
8. Extract it and install `app-debug.apk` on an Android phone.

The workflow is intentionally unsigned for easy testing. A production Google Play release should use a protected Android signing key and produce a signed release artifact/AAB.

The build targets Android API 36, matching Google's 2026 target requirement for new apps/updates from August 31, 2026.

The app currently contains the VELORA Wellness UI and local persistence. Real cloud login/sync and robust native scheduled/background notifications are still production upgrades.
