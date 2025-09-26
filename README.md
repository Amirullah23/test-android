# TestAndroid

Sebuah aplikasi Android sederhana yang dikembangkan menggunakan Java.

## Fitur

- UI sederhana dengan TextView dan Button
- Implementasi click listener
- Toast notification
- Material Design theme

## Struktur Proyek

```
app/
├── src/
│   ├── main/
│   │   ├── java/com/example/testandroid/
│   │   │   └── MainActivity.java
│   │   ├── res/
│   │   │   ├── layout/
│   │   │   │   └── activity_main.xml
│   │   │   ├── values/
│   │   │   │   ├── colors.xml
│   │   │   │   ├── strings.xml
│   │   │   │   └── themes.xml
│   │   │   └── drawable/
│   │   └── AndroidManifest.xml
│   ├── test/ (Unit tests)
│   └── androidTest/ (Instrumented tests)
└── build.gradle
```

## Cara Menjalankan

1. Buka proyek di Android Studio
2. Sync project dengan gradle files
3. Jalankan aplikasi pada emulator atau device fisik

## Requirements

- Android Studio Arctic Fox atau lebih baru
- Android SDK API level 21 (Android 5.0) atau lebih tinggi
- JDK 8 atau lebih baru

## Dependencies

- AndroidX AppCompat
- Material Components
- ConstraintLayout
- JUnit untuk testing

## Development

Aplikasi ini menggunakan:
- Java sebagai bahasa pemrograman
- Material Design Components
- AndroidX libraries
- Gradle sebagai build system