# SMART PKK

Aplikasi SMART PKK berbasis web untuk edukasi dan pemantauan kesehatan masyarakat.

- Web: <https://andazmortin88.github.io/smart_pkk/>
- Android: wrapper WebView pada direktori `app/`

## Build APK

GitHub Actions akan membangun APK debug secara otomatis ketika proyek Android berubah. Hasil build tersedia sebagai artifact bernama `SMART-PKK-APK` dan berisi:

- `SMART-PKK.apk`
- `SHA256SUMS.txt`

Build manual memerlukan JDK 17, Android SDK 35, dan Gradle 8.9:

```bash
gradle :app:assembleDebug
```
