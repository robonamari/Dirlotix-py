<div align="center">

[**🇺🇸 English**](README.md)
</div>

<p align="center">
    <img src="https://img.shields.io/github/languages/code-size/robonamari/Dirlotix-py?style=flat" alt="Code Size">
    <img src="https://tokei.rs/b1/github/robonamari/Dirlotix-py?style=flat" alt="Total lines">
    <img src="https://img.shields.io/badge/python-%5E3.7-blue" alt="Python Versions">
    <img src="https://img.shields.io/github/license/robonamari/Dirlotix-py" alt="GitHub license">
</p>

---

این پروژه یک برنامه مدیریت فایل تحت وب است که با Python و Flask ساخته شده است. این برنامه به کاربران امکان می دهد تا فایل های موجود در سرور را مرور و دانلود کنند، لیست دایرکتوری ها را مشاهده کنند و با انواع مختلف فایل ها تعامل داشته باشند. همچنین، این برنامه از قابلیت چندزبانه پشتیبانی می کند و به کاربران اجازه می دهد تنظیمات مختلفی مانند رنگ های تم، فونت ها و فاوآیکن را پیکربندی کنند.

## ویژگی ها  
- مرور و مشاهده فایل ها و دایرکتوری ها.  
- پشتیبانی از انواع مختلف فایل ها (تصاویر، ویدئوها، صدا، متن، PDF و موارد دیگر).  
- جستجو و مرتب سازی فایل ها بر اساس نام، اندازه یا تاریخ آخرین تغییر.  
- پشتیبانی از چندین زبان با بارگذاری داینامیک از طریق فایل های YAML (بر اساس استاندارد ISO 639-1، شامل تقریباً 136 زبان) (به زودی).  
- قابلیت تنظیم رنگ های تم، فونت ها و فاوآیکن.  
- مدیریت خطاها و ریدایرکت برای خطاهای مختلف HTTP.

## تنظیمات میزبانی شخصی
<details>
<summary>4 مرحله برای میزبانی Dirlotix-py روی سرور شخصی</summary>

### 1. کلون کردن مخزن
```bash
git clone https://github.com/robonamari/Dirlotix-py
```

### 2. نصب پایتون و وابستگی ها  
پایتون 3.7 یا بالاتر را نصب کنید، سپس وابستگی های مورد نیاز را نصب کنید:
```bash
pip install -r requirements.txt
```

### 3. تنظیم اسکریپت  
1. نام **.env.example** را به **.env** تغییر دهید.  
2. توضیحات کامل متغیرهای محیطی داخل فایل `.env` نوشته شده اند، آن ها را مطابق نیاز تکمیل کنید.  

### 4. اجرای اسکریپت
```bash
python index.py
```

### انجام شد!  
اسکریپت شما باید به طور کامل تنظیم شده و آماده اجرا باشد!

</details>
