# Govind Truecaller (Android App)

Complete Kotlin + Jetpack Compose Android Studio project implementing:
- **Live Call Screening & Auto-Blocking** (`GovindCallScreeningService` with <5s decision budget)
- **Built-in Dialer & Full Call History Tracking** (Incoming, Outgoing, Missed, Blocked)
- **Offline Number Database** (Room SQLite pre-seeded + Wi-Fi delta sync)
- **Global Number & Location Lookup** (`libphonenumber` E.164, geocoder, carrier)
- **Blocklist & Whitelist Management** + adjustable Spam Auto-Block Threshold
- **Vayu (Air Quality / AQI) Tracking** (OpenAQ API with 30-min battery-saving cache)
- **Battery-Optimized Sync & Encrypted Cloud Backup** (`WorkManager` Wi-Fi + battery constraints + AES-256 export)
- **Official Fraud Reporting Shortcut** (Sanchar Saathi Chakshu)

## How to Build & Run
1. Unzip `govind-truecaller-android.zip`.
2. Open the `GovindTruecallerAndroid` folder in **Android Studio**.
3. Let Gradle sync all dependencies (internet required on your PC for first Gradle sync).
4. Connect an Android phone (Android 10 / API 29+) and click **Run**.
5. Grant Call Screening Role & permissions when prompted.
