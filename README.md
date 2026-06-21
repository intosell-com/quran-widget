# Quran Random Image Widget

ویجت فوق‌مدرن نمایش تصادفی پوسترهای قرآنی به صورت عکس.

این پروژه با فایل متنی `quran.txt` کار می‌کند. هر خط این فایل یک آدرس مستقیم تصویر است و برنامه در هر بار بارگذاری، یکی از تصاویر را تصادفی نمایش می‌دهد.

## فایل‌ها

- `index.html`: صفحه اصلی، پیش‌نمایش و کد اشتراک‌گذاری
- `embed.html`: نسخه سبک مخصوص نمایش داخل سایت‌های دیگر
- `widget.js`: اسکریپت اشتراک‌گذاری برای سایت‌ها و وبلاگ‌ها
- `app.js`: منطق خواندن `quran.txt` و نمایش تصادفی تصویر
- `styles.css`: طراحی فوق‌مدرن و واکنش‌گرا
- `quran.txt`: فهرست آدرس تصاویر آیات

## انتشار روی GitHub Pages

1. یک مخزن جدید در GitHub بسازید.
2. همه فایل‌ها را در ریشه مخزن آپلود کنید.
3. از بخش Settings > Pages، شاخه اصلی را برای انتشار انتخاب کنید.
4. پس از فعال شدن Pages، آدرس سایت شما شبیه این خواهد بود:

```text
https://USERNAME.github.io/REPOSITORY/
```

## کد استفاده در سایت‌های دیگر

```html
<script src="https://USERNAME.github.io/REPOSITORY/widget.js" data-quran-widget></script>
```

## کد جایگزین iframe

```html
<iframe src="https://USERNAME.github.io/REPOSITORY/embed.html" style="width:100%;max-width:900px;height:470px;border:0;border-radius:34px;overflow:hidden" loading="lazy"></iframe>
```

## تنظیمات اختیاری اسکریپت

```html
<script
  src="https://USERNAME.github.io/REPOSITORY/widget.js"
  data-quran-widget
  data-height="470"
  data-max-width="900px"
  data-radius="34px">
</script>
```

## منبع و پشتیبان

در قالب، لینک «منبع و پشتیبان: قرآن» به صفحه پوسترهای قرآنی Intosell اضافه شده است.
