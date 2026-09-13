# Zlag VPN v2.0.1-beta.2 (beta)

Android 2.0.1-beta.2 fixes:

- Zlag launcher artwork for every screen density, with dark background and themed-icon support.
- Email/password login uses native HTTP, fixing the Android WebView Network Error.
- Google sign-in opens the system browser and returns to the app using a short-lived code protected by S256 PKCE.
- Keeps the existing Android application ID and release key: install over beta.1 to update.

The Windows installer remains at 2.0.1-beta.1. APK signature, alignment, upgrade,
launcher and real API error response were checked on the Android emulator.
Google account completion and VPN operation on a physical phone still need testing.


- Windows x64 (v2.0.1-beta.1): installer includes Wintun; application has no Authenticode signature.
- Android: directly installable signed APK. Real-device VPN validation remains pending.
- Windows private VPS reachability was verified; actual match traffic validation remains pending.
- Android uses net.zlag.app and a new release signing key. The February app used net.zlag.client: this beta installs as a separate app, not an in-place update of that old package.
- macOS, iOS, Linux and Windows ARM64 are not part of this beta.
- Automatic in-app updates are not validated. Download updates from the website.

[Windows installer](https://raw.githubusercontent.com/MarcoAR1/zlag-releases/main/releases/v2.0.1-beta.1/zlag-setup-windows-amd64.exe) | [Android APK](https://raw.githubusercontent.com/MarcoAR1/zlag-releases/main/releases/v2.0.1-beta.2/zlag-client-android.apk)

Source commit: d641b679d5ed499c211b3050384b77a274cd1062. Source has local changes: True.