[README.md](https://github.com/user-attachments/files/28685636/README.md)
<div dir="rtl">

# 🎯 محاكي الميديا باينج | Media Buying Simulator

> لعبة تعليمية تفاعلية لاحتراف شراء الإعلانات الرقمية وإدارة الحملات — من الإطلاق الأول حتى إدارة وكالة كاملة.

[![بناء التطبيق](https://github.com/zainabmjcreates-oss/media-buying-simulator/actions/workflows/build-apk.yml/badge.svg)](https://github.com/zainabmjcreates-oss/media-buying-simulator/actions)

---

## ✨ ما هي اللعبة؟

محاكٍ تدريبي عملي يعلّمك **شراء الإعلانات (Media Buying)** عبر اللعب، بمحرّك رياضي واقعي يحاكي سلوك منصّات الإعلان الحقيقية:

- 🎓 **الأكاديمية**: 50 مصطلحاً في 7 مجموعات + اختبار نهائي
- 🎯 **المستوى الأول — الحملات**: 5 مهام (الإطلاق، موسم الذروة، السوق المزدحم، الميزانية الضيقة، الحملة الطويلة)
- 📊 **المستوى الثاني — المحفظة**: إدارة عدة حملات بميزانية مشتركة وتكامل القمع
- 🏢 **المستوى الثالث — الوكالة**: إدارة عملاء بشخصيات، وفريق، وأحداث، وسمعة
- 🏅 **8 شارات** وشهادة إتمام

---

## 📥 كيف تشغّل اللعبة؟

### 🌐 على المتصفح (الحاسوب وأي جهاز)
افتح الرابط مباشرة:
```
https://zainabmjcreates-oss.github.io/media-buying-simulator
```
تعمل فوراً على Windows و macOS و Linux وأي متصفح حديث.

### 📱 على iPhone / iPad (كتطبيق)
1. افتح الرابط أعلاه في **Safari**
2. اضغط زر **المشاركة** (المربع مع السهم) ⬆️
3. اختر **"إضافة إلى الشاشة الرئيسية"**
4. يظهر التطبيق على شاشتك ويعمل **دون إنترنت**

### 🤖 على Android (تطبيق APK حقيقي)
1. اذهب إلى: **[Releases](https://github.com/zainabmjcreates-oss/media-buying-simulator/releases)**
2. حمّل ملف **`media-buying-simulator.apk`** من أحدث إصدار
3. افتحه على هاتفك وثبّته (فعّل "التثبيت من مصادر غير معروفة" إن طُلب)

> أو ثبّتها كـ PWA من Chrome مثل خطوات iPhone أعلاه.

---

## 🛠️ للمطوّرين

المشروع مبني بـ **React** ومغلّف بـ **Capacitor** لأندرويد.

</div>

```bash
npm install
npx cap add android
npx cap sync android
cd android && ./gradlew assembleDebug
```

<div dir="rtl">

البناء يتم **تلقائياً في السحابة** عبر GitHub Actions عند كل رفع — لا حاجة لأدوات محلية.

### الملفات
| الملف | الوصف |
|------|-------|
| `www/index.html` | اللعبة كاملة (React مضمّن، تعمل دون إنترنت) |
| `www/sw.js` | عامل الخدمة (PWA offline) |
| `www/manifest.json` | بيانات التطبيق |
| `.github/workflows/` | البناء والنشر التلقائي |
| `capacitor.config.json` | إعدادات Capacitor |

---

## ⚙️ إعداد المستودع (مكتمل تلقائياً)

✅ GitHub Pages: تم التفعيل تلقائياً عند رفع الملفات (مصدر: GitHub Actions)

✅ Releases: يُنشأ تلقائياً عند كل بناء (APK متاح للتحميل المباشر)

---

## 📄 الترخيص

تعليمي / مفتوح للاستخدام.

</div>
