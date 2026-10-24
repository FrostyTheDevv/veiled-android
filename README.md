# Veiled for Android

This is the official public distribution repository for Veiled Android release artifacts. Application source and build credentials are maintained separately.

Signed APKs appear in [Releases](https://github.com/FrostyTheDevv/veiled-android/releases) after release validation. An empty release list means no official Android build has been published here yet.

## Install with Obtainium

After the first beta is published:

1. Open Obtainium and choose **Add App**.
2. Set the app source to `https://github.com/FrostyTheDevv/veiled-android`.
3. Enable **Include Prereleases** to receive beta builds.
4. Select the Android `.apk` release asset. Checksum, metadata, and signature-report files are verification files, not installers.
5. Add the app and follow Android's installation prompts. Obtainium tracks later releases; Android may still require approval to install an update.

## Supported devices

- Android 8.0 or newer (API 26+).
- 64-bit `arm64-v8a` and `x86_64` devices.
- Application ID: `lol.veiled.android`.

## Verify a download

Each published release includes the APK, its SHA-256 checksum, package metadata, and an APK signature report. Compare the APK's checksum with its release checksum file. The release notes identify the signing-certificate fingerprint verified for that build.

Keep the installed application's signing identity when updating. APKs signed with a different key cannot update the existing installation. Avoid uninstalling merely to bypass a signature mismatch; report it so the release can be investigated.

Google Play distribution is managed separately. Obtainium publication does not mean a Play submission has been approved.
