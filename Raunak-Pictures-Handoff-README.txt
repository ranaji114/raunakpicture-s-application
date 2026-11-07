Raunak Pictures 1.1.3 — Owner handoff

Files:
- Raunak-Pictures-Production-1.1.3.apk: signed Android release APK.
- Raunak-Pictures-Source-1.1.3.zip: modified source project (no node_modules or build outputs).
- Raunak-Pictures-release-key.p12: private signing key required for future APK updates.
- Raunak-Pictures-release-key-info.txt: keystore alias/password and Android OAuth SHA-1.

IMPORTANT:
Keep the .p12 keystore and its password note in separate secure places. Do not upload either to GitHub or share publicly. Every future update to this installed app must be signed with this same keystore; losing it means the new APK cannot update this installation normally.

Install the APK over version 1.1.2 without uninstalling. After install, open Backup & Restore, connect the owner's Google account if prompted, and run Sync now. Keep a separate manual JSON backup too. Google Drive OAuth is limited to the configured owner/test account while the consent screen remains in Testing.

Source build prerequisites: Node.js/npm, JDK 21, Android SDK platform/build-tools 36. Run npm ci, npm run lint, npm run build, npx cap sync android, then build android/app release using the provided signing credentials as environment variables RP_RELEASE_KEYSTORE, RP_RELEASE_STORE_PASSWORD, RP_RELEASE_KEY_ALIAS, RP_RELEASE_KEY_PASSWORD.

APK SHA-256: fe814810e8dd884648de68670bcf5ed99717189c0c84a1110b30b79e6aa81418
Package: com.raunakpictures.studiomanagement
Version: 1.1.3 (versionCode 8)
Release certificate SHA-1: 84:C2:BE:6A:32:32:4E:2B:39:05:D1:F9:29:19:4F:11:F6:DB:01:0A
