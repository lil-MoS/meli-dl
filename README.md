# ⚡ Meli-Action

> مجموعه ابزارهای دانلود خودکار با GitHub Actions | بدون نیاز به سرور | بدون فیلترشکن

[![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-دانلود%20خودکار-2088FF?style=flat-square&logo=github-actions&logoColor=white)](https://github.com/features/actions)
[![Fork](https://img.shields.io/badge/🚀%20فورک%20رایگان-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/melioffice/meli-action/fork)
[![License](https://img.shields.io/badge/مجوز-MIT-FFD43B?style=flat-square)](LICENSE)

---

## 🎯 قابلیت‌ها

| سرویس | قابلیت |
|-------|--------|
| 🎬 **YouTube** | ویدیو (720p/1080p/4K) • MP3 • لیست پخش • زیرنویس • SponsorBlock |
| 🎵 **Spotify / SoundCloud** | MP3/FLAC • کیفیت 320kbps |
| 📱 **Google Play** | دانلود APK • ادغام Split APK |
| 💬 **Telegram** | دانلود فایل • ادامه دانلود |
| 🔗 **لینک مستقیم** | هر فایلی • رمزگذاری ZIP |
| 📄 **سایر** | ذخیره صفحه وب (MHTML) • اسکرین‌شات |

---

## 🚀 نحوه استفاده (۳ مرحله)
🔘 کلیک روی دکمه Fork در بالای صفحه

⚙️ رفتن به تب Actions → انتخاب ابزار → Run workflow

📥 دریافت فایل از پوشه downloads/ یا Releases



### مثال سریع:
```yaml
ورودی:
  URL: https://youtu.be/...
  کیفیت: 1080p
  روش: repository

خروجی:
  → downloads/video.mp4
⚙️ تنظیمات (اختیاری)
افزودن کوکی یوتیوب (برای ویدیوهای سن‌دار):


Settings → Secrets → Actions → YT_COOKIES
تغییر حداکثر حجم هر قسمت:

فیلد max_part_mb → مقدار 90 تا 1900 مگابایت

🌐 چرا بدون فیلترشکن؟
تمام درخواست‌ها از سرورهای GitHub (آمریکا/اروپا) ارسال می‌شوند.

📊 محدودیت‌ها
مورد	مقدار
زمان اجرا	45-60 دقیقه
حجم توصیه‌شده	زیر 2 گیگ
فضای ریپو	1 گیگ (رایگان)
🤝 مشارکت
فورک کنید، تغییرات را اعمال کنید و Pull Request بزنید.

📞 ارتباط
GitHub • LiL-MoS

<div align="center">
⭐ اگر مفید بود، ستاره دهید ⭐

🇮🇷 ساخته شده در ایران

</div> ```
