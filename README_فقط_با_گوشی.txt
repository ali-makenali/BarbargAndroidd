ساخت APK فقط با گوشی — بدون کامپیوتر

روش:
1) یک حساب GitHub بساز یا وارد حساب خودت شو.
2) در GitHub یک Repository جدید بساز (مثلاً BarbargAndroid).
3) فایل ZIP را در گوشی Extract کن.
4) محتویات پوشه را داخل Repository آپلود کن.
   مهم: پوشه .github هم باید همراه فایل‌ها آپلود شود.
5) در Repository وارد تب Actions شو.
6) اگر GitHub اجازه خواست، Workflows را فعال کن.
7) Workflow با نام «Build Android APK» را انتخاب کن.
8) روی Run workflow بزن.
9) چند دقیقه صبر کن تا ساخت تمام شود.
10) وارد اجرای موفق شو و در بخش Artifacts فایل «Barbarg-APK» را دانلود کن.
11) ZIP Artifact را استخراج کن؛ فایل app-debug.apk همان APK قابل نصب است.

نکته:
GitHub Actions روی سرور GitHub پروژه را Build می‌کند؛ بنابراین برای ساخت APK نیازی به کامپیوتر یا Android Studio نداری.

اگر Build خطا داد، متن خطا یا اسکرین‌شات صفحه Actions را به ChatGPT بفرست.


اصلاحات نسخه جدید:
- Java و Kotlin هر دو روی JVM 17 تنظیم شده‌اند.
- MainActivity از Activity استاندارد اندروید استفاده می‌کند؛ بنابراین به وابستگی AndroidX Activity که در فایل قبلی تعریف نشده بود نیاز ندارد.
- پس از بارگذاری فایل‌ها در GitHub، از Actions گزینه Run workflow را اجرا کنید.
