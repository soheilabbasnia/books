<div dir="rtl">

# کتابخانه دیجیتال علم داده و برنامه‌نویسی (Books)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Category: Books & Guides](https://img.shields.io/badge/Category-Books%20%26%20Reference-purple.svg)](#)
[![Topic: Data Science & AI](https://img.shields.io/badge/Topic-Data_Science_%26_AI-orange.svg)](#)
[![Format: PDF Books](https://img.shields.io/badge/Format-PDF_Books-critical.svg)](#)

[English](README.md) | فارسی

مجموعه‌ای دست‌چین‌شده، سازمان‌یافته و کاربردی از کتاب‌های مرجع، دستورالعمل‌های فنی، برگه‌های تقلب (Cheat Sheets) و نقشه‌های راه شغلی در زمینه‌های **علم داده (Data Science)**، **یادگیری ماشین (Machine Learning)**، **یادگیری عمیق (Deep Learning)**، **آمار و احتمال**، **پایتون** و **پایگاه‌داده SQL**.

---

## نمای کلی پروژه

مسیر یادگیری و تسلط بر شاخه‌های مدرن علم داده و مهندسی هوش مصنوعی نیازمند دسترسی به منابع معتبر و استاندارد است. این مخزن به عنوان یک آرشیو جامع و طبقه‌بندی‌شده از منابع آموزشی برای یادگیری شخصی و بهره‌برداری توسعه‌دهندگان و پژوهشگران گردآوری شده است.

نکات برجسته:
- **دسته‌بندی موضوعی دقیق:** تفکیک منابع بر اساس شاخه‌های تخصصی (تحلیل داده، یادگیری عمیق، EDA، پکیج‌های پایتون، آمار، دیتابیس و رودمپ‌ها).
- **تمرکز بر یادگیری کاربردی و پروژه‌محور:** شامل کتاب‌های دستورالعمل (Cookbook)، آموزش‌های عملی و خلاصه فرمول‌ها.
- **نقشه‌های راه شغلی (Roadmaps):** راهنمای بصری مهارت‌های لازم برای مسیرهای شغلی مهندس هوش مصنوعی، دانشمند داده، متخصص بینایی ماشین و مهندس کلان‌داده.

---

## جدول دسته‌بندی کتابخانه

| دسته‌بندی | موضوعات و مباحث پوشش‌داده‌شده | آثار و منابع شاخص |
| :--- | :--- | :--- |
| [`data-analysis`](data-analysis/) | جمع‌آوری داده‌ها، تمیزکاری، تحلیل پیشرفته و بصری‌سازی با پایتون | *Hands-On Data Analysis with Pandas* |
| [`deep-learning`](deep-learning/) | معماری شبکه‌های عصبی عمیق، بینایی ماشین، فریم‌ورک‌های FastAI و PyTorch | *Deep Learning for Coders with Fastai and PyTorch* |
| [`eda`](eda/) | تحلیل اکتشافی داده‌ها، تحلیل و پیش‌بینی سری‌های زمانی، داده‌کاوی | *Hands-On Exploratory Data Analysis with Python*, *Practical Time Series Analysis* |
| [`python-packages`](python-packages/) | مصورسازی با Matplotlib، کار با پانداس، محاسبات علمی | *Pandas Cookbook*, *Hands-On Matplotlib*, *Learning Pandas* |
| [`statistics`](statistics/) | احتمال، آمار توصیفی و استنباطی، خلاصه فرمول‌ها، آمار کاربردی برای ماشین لرنینگ | *Statistics for Data Science*, *Statistics for Machine Learning*, چیت‌شیت‌های آماری |
| [`sql`](sql/) | کوئری‌نویسی تحلیلی پایگاه‌داده، مفاهیم رابطه‌ای، SQL برای علم داده | *SQL for Data Science* |
| [`roadmap`](roadmap/) | مهارت‌های گام‌به‌گام برای موقعیت‌های شغلی مختلف دیتا | هوش مصنوعی، یادگیری ماشین، بینایی ماشین، دیتا ساینس، کلان‌داده |

---

## نحوه دریافت و استفاده

### کلون کردن کامل مخزن

جهت دانلود تمامی کتاب‌ها و منابع:
```bash
git clone https://github.com/soheilabbasnia/books.git
cd books
```

### دانلود پوشه مشخص با قابلیت Sparse-Checkout

اگر تنها به یک پوشه مشخص (مانند نقشه‌های راه یا آمار) نیاز دارید:
```bash
git clone --filter=blob:none --no-checkout https://github.com/soheilabbasnia/books.git
cd books
git sparse-checkout init --cone
git sparse-checkout set roadmap statistics
git checkout main
```

---

## ساختار پوشه‌های مخزن

```text
books/
├── data-analysis/          # کتاب‌های تخصصی تحلیل داده و کار با کتابخانه‌ها
├── deep-learning/          # آموزش‌های شبکه‌های عصبی و یادگیری عمیق
├── eda/                    # کتاب‌های تحلیل اکتشافی و سری‌های زمانی
├── python-packages/        # آموزش‌های جامع پانداس و مت‌پلات‌لیب
├── roadmap/                # نقشه‌های راه گرافیکی مهارت‌های هوش مصنوعی و دیتا
├── sql/                    # آموزش‌های کاربردی SQL برای تحلیلگران
├── statistics/             # مبانی آمار و احتمال، فرمول‌ها و چیت‌شیت‌ها
├── rename-app.py           # اسکریپت پایتون برای نام‌گذاری استاندارد فایل‌ها
├── LICENSE                 # مجوز مخزن
└── README.md               # مستندات انگلیسی
```

---

## مشارکت

پیشنهاد افزودن کتاب‌های باکیفیت و به‌روزرسانی نقشه‌های راهواره مورد استقبال است!

1. مخزن را فورک کنید.<br>
2. یک شاخه جدید بسازید (`git checkout -b suggest/new-resource`).<br>
3. تغییرات خود را کامیت کنید (`git commit -m "Add new feature"`).<br>
4. تغییرات را به شاخه خود پوش نمایید (`git push origin suggest/new-resource`).<br>
5. یک Pull Request باز کنید.

---

## مجوز (License)

ساختار طبقه‌بندی و اسکریپت‌های موجود در این مخزن تحت مجوز [MIT License](LICENSE) منتشر شده‌اند.
حقوق نشر کتاب‌ها متعلق به نویسندگان و ناشران مربوطه است.

</div>

