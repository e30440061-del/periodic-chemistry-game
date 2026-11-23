# ماجراجویی جدول تناوبی

بازی آموزشی فارسی جدول تناوبی (نسخه مناسب GitHub Pages).

## انتشار با GitHub Pages
1. یک Repository بسازید و فایل‌های این پوشه را در ریشه آن آپلود کنید.
2. از تب **Settings → Pages**، در بخش Build and deployment، گزینه **GitHub Actions** را انتخاب کنید.
3. به تب **Actions** بروید و workflow با نام **Deploy static game to GitHub Pages** را اجرا/منتظر اجرا بمانید.
4. پس از پایان موفق، آدرس سایت در Settings → Pages نشان داده می‌شود.

## درباره دستیار
این نسخه روی GitHub Pages کاملاً استاتیک است و دستیار آموزشی آفلاین دارد. GitHub Pages API/serverless اجرا نمی‌کند. برای اتصال به مدل هوش مصنوعی آنلاین باید یک backend جداگانه با کلید API محفوظ راه‌اندازی شود؛ کلید را هرگز داخل HTML قرار ندهید.

## اجرا محلی
فایل `index.html` را در مرورگر باز کنید. برای نصب‌پذیری PWA و Service Worker، بهتر است سایت را از HTTPS اجرا کنید.
