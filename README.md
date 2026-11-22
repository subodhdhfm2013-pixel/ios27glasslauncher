# iOS 27 Glass Launcher (Android 7+)

Kotlin launcher project targeting API 32 (Android 12), minimum API 24.

Implemented in this source revision:
- HOME/default launcher activity
- Installed launcher-app enumeration, launch, icon/label rendering, alphabetical drawer and filtering
- Home pages, configurable grid columns and page size, icon size, label visibility
- Dock configuration and opacity
- App context menu: dock add/remove, hide, app info
- Hidden-app preference and unhide dialog
- Glass-inspired background/panels
- Control-center-style shortcuts to Android settings panels and brightness adjustment (write-settings authorization may be required)
- Wallpaper picker entry
- Basic app widget picker/host entry (placement/persistence is limited)

Limitations: drag-and-drop home rearrangement, folder management, notification rendering, weather/music widgets, backup/restore, robust widget placement/persistence, and a real flashlight toggle are not complete in this source. Android system restrictions mean network/mobile data, airplane mode, and some Bluetooth/Wi-Fi controls launch system settings rather than being toggled directly. Brightness write access may require granting special settings permission.

## Build
Open this directory in Android Studio, sync Gradle, then Build > Build APK(s). This source has not been compiled or device-tested in the current environment.
