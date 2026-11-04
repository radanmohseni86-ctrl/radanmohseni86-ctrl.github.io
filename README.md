<div dir="rtl">

# جزوه‌های من

صفحه‌ی اصلی جزوه‌ها؛ از اینجا به هر جزوه می‌روید.

**آدرس:** https://radanmohseni86-ctrl.github.io/

## اضافه کردن جزوه‌ی جدید

۱. جزوه را روی GitHub Pages منتشر کنید (در مخزن همان جزوه: Settings ← Pages).

۲. یک تصویر از صفحه‌ی اصلی جزوه با نسبت ۱۶ به ۱۰ (مثلاً ۹۶۰×۶۰۰) در پوشه‌ی `thumbs/` بگذارید.

۳. در فایل `index.html` یک مورد به فهرست داخل `<script type="application/json" id="projects">` اضافه کنید:

</div>

```json
{
  "title": "نام جزوه",
  "description": "یک یا دو جمله درباره‌ی جزوه",
  "url": "https://radanmohseni86-ctrl.github.io/REPO/",
  "repo": "https://github.com/radanmohseni86-ctrl/REPO",
  "image": "thumbs/REPO.webp",
  "tags": ["برچسب ۱", "برچسب ۲"]
}
```
