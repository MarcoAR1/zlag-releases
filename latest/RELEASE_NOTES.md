# Zlag VPN v2.0.1-beta.1 (beta)

- Windows x64: installer includes Wintun; application has no Authenticode signature.
- Android: directly installable signed APK. Real-device VPN validation remains pending.
- Windows private VPS reachability was verified; actual match traffic validation remains pending.
- Android uses net.zlag.app and a new release signing key. The February app used net.zlag.client: this beta installs as a separate app, not an in-place update of that old package.
- macOS, iOS, Linux and Windows ARM64 are not part of this beta.
- Automatic in-app updates are not validated. Download updates from the website.

[Windows installer](https://raw.githubusercontent.com/MarcoAR1/zlag-releases/main/releases/v2.0.1-beta.1/zlag-setup-windows-amd64.exe) | [Android APK](https://raw.githubusercontent.com/MarcoAR1/zlag-releases/main/releases/v2.0.1-beta.1/zlag-client-android.apk)

Source commit: d641b679d5ed499c211b3050384b77a274cd1062. Source has local changes: True.