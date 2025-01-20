# Persian Language Support for Laravel (v5.8 - v11)

This package provides Persian translations for Laravel framework versions 5.8 to 11.

## Supported Versions

- Laravel 5.8.\*
- Laravel 6.\*
- Laravel 7.\*
- Laravel 8.\*
- Laravel 9.\*
- Laravel 10.\*
- Laravel 11.\*

---

## What's Included

The package contains translation files for both JSON and PHP arrays:

```text
laravel/
└── resources/
    └── lang/
        ├── fa.json
        └── fa/
            ├── auth.php
            ├── pagination.php
            ├── passwords.php
            └── validation.php
```

---

## Installation and Usage

### Steps

1. Copy the `fa.json` file and the `fa` directory from this package to your Laravel project's `\resources\lang` directory:
   ```text
   your-laravel-project/
   └── resources/
       └── lang/
           ├── fa.json
           └── fa/
   ```

2. Open the `config/app.php` file in your Laravel project and update the locale setting:
   ```php
   'locale' => 'en',
   ```
   Change it to:
   ```php
   'locale' => 'fa',
   ```

3. You're all set! Your Laravel application will now use Persian translations for built-in messages and validation errors.

---

## Special Note for Laravel 10 and 11

For Laravel versions 10 and 11, you must first publish the language files using the following Artisan command:

```bash
php artisan lang:publish
```

This will create a directory structure similar to the following:

```text
laravel/
└── lang/
    ├── fa.json
    └── fa/
        ├── auth.php
        ├── pagination.php
        ├── passwords.php
        └── validation.php
```

The `fa.json` file is ideal for translating the entire application quickly.

---

<div dir="rtl">

## نحوه استفاده

1. ابتدا فایل `fa.json` و پوشه `fa` این پکیج را به دایرکتوری `\resources\lang` پروژه لاراولی خود کپی کنید:
   ```text
   your-laravel-project/
   └── resources/
       └── lang/
           ├── fa.json
           └── fa/
   ```

2. فایل `app.php` در مسیر `\config` را باز کرده و مقدار `'locale' => 'en'` را به `'locale' => 'fa'` تغییر دهید.

3. تبریک! پیام‌ها و ارورهای لاراول شما به زبان فارسی نمایش داده می‌شوند.

-- **نکته:** برای لاراول نسخه 10 و 11، ابتدا فایل‌های زبان را با دستور Artisan زیر منتشر کنید:
   ```bash
   php artisan lang:publish
   ```

   ساختار فایل‌ها پس از انتشار:
   ```text
   laravel/
   └── lang/
       ├── fa.json
       └── fa/
           ├── auth.php
           ├── pagination.php
           ├── passwords.php
           └── validation.php
   ```

</div>
