# 🎨 موقعي الشخصي — خالد الحارثي

موقع شخصي (Portfolio) لمصمم جرافيك ومتخصص في العلامات التجارية.
مبني بـ HTML و CSS و JavaScript خالص — بدون أي مكتبات خارجية، سريع وخفيف.

> **Personal portfolio website** for a graphic designer & brand specialist.
> Built with vanilla HTML, CSS & JS — no frameworks, no build step.

---

## ✨ المميزات

- تصميم عصري وحيوي بواجهة **عربية RTL** كاملة
- قسم رئيسي متحرك مع كلمة تخصص تتبدّل تلقائيًا
- شريط خدمات متحرك (Marquee)
- عدّاد أرقام يتحرك عند الظهور
- معرض أعمال بفلاتر تصنيف
- نموذج تواصل يفتح البريد جاهزًا
- **متجاوب بالكامل** مع الجوال + يحترم `prefers-reduced-motion`

---

## 🚀 التشغيل محليًا

ما يحتاج أي تجهيزات. فقط افتح `index.html` في المتصفح.

أو شغّل خادمًا محليًا بسيطًا:

```bash
# باستخدام Python
python3 -m http.server 8000

# ثم افتح
# http://localhost:8000
```

---

## 🌐 النشر على GitHub Pages (مجانًا)

1. أنشئ مستودعًا (repository) جديدًا على GitHub وارفع هذه الملفات إليه:
   ```bash
   git init
   git add .
   git commit -m "أول نسخة من الموقع"
   git branch -M main
   git remote add origin https://github.com/USERNAME/REPO.git
   git push -u origin main
   ```
2. من صفحة المستودع، افتح **Settings → Pages**.
3. تحت **Source** اختر الفرع `main` والمجلد `/ (root)`، ثم **Save**.
4. بعد دقيقة يصير موقعك متاحًا على:
   `https://USERNAME.github.io/REPO/`

> 💡 لربط نطاق خاص (Custom domain)، أضف ملف `CNAME` يحتوي على نطاقك.

---

## ✏️ ما الذي عليك تعديله

| المكان | الملف | التعديل |
|--------|-------|---------|
| الاسم `خالد الحارثي` | `index.html` | ضع اسمك (يظهر في الهيدر والفوتر و"من أنا") |
| الأحرف `KH` في الشعار | `index.html` | ضع أول حرفين من اسمك |
| البريد `hello@example.com` | `index.html` + `assets/js/main.js` | بريدك (موجود في مكانين) |
| الهاتف `+968 9000 0000` | `index.html` | رقمك / واتساب |
| روابط السوشل ميديا `href="#"` | `index.html` | حساباتك |
| الأرقام / سنوات الخبرة | `index.html` | إحصائياتك الحقيقية |
| صور المعرض (التدرّجات اللونية) | `index.html` + `assets/css/style.css` | صور مشاريعك |
| الألوان | `assets/css/style.css` | متغيرات `:root` في أعلى الملف |

---

## 📁 هيكل المشروع

```
portfolio-site/
├── index.html            # الصفحة الرئيسية
├── assets/
│   ├── css/style.css     # كل التنسيقات
│   └── js/main.js        # كل التفاعلات
├── README.md
├── LICENSE
└── .gitignore
```

---

## 📄 الرخصة

هذا المشروع متاح تحت رخصة [MIT](LICENSE) — استخدمه وعدّله بحرية.
