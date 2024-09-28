# مشروع توقيع تطبيقات Android

هذا المشروع يهدف إلى تسهيل عملية توقيع تطبيقات Android باستخدام أدوات مختلفة.

## المحتويات

- [التثبيت](#التثبيت)
- [التوقيع](#التوقيع)
- [الأدوات المستخدمة](#الأدوات-المستخدمة)
- [معلومات عن build-tools](#معلومات-عن-build-tools)

## التثبيت

لتحديث الحزم المثبتة وتثبيت Python، افتح الطرفية واستخدم الأوامر التالية:

    
    pkg update && pkg upgrade
    pkg install python
    pkg install wget
    pkg install unzip
    pkg install openjdk-17

لتنزيل ملف ZIP الخاص بالتوقيع، استخدم الأمر التالي:

    wget https://github.com/Gisnsl/singtuer/releases/download/1.0/signature.zip
التوقيع
لتشغيل البرنامج والتوقيع، استخدم الأمر التالي:


    
    unzip signature.zip
    cd signature
    chmod +x *
    python main.py
    
ادوات أخرى يمكنك استخدامها :
aapt2: أداة لتحليل وتعديل ملفات APK. تستخدم لتحضير ملفات APK قبل التوقيع.
zipalign: أداة لمحاذاة ملفات APK. تساعد في تحسين أداء التطبيق عند التثبيت.
unzip: أداة لفك ضغط ملفات ZIP. تُستخدم لفك ضغط الملفات المنزلة.
معلومات عن build-tools
build-tools هي مجموعة من الأدوات المستخدمة في بناء وتطوير تطبيقات Android. تتضمن هذه الأدوات:

aapt: أداة لتحليل وتعبئة ملفات APK. تستخدم لتحويل الموارد إلى ملفات ثنائية.
aapt2: النسخة المحسنة من aapt، تعمل بشكل أسرع وتدعم ميزات جديدة.
zipalign: أداة لتحسين APKs عن طريق محاذاة البيانات في ذاكرة التخزين.
lint: أداة لتحليل الشيفرة للكشف عن الأخطاء والممارسات السيئة.
proguard: أداة لتقليل حجم تطبيقات Android وتحسين الكود.

## المطور:
- **AHMED**
- جميع حقوق الطبع والنشر محفوظة للمطور AHMED.
- **قناتي على التيليجرام**
![Telegram](https://img.shields.io/badge/Telegram-Join%20Chat-blue.svg) [![Telegram](https://img.icons8.com/color/48/000000/telegram-app.png)](https://t.me/maho9s)
