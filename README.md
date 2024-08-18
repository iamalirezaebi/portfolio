
### مرحله ۱: ایجاد حساب کاربری در GitHub
اگر هنوز حساب GitHub ندارید، باید یک حساب ایجاد کنید.
1. به [GitHub](https://github.com/) بروید.
2. روی **Sign up** کلیک کنید و دستورالعمل‌ها را برای ایجاد حساب خود دنبال کنید.

### مرحله ۲: ایجاد یک مخزن جدید
1. به حساب GitHub خود وارد شوید.
2. در گوشه بالای سمت راست صفحه، روی آیکون **+** کلیک کرده و **New repository** را انتخاب کنید.
3. نام مخزن را به این صورت قرار دهید: **yourusername.github.io**. نام کاربری خود را به جای `yourusername` قرار دهید. این نامگذاری اهمیت دارد زیرا به GitHub می‌گوید که مخزن شما را به عنوان یک وبسایت میزبانی کند.
4. در صورت تمایل، توضیحی اضافه کنید.
5. انتخاب کنید که آیا می‌خواهید مخزن عمومی یا خصوصی باشد.
6. می‌توانید مخزن را با یک فایل **README** مقداردهی اولیه کنید (اختیاری).
7. روی **Create repository** کلیک کنید.

### مرحله ۳: راه‌اندازی وبسایت پورتفولیو
حالا که مخزن شما ایجاد شده است، می‌توانید شروع به راه‌اندازی پورتفولیوی خود کنید.
1. می‌توانید یک فایل `index.html` را مستقیماً در مخزن خود ایجاد کنید یا از یک قالب استفاده کنید.
2. برای ایجاد یک فایل جدید، روی **Add file** > **Create new file** کلیک کنید.
3. نام فایل را `index.html` بگذارید. این صفحه اصلی پورتفولیوی شما خواهد بود.
4. محتوای HTML خود را به این فایل اضافه کنید. به عنوان مثال:
‏   ```html
‏   <!DOCTYPE html>
‏   <html lang="en">
‏   <head>
‏       <meta charset="UTF-8">
‏       <meta name="viewport" content="width=device-width, initial-scale=1.0">
‏       <title>پورتفولیو من</title>
‏   </head>
‏   <body>
‏       <h1>به پورتفولیو من خوش آمدید</h1>
‏       <p>سلام، من [نام شما] هستم، یک [حرفه شما].</p>
‏       <p>این‌ها برخی از پروژه‌های من هستند:</p>
‏       <ul>
‏           <li><a href="https://github.com/yourusername/project1">پروژه 1</a></li>
‏           <li><a href="https://github.com/yourusername/project2">پروژه 2</a></li>
‏       </ul>
‏   </body>
‏   </html>
   ```
5. به پایین صفحه بروید و روی **Commit new file** کلیک کنید تا تغییرات شما ذخیره شود.

### مرحله ۴: سفارشی‌سازی پورتفولیو (اختیاری)
شما می‌توانید پورتفولیوی خود را با افزودن CSS برای استایل‌دهی و JavaScript برای تعاملات، سفارشی کنید.
1. فایل‌های اضافی مانند `style.css` برای استایل‌دهی یا `script.js` برای JavaScript ایجاد کنید.
2. این فایل‌ها را در `index.html` خود لینک کنید.
‏   ```html
‏   <link rel="stylesheet" href="style.css">
‏   <script src="script.js"></script>
   ```
3. همچنین می‌توانید تصاویر، صفحات بیشتر، و حتی از فریم‌ورک‌هایی مانند Bootstrap استفاده کنید تا سایت شما حرفه‌ای‌تر به نظر برسد.

### مرحله ۵: انتشار پورتفولیو
پس از اینکه تغییرات خود را انجام دادید:
1. به **Settings** در مخزن خود بروید.
2. به پایین بروید تا به بخش **GitHub Pages** برسید.
3. در قسمت "Source"، شاخه‌ای که می‌خواهید استفاده کنید (معمولاً `main` یا `master`) را انتخاب کنید.
‏4. GitHub به شما یک آدرس URL می‌دهد که پورتفولیوی شما در آن منتشر شده است، معمولاً `https://yourusername.github.io/`.

### مرحله ۶: بازبینی و به‌روزرسانی پورتفولیو
1. به آدرس URL پورتفولیوی خود بروید تا ببینید چگونه به نظر می‌رسد.
2. همیشه می‌توانید به مخزن خود بازگردید تا تغییرات را اعمال کنید یا محتوای جدید اضافه کنید.
3. هر زمانی که تغییراتی انجام دهید، GitHub Pages به‌طور خودکار سایت زنده شما را به‌روز می‌کند.

### مرحله ۷: به اشتراک گذاشتن پورتفولیو
وقتی پورتفولیوی شما آماده شد، می‌توانید لینک آن را با کارفرمایان بالقوه به اشتراک بگذارید، به رزومه خود اضافه کنید یا آن را در پروفایل‌های شبکه‌های اجتماعی خود قرار دهید.

### نکات اضافی:
- **استفاده از قالب**: اگر تمایل ندارید یک سایت از ابتدا بسازید، می‌توانید یک قالب پورتفولیو GitHub Pages پیدا کرده و آن را به مخزن خود فورک کنید.
- **اضافه کردن دامنه سفارشی**: اگر می‌خواهید یک دامنه سفارشی (مثلاً `www.yourname.com`) داشته باشید، می‌توانید آن را در بخش **Custom domain** GitHub Pages تنظیم کنید.
- **آنالیز و SEO**: می‌توانید ابزارهایی مانند Google Analytics یا ابزارهای دیگر را اضافه کنید تا ترافیک را مانیتور کرده و پورتفولیوی خود را برای موتورهای جستجو بهینه کنید.
