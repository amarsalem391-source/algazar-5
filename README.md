دليل سريع — كيفية تعديل الواجهة ودفع التغييرات عبر Git

ملخص:
- الخلفية المستخدمة في الواجهة موجودة هنا: assets/images/algzar-bg.jpg
- تم تحديث الصفحات التالية لتستخدم الخلفية: dashbord.html, user-page.html, index.html

خطوات سريعة لتعديل وصرف التغيير (محلياً):

1) انسخ/أضف الصورة الخلفية في المشروع:
   - ضع الصورة المطلوبة في المسار: assets/images/algzar-bg.jpg

2) افتح الفرع الجديد للعمل عليه (تغيير اسم الفرع حسب المهمة):

```bash
git checkout -b feature/update-background
```

3) راجع التغييرات محلياً واختبر الصفحات في المتصفح.

4) أضف الملفات التي عدلتها أو أضفتها:

```bash
git add dashbord.html index.html user-page.html README.md assets/images/algzar-bg.jpg
```

5) سجل التزام (commit) مع رسالة واضحة:

```bash
git commit -m "Update background image and add git instructions"
```

6) ادفع الفرع إلى المستودع البعيد:

```bash
git push origin feature/update-background
```

7) افتح Pull Request من الفرع الجديد لدمج التغييرات بعد المراجعة.

ملاحظات:
- لا يمكنني إنشاء ملف الصورة تلقائياً هنا؛ ضع صورتك بنفسك في المسار المحدد أعلاه.
- إن أردت، أستطيع إضافة صورة بديلة صغيرة (placeholder) أو ملف CSS إضافي للتجربة.

بالتوفيق! اگر تريد أعمل commit و push من جهازك، أعطني أمر الموافقة أو اسم الفرع لتضمينه في رسالة الالتزام.
