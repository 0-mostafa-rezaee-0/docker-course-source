![alt text](images/thumbnail.png)

# Docker Tutorial (Persian)

This repository contains the Dockerfiles and related resources used throughout the course which is available on my YouTube channel at [Silicium with Mehran Tarif](https://www.youtube.com/playlist?list=PLAt10Vana3Ye_xFzq-whnnOhPsHQe1NDX). The course covers the fundamentals of Docker, including:

<div dir="rtl" align="right">

- **۰۰** - آموزش داکر - داکر چیست و به چه دردی میخوره؟ (7:36)  
- **۰۱** - تفاوت داکر با ماشین مجازی - داکر چطوری کار می کنه؟ (7:23)  
- **۰۲** - نصب و کانفیگ داکر بر روی لینوکس (5:23)  
- **۰۳** - نصب و کانفیگ داکر بر روی ویندوز (7:55)  
- **۰۴** - ثبت نام در Docker Hub و لاگین با Docker و کاهش محدودیت دانلود ایمیج (4:42)  
- **۰۵** - دانلود ایمیج Nginx و ران کردنش (8:30)  
- **۰۶** - تنظیم پورت در داکر (3:24)  
- **۰۷** - اجرای دستورات با کانتینرها، اجرای شل (4:45)  
- **۰۸** - آشنایی با Volume - اشتراک گذاری، ذخیره سازی و بک‌آپ دیتای کانتینر (8:02)  
- **۰۹** - نکات مبتدی باقی‌مانده: حذف کانتینر و ایمیج، ذخیره و لود ایمیج، نسخه‌های سبک‌تر مثل آلپاین و ... (12:19)  
- **۱۰** - آشنایی با Dockerfile - ساخت ایمیج‌های جدید (5:46)  
- **۱۱** - آشنایی به Docker Compose (5:09)  
- **۱۲** - داکرایز کردن یه وبسایت Static و نوشتن اولین Dockerfile (12:51)  
- **۱۳** - نوشتن اولین Docker Compose مون و اجرای کانتینر (8:08)  
- **۱۴** - داکرایز کردن یه پروژه ساده Flask (1) (17:12)  
- **۱۵** - داکرایز کردن یه پروژه ساده Flask (2) (10:01)  
- **۱۶** - داکرایز کردن Django با Gunicorn و Nginx و MariaDB و Volumes و ... (7:12)  
- **۱۷** - تنظیمات مهم پروژه Django برای داکرایز کردنش (15:32)  
- **۱۸** - نوشتن Dockerfile اپ و تنظیم Volume هاش (12:03)  
- **۱۹** - تنظیم Nginx و سرو کردن Static و Media (5:37)  
- **۲۰** - تنظیم دیتابیس MariaDB برای استفاده در پروژه‌مون (15:27)  
- **۲۱** - توالی اجرای کانتینرها (حل مشکل اجرای App قبل از MariaDB) (13:12)  
- **۲۲** - داکرایز کردن وردپرس با LAMP (PHP و Apache و MySQL) (17:14)  
- **۲۳** - داکرایز کردن Node.js و دیتابیس Mongo (آماده‌سازی پروژه) (12:42)  
- **۲۴** - داکرایز کردن Node.js و دیتابیس Mongo (نوشتن Docker Compose) (9:53)  

</div>

## Repository Folders

```
.
├── E12
│   └── themes
│       ├── css
│       ├── images
│       │   ├── background
│       │   ├── gallery
│       │   ├── icon
│       │   ├── news
│       │   ├── speakers
│       │   └── sponsors
│       ├── js
│       └── plugins
│           ├── bootstrap
│           ├── font-awsome
│           │   ├── css
│           │   └── fonts
│           ├── google-map
│           │   └── images
│           ├── jquery
│           ├── magnific-popup
│           ├── shuffle
│           ├── slick
│           │   └── fonts
│           └── syotimer
├── E13
│   └── themes
│       ├── css
│       ├── images
│       │   ├── background
│       │   ├── gallery
│       │   ├── icon
│       │   ├── news
│       │   ├── speakers
│       │   └── sponsors
│       ├── js
│       └── plugins
│           ├── bootstrap
│           ├── font-awsome
│           │   ├── css
│           │   └── fonts
│           ├── google-map
│           │   └── images
│           ├── jquery
│           ├── magnific-popup
│           ├── shuffle
│           ├── slick
│           │   └── fonts
│           └── syotimer
├── E14
│   ├── app
│   └── nginx
├── E15
│   ├── app
│   └── nginx
├── E16
├── E17
│   └── source
│       ├── app
│       │   ├── config
│       │   │   └── __pycache__
│       │   └── web
│       │       └── __pycache__
│       ├── media
│       └── static
│           └── admin
│               ├── css
│               │   └── vendor
│               │       └── select2
│               ├── fonts
│               ├── img
│               │   └── gis
│               └── js
│                   ├── admin
│                   └── vendor
│                       ├── jquery
│                       ├── select2
│                       │   └── i18n
│                       └── xregexp
├── E18
│   └── source
│       ├── app
│       ├── nginx
│       └── volumes
│           ├── app
│           │   ├── config
│           │   │   └── __pycache__
│           │   └── web
│           │       └── __pycache__
│           ├── media
│           └── static
│               └── admin
│                   ├── css
│                   │   └── vendor
│                   │       └── select2
│                   ├── fonts
│                   ├── img
│                   │   └── gis
│                   └── js
│                       ├── admin
│                       └── vendor
│                           ├── jquery
│                           ├── select2
│                           │   └── i18n
│                           └── xregexp
├── E19
│   └── source
│       ├── app
│       ├── nginx
│       └── volumes
│           ├── app
│           │   ├── config
│           │   │   └── __pycache__
│           │   └── web
│           │       └── __pycache__
│           ├── media
│           └── static
│               └── admin
│                   ├── css
│                   │   └── vendor
│                   │       └── select2
│                   ├── fonts
│                   ├── img
│                   │   └── gis
│                   └── js
│                       ├── admin
│                       └── vendor
│                           ├── jquery
│                           ├── select2
│                           │   └── i18n
│                           └── xregexp
├── E20
│   └── source
│       ├── app
│       ├── nginx
│       └── volumes
│           ├── app
│           │   ├── config
│           │   │   └── __pycache__
│           │   └── web
│           │       └── __pycache__
│           ├── media
│           └── static
│               └── admin
│                   ├── css
│                   │   └── vendor
│                   │       └── select2
│                   ├── fonts
│                   ├── img
│                   │   └── gis
│                   └── js
│                       ├── admin
│                       └── vendor
│                           ├── jquery
│                           ├── select2
│                           │   └── i18n
│                           └── xregexp
├── E21
│   └── source
│       ├── app
│       ├── nginx
│       └── volumes
│           ├── app
│           │   ├── config
│           │   │   └── __pycache__
│           │   └── web
│           │       └── __pycache__
│           ├── media
│           └── static
│               └── admin
│                   ├── css
│                   │   └── vendor
│                   │       └── select2
│                   ├── fonts
│                   ├── img
│                   │   └── gis
│                   └── js
│                       ├── admin
│                       └── vendor
│                           ├── jquery
│                           ├── select2
│                           │   └── i18n
│                           └── xregexp
├── E22
│   └── source
├── E23
│   └── source
│       └── blog-app-master
├── E24
│   └── source
│       └── app
│           └── app
└── images

192 directories

```