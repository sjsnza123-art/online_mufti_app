# Online Mufti App

یہ ایک **Flutter project structure** ہے جو GitHub کے لیے تیار ہے۔  
آپ اسے سیدھا GitHub پر upload کر سکتے ہیں اور `flutter build apk` سے فوراً APK بنا سکتے ہیں۔

## استعمال کا طریقہ
```bash
git clone https://github.com/USERNAME/online_mufti_app.git
cd online_mufti_app
flutter pub get
flutter build apk --release
```

APK path: `build/app/outputs/flutter-apk/app-release.apk`

## نوٹ
- اپنی اصل ایپ کا کوڈ `lib/main.dart` میں ڈالیں۔
- اپنی dependencies کو `pubspec.yaml` میں شامل کریں۔
- `assets/` فولڈر میں images, sounds, وغیرہ رکھیں۔
