# Vortex Tech على GitHub Pages

## 1) رفع الموقع
1. أنشئ مستودع جديد على GitHub (لازم **Public** علشان Pages المجاني).
2. ارفع كل ملفات المجلد ده (index.html, admin.html, style.css, videos.json, .nojekyll).
3. من Settings ← Pages: اختار Branch = main و Folder = / (root) ثم Save.
4. بعد دقيقة الموقع يظهر على: https://USERNAME.github.io/REPO/

## 2) عمل التوكن (للأدمن)
1. GitHub ← Settings ← Developer settings ← Personal access tokens ← **Fine-grained tokens** ← Generate new token.
2. Repository access: **Only select repositories** واختار مستودع الموقع بس.
3. Permissions ← Repository permissions ← **Contents: Read and write**.
4. انسخ التوكن (بيظهر مرة واحدة).

## 3) استخدام لوحة الأدمن
افتح: https://USERNAME.github.io/REPO/admin.html
- حط اسم حسابك واسم المستودع والتوكن واضغط حفظ (بيتخزن في متصفحك بس).
- أضف محتوى من التبويبات: لينك يوتيوب، فيديو (mp4/webm)، صورة (jpg/png/webp/gif)، كتاب PDF، أو لينك منشور (فيسبوك/إنستجرام/تليجرام...). الملفات حتى 50MB.
- الموقع بيعرض فلتر (الكل / فيديو / صور / كتب / منشورات) تلقائيًا حسب المحتوى اللي ضفته.
- التغييرات بتظهر على الموقع بعد حوالي دقيقة (وقت نشر GitHub Pages).

## ملاحظات أمان
- التوكن زي كلمة السر: متشاركوش، ولو اتسرب امسحه من GitHub فورًا.
- صفحة admin.html بتبان لأي حد، لكن مفيش حد يقدر يعدل من غير التوكن.
- المستودع Public، يعني ملفات الفيديو المرفوعة عامة.
- GitHub مش مناسب لمكتبة فيديوهات كبيرة (حد الملف 100MB وحجم الموقع حوالي 1GB)؛ يوتيوب هو الأفضل.
