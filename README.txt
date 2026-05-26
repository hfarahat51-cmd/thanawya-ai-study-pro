Thanawya AI Study Pro - Secure Files

الملفات الموجودة:
1. login.html
   صفحة تسجيل الدخول وإنشاء الحساب.

2. index.html
   صفحة المحتوى المحمي.
   تتحقق من:
   - تسجيل الدخول
   - الاشتراك active
   - الجهاز الأول فقط
   ثم تفتح PDF من Supabase Storage.

3. subscribe.html
   صفحة تظهر للطالب لو الاشتراك غير مفعل أو انتهى.

قبل الرفع:
1. افتح login.html وغير:
   PUT_YOUR_SUPABASE_PROJECT_URL_HERE
   PUT_YOUR_SUPABASE_ANON_KEY_HERE

2. افتح index.html وغير نفس القيم:
   PUT_YOUR_SUPABASE_PROJECT_URL_HERE
   PUT_YOUR_SUPABASE_ANON_KEY_HERE

3. في index.html تأكد من اسم الـ bucket:
   const PDF_BUCKET = "course-files";

4. في index.html تأكد من اسم ملف الـ PDF:
   const PDF_PATH = "thanawya-study-pro.pdf";

5. في subscribe.html غير رقم الواتساب:
   https://wa.me/201000000000

بعد التعديل:
ارفع الملفات الثلاثة على الاستضافة:
- login.html
- index.html
- subscribe.html

ملحوظة مهمة:
لا تبعت ملف PDF للطالب مباشرة.
ارفعه داخل Supabase Storage في bucket خاص Private باسم course-files.
