---
title: نصب پایتون و ide
date: 2025-01-30
category: [اموزش پایتون]
priority: 0
image:
    path: /assets/img/poster/python-tutorial/images-00.jpg
---
>هداف یادگیری
>پس از این بخش:
>- با پایتون اشنا خواهید شد
>- راجب مفسر و ide ها یاد میگیرید
>- ابزار های لازم برای برنامه نویسی در پایتون را نصب خواهید کرد
{: .prompt-tip }


## **Python چیست؟**

پایتون یک زبان برنامه‌نویسی ساده، خوانا و چندمنظوره است که برای توسعه وب، هوش مصنوعی، علوم داده، خودکارسازی وظایف، و بسیاری از کاربردهای دیگر استفاده می‌شود.

## **مفسر (Interpreter) چیست؟**

مفسر یک برنامه است که کد پایتون را خط‌به‌خط اجرا می‌کند. برخلاف زبان‌هایی مثل C++ که نیاز به کامپایل دارند، پایتون مستقیماً توسط مفسر اجرا می‌شود.

## **IDE چیست؟**

IDE (محیط توسعه یکپارچه) برنامه‌ای است که امکاناتی مثل ویرایش کد، اشکال‌زدایی (Debugging)، اجرا و مدیریت پروژه را فراهم می‌کند.



## راهنمای نصب پایتون و PyCharm

در ادامه، راهنمای نصب پایتون و PyCharm را برای شما آماده کرده‌ام
اما اگر اموزش برای شما نامفهوم بود، میتوانید به وبسایت مکتب خونه مراحعه کنید:
https://maktabkhooneh.org/mag/learning-how-to-code-with-pycharm/

---

### نصب پایتون

1. **دانلود پایتون**:
   - به وب‌سایت رسمی پایتون مراجعه کنید: [python.org](https://www.python.org/).
   - به بخش **Downloads** بروید و آخرین نسخه پایتون را برای سیستم عامل خود دانلود کنید (معمولاً به صورت خودکار نسخه مناسب پیشنهاد می‌شود).

2. **نصب پایتون**:
   - فایل نصبی دانلود شده را اجرا کنید.
   - در صفحه اول، گزینه **Add Python to PATH** را حتما انتخاب کنید.
   - روی **Install Now** کلیک کنید تا نصب شروع شود.
   - پس از اتمام نصب، می‌توانید با باز کردن ترمینال یا Command Prompt و تایپ کردن `python --version` از نصب موفقیت‌آمیز پایتون اطمینان حاصل کنید.

---

### نصب PyCharm

1. **دانلود PyCharm**:
   - به وب‌سایت JetBrains مراجعه کنید: [jetbrains.com/pycharm](https://www.jetbrains.com/pycharm/).
   - نسخه **Community** (رایگان) یا **Professional** (پولی) را دانلود کنید. برای شروع، نسخه Community کافی است.

2. **نصب PyCharm**:
   - فایل نصبی دانلود شده را اجرا کنید.
   - مراحل نصب را دنبال کنید و تنظیمات پیش‌فرض را بپذیرید.
   - پس از نصب، PyCharm را باز کنید.

3. **پیکربندی PyCharm**:
   - هنگام اولین اجرا، PyCharm از شما می‌پرسد که آیا می‌خواهید تنظیمات پیش‌فرض را بارگذاری کنید یا تنظیمات جدید ایجاد کنید. اگر تازه‌کار هستید، گزینه **Do not import settings** را انتخاب کنید.
   - در مرحله بعد، می‌توانید تم و رنگ‌بندی مورد نظر خود را انتخاب کنید.
   - پس از آن، PyCharm آماده استفاده است.

---

### ایجاد یک پروژه جدید در PyCharm

1. **باز کردن PyCharm**.
2. **ایجاد پروژه جدید**:
   - روی **New Project** کلیک کنید.
   - در پنجره باز شده، نام پروژه و محل ذخیره‌سازی آن را مشخص کنید.
   - در بخش **Interpreter**، مطمئن شوید که مفسر پایتون به درستی انتخاب شده است (معمولاً به صورت خودکار تشخیص داده می‌شود).
   - روی **Create** کلیک کنید.

3. **ایجاد فایل پایتون**:
   - در پنجره پروژه، روی پوشه پروژه راست‌کلیک کنید و **New > Python File** را انتخاب کنید.
   - نام فایل را وارد کنید (مثلاً `main.py`) و Enter بزنید.

4. **نوشتن و اجرای کد**:
   - کد خود را در فایل ایجاد شده بنویسید.
   - برای اجرای کد، روی فایل راست‌کلیک کنید و **Run** را انتخاب کنید یا از کلیدهای ترکیبی `Shift + F10` استفاده کنید.