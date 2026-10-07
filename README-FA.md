# انبارنو
ساخت APK: همان روش DayFlow (آپلود در GitHub ← Actions ← Run workflow ← Artifact: Anbarno-apk).
## یک‌بار تنظیم Firebase (برای ورود گوگل و کاربران)
1. Firebase Console ← Authentication ← Google را فعال کن.
2. Firestore Database را بساز و محتوای `firestore.rules` را در Rules بگذار و Publish کن.
3. بدون این مرحله برنامه فقط با «ادامه بدون ورود» (ذخیره محلی) کار می‌کند.
