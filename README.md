# تطبيق أذكاري | Athkari

تطبيق أذكار إسلامية باللغة العربية مبني بـ Flutter.

## المزايا
- أذكار الصباح والمساء والنوم والاستيقاظ وبعد الصلاة.
- حصن المسلم: السفر، الطعام، المنزل، المسجد، المرض وغيرها.
- عداد تسبيح مع حفظ العدد.
- المفضلة.
- بحث في الأذكار.
- الوضع الليلي.
- مواقيت صلاة قابلة للتوسعة وربطها لاحقًا بمصدر مواقيت موثوق.
- تحديد الموقع عبر GPS كأساس لمزايا القبلة والمواقيت.
- صفحة القبلة مع حساب اتجاه القبلة محليًا من الإحداثيات.
- بنية جاهزة للبناء والنشر عبر GitHub.

## التشغيل
```bash
flutter pub get
flutter run
```

## إنشاء APK
```bash
flutter build apk --release
```

ملف APK سيكون عادة في:
`build/app/outputs/flutter-apk/app-release.apk`

## GitHub
```bash
git init
git add .
git commit -m "Initial Athkari app"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/athkari-app.git
git push -u origin main
```
