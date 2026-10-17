# Steganography Suite

**Advanced LSB Steganography and Encryption Tool for Android**

Version: 2.3  
Developer: CyberH4XOR  
Platform: Android (API 21+)

---

## [ ENGLISH ]

### Overview

Steganography Suite is a professional-grade utility designed for concealing sensitive data within raster images using the Least Significant Bit (LSB) technique. The application provides an advanced security layer by combining data embedding with industry-standard cryptography.

### Core Features

- **Data Embedding:** Conceal text or arbitrary files within PNG images.
- **Cryptography:** AES-256-GCM authenticated encryption for maximum confidentiality.
- **Integrity Verification:** HMAC-SHA256 signatures to ensure payloads have not been tampered with.
- **Redundant Bit-Spreading:** Evenly distributes payload bits across the entire image to minimize statistical anomalies.
- **Steganalysis:** Built-in statistical analysis (Chi-Square, Entropy, Runs Test, RS Analysis) to detect hidden data.
- **Bilingual Interface:** Full support for English and Persian (Farsi).
- **Modern UI:** Dark theme with glassmorphism elements.
- **Offline Operation:** 100% of processing occurs locally on the device. No network requests are made.

### Usage Instructions

**1. Encoding (Hide Data)**
- Navigate to the "Encode" tab.
- Select a carrier image (PNG or JPG).
- Input the text or select a file to hide.
- (Optional) Provide a strong password for encryption.
- Tap "Encode & Download". The output is saved as a `_stego.png` file.

**2. Decoding (Extract Data)**
- Navigate to the "Decode" tab.
- Select the stego image (must be the exact PNG produced by this tool).
- Enter the password if encryption was used.
- Tap "Extract" to reveal the hidden payload.

**3. Analysis (Steganalysis)**
- Navigate to the "Analyze" tab.
- Select an image.
- Run the analysis to view statistical metrics and determine the likelihood of hidden data.

### Technical Specifications

| Parameter | Specification |
|-----------|---------------|
| Embedding Algorithm | LSB (RGB channels) |
| Encryption | AES-256-GCM |
| Key Derivation | PBKDF2-HMAC-SHA256 (210,000 iterations) |
| Integrity Check | HMAC-SHA256 |
| Output Format | PNG (Lossless) |
| Minimum Android Version | 5.0 (API 21) |

### Limitations

- Output must be saved as PNG. JPEG compression destroys LSB data.
- Resizing or cropping the stego image will corrupt the payload.
- Maximum payload capacity is calculated as `Width × Height × 3 / 8` bytes.

### Security Notice

All operations are performed offline. The developer assumes no responsibility for the misuse of this tool. Always use strong passwords for sensitive data.

---

## [ PERSIAN / فارسی ]

### معرفی برنامه

استگانوگرافی سوئیت (Steganography Suite) یک ابزار حرفه‌ای برای پنهان‌سازی اطلاعات در تصاویر با استفاده از تکنیک بیت کم‌ارزش (LSB) است. این برنامه با ترکیب جاسازی داده و رمزنگاری استانداردهای صنعتی، لایه‌ای پیشرفته از امنیت را فراهم می‌کند.

### امکانات اصلی

- **جاسازی داده:** پنهان‌سازی متن یا هر نوع فایلی در تصاویر PNG.
- **رمزنگاری:** استفاده از الگوریتم AES-256-GCM برای محرمانگی حداکثری.
- **تأیید یکپارچگی:** امضای دیجیتال HMAC-SHA256 برای اطمینان از عدم دستکاری داده‌ها.
- **پخش تصادفی بیت‌ها:** توزیع یکنواخت بیت‌های داده در کل تصویر برای کاهش ناهنجاری‌های آماری.
- **تحلیل استگانوگرافی:** ابزارهای آماری داخلی (Chi-Square, Entropy, Runs Test, RS Analysis) برای شناسایی داده‌های پنهان.
- **رابط کاربری دوزبانه:** پشتیبانی کامل از زبان‌های انگلیسی و فارسی.
- **ظاهر مدرن:** تم تاریک با المان‌های شیشه‌ای (Glassmorphism).
- **عملکرد آفلاین:** تمامی پردازش‌ها به صورت محلی روی دستگاه انجام می‌شود و هیچ داده‌ای به سرور ارسال نمی‌گردد.

### راهنمای استفاده

**۱. رمزنگاری (پنهان‌سازی داده)**
- به تب "رمزنگاری" بروید.
- یک تصویر میزبان (PNG یا JPG) انتخاب کنید.
- متن مورد نظر را وارد کرده یا یک فایل انتخاب کنید.
- (اختیاری) یک رمز عبور قوی وارد کنید.
- دکمه "رمزنگاری و دانلود" را بزنید. خروجی با نام `_stego.png` ذخیره می‌شود.

**۲. استخراج (بازیابی داده)**
- به تب "استخراج" بروید.
- تصویر استگو (باید دقیقاً همان فایل PNG تولیدشده باشد) را انتخاب کنید.
- در صورت رمزنگاری، رمز عبور را وارد کنید.
- دکمه "استخراج" را بزنید تا محتوای پنهان نمایش داده شود.

**۳. تحلیل (استگانالیز)**
- به تب "تحلیل" بروید.
- یک تصویر انتخاب کنید.
- تحلیل را اجرا کنید تا شاخص‌های آماری و احتمال وجود داده پنهان را مشاهده کنید.

### مشخصات فنی

| پارامتر | مشخصات |
|---------|---------|
| الگوریتم جاسازی | LSB (کانال‌های RGB) |
| رمزنگاری | AES-256-GCM |
| مشتق‌سازی کلید | PBKDF2-HMAC-SHA256 (۲۱۰,۰۰۰ تکرار) |
| تأیید یکپارچگی | HMAC-SHA256 |
| فرمت خروجی | PNG (بدون اتلاف) |
| حداقل نسخه اندروید | ۵.۰ (API 21) |

### محدودیت‌ها

- خروجی باید حتماً به فرمت PNG ذخیره شود. فشرده‌سازی JPEG داده‌های LSB را از بین می‌برد.
- تغییر اندازه یا برش تصویر استگو، محتوای پنهان را خراب می‌کند.
- حداکثر ظرفیت داده برابر است با `عرض × ارتفاع × 3 / 8` بایت.

### هشدار امنیتی

تمام عملیات به صورت آفلاین انجام می‌شود. توسعه‌دهنده هیچ مسئولیتی در قبال استفاده نادرست از این ابزار نمی‌پذیرد. همواره برای داده‌های حساس از رمز عبور قوی استفاده کنید.

---

## Developer Contact

- GitHub: [Insert GitHub URL]
- Telegram: [Insert Telegram ID]
- Email: [Insert Email Address]

## License

This project is licensed under the GNU General Public License v3.0 (GPL-3.0).
You are free to use, modify, and distribute this software, provided that any derivative work is also open-source under the same license.
