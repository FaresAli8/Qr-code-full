# SmartQRCode Builder

## متطلبات التشغيل
- JDK 17 أو أحدث.
- Android SDK (يفضل Command Line Tools المثبتة).

## خطوات البناء (Terminal)
1. تأكد من إعطاء صلاحية التنفيذ لـ gradlew:
   ```bash
   chmod +x gradlew
   ```
2. ابدأ البناء:
   ```bash
   ./gradlew assembleDebug
   ```
3. ستجد ملف الـ APK الناتج هنا:
   `app/build/outputs/apk/debug/app-debug.apk`

## ملاحظات
- يستخدم التطبيق **Jetpack Compose** للواجهة.
- يستخدم **CameraX** و **ZXing** للمسح والتوليد.
- يستخدم **FileProvider** لمشاركة صور الـ QR بأمان.