# Alikhonov English Test — APK build

Bu loyiha APK build qilishga tayyor Flutter loyiha.

## Telefon orqali
1. Loyihani GitHub repository'ga yuklang.
2. Repository'da Flutter build workflow ishga tushiring.
3. `build/app/outputs/flutter-apk/app-release.apk` faylini artifact sifatida yuklab oling.

## Lokal Flutter
`flutter pub get`
`flutter build apk --release`

APK chiqishi:
`build/app/outputs/flutter-apk/app-release.apk`

## Muhim
Bu ZIP ichida Flutter SDK yoki Android SDK yo'q. Ularni ZIP ichiga qo'shish kerak emas; build server Flutter/Android toolchain'dan foydalanadi.
