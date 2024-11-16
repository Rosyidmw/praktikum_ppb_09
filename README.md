# praktikum_09

<!-- A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference. -->

#### Cara mengatasi error seperti ini
![error-running](https://github.com/user-attachments/assets/782f38ac-3cfc-405c-966f-d621e762c2ae)

#### Beberapa langkah mengatasi error
1) Update gradle pada gradle-wrapper.properties menjadi 
```
distributionUrl=https\://services.gradle.org/distributions/gradle-8.4-all.zip
```

2) Update setting.gradle pada folder android menjadi
```
id "com.android.application" version "8.3.0" apply 
```

3) Update build.gradle pada folder android/app/ menjadi
```
ndkVersion = "25.1.8937393"
```