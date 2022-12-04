# How-to-install-wordpress-on-xampp

حالا برای نصب وردپرس ابتدا با مراجعه به وبسایت رسمی وردپرس آخرین نسخه منتشر شده از این سیستم مدیریت محتوای محبوب را دانلود کنید، پیشنهاد میکنم به آدرس https://fa.wordpress.org مراجعه کنید تا نسخه فارسی را دریافت کنید و توصیه اکیدی که دارم این است که به دلیل مسائل امنیتی به هیچ وجه از سایر سایت‌ها وردپرس را دانلود نکنید چرا که ممکن است با قرار دادن کدهای مخرب در فایل‌های وردپرس سایت شما مورد هک قرا گیرد، البته ذکر این نکته که اگر از هاست مناسب برای سایت وردپرس استفاده کرده باشید به راحتی با اسکن فایلهای مختلف میتواند در صورت وجود باگ و ویروسی آن را شناسایی کند.

![get wordpress](https://user-images.githubusercontent.com/119763541/205469063-717b831b-709c-443f-8d6c-265bfb01f508.png)

![get wordpress1](https://user-images.githubusercontent.com/119763541/205469068-56f05800-ad78-4281-a5a6-94f42abe9799.png)

پس از دانلود نسخه Zip وردپرس به پوشه‌ی c:\xampp\htdocs که در درایو C قرار دارد مراجعه کرده و یک پوشه جدید با آدرسی که قصد دارید در مرورگر پس از مراجعه به آن سایت اجرا شود وارد کنید.  بنابراین برای دسترسی به وردپرس و مشاهده سایت در لوکال هاست لازمه تا به آدرس

localhost/نام پوشه


مراجعه کنید و سایت را در لوکال هاست به صورت کامل مدیریت کنید.

![setup-new-wordpress-folder-localhost-xampp](https://user-images.githubusercontent.com/119763541/205469405-c5a6769f-ee1d-49c8-8f9c-17c7ed822345.jpg)

پس از ایجاد پوشه، فایل دانلود شده وردپرس را در آن کپی کرده و از حالت zip خارج کنید. سپس فایل‌های موجود در پوشه wordpress را نیز با استفاده از عملیات cut به دایرکتوی

c:\xampp\htdocs\نام پوشه

منتقل کنید، دلیل این کار اینه که آدرس انتخاب شده برای سایت شما طولانی نباشد. در مرحله بعد مشابه تصویر زیر فایلی که با عنوان wp-config-sample.php در اسکریپت وردپرس وجود دارد را به wp-config.php تغییر نام دهید و برای وارد کردن اطلاعات دیتابیس به ترتیبی که در ادامه به آن میپردازم اقدام کنید.

![edit-wp-config-xampp](https://user-images.githubusercontent.com/119763541/205469907-1304ed4a-0a79-4f68-9a0d-c942c8d2d7d5.jpg)

DB_NAME: 

این بخش شامل نام پایگاه داده وردپرس شماست که در صفحه phpmyadmin ساختید، بنابراین کافیه تا مشابه نمونه فوق نام پایگاه داده خودتان را به جای آن وارد کنید .

DB_USER:

این بخش نیز شامل نام کاربر پایگاه داده وردپرس می‌باشد، در حالت پیشفرض نام یوزر پایگاه داده در زمپ root می‌باشد بنابراین مانند نمونه نیز به جای یوزر پایگاه داده عبارت root را وارد کنید.

DB_PASSWORD:

از آنجایی که در ساخت پایگاه داده با استفاده از برنامه زمپ پسوردی انتخاب نمیشه این گزینه باید خالی گذاشته شود، بنابراین عبارت password_here را از آن حذف کرده و خالی بگذارید.

پس از اینکه به درستی موارد مورد نظر وارد شد فایل مورد نظر را با استفاده از کلیدهای ترکیبی Ctrl + S ذخیره کنید تا اطلاعات مربوط به پایگاه داده وردپرس که شامل نام پایگاه داده، نام کاربر پایگاه داده و رمز پایگاه داده میشود ذخیره گردد، سپس مرورگر خود را باز کنید و پس از

localhost/ نام پوشه‌ای که وردپرس در آن قرار دارد

وارد کنید.


