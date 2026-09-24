# ✈️ جانمون — Telegram Flight Bot (n8n)

ربات تلگرامی برای پیدا کردن ارزان‌ترین بلیط هواپیما در ۳ روز آینده.
کاربر مبدأ و مقصد را می‌گوید، ربات ارزان‌ترین پروازها را پیدا می‌کند و با دکمه «لینک خرید» کاربر را به صفحه‌ی همان پرواز در سایت فروش می‌برد.

> ربات بلیط نمی‌فروشد؛ فقط جست‌وجو می‌کند. پروژه‌ی آموزشی/نمونه‌کار برای ساخت ربات و خودکارسازی با n8n.

## Features
- 🔎 جست‌وجوی ارزان‌ترین پرواز داخلی و خارجی (از/به ایران)
- 📅 بازه‌ی ۳ روز آینده
- 💬 رابط کاربری تلگرام
- 🔗 دکمه‌ی لینک خرید

## Stack
n8n · Telegram Bot API · HTTP Request · Code node (JavaScript)

## Setup
1. در n8n: **Workflows → Import from file** و فایل `janemoon-flight-bot.workflow.json` را انتخاب کنید.
2. از [@BotFather](https://t.me/BotFather) یک توکن بسازید.
3. در نود **Config** مقدار `YOUR_TELEGRAM_BOT_TOKEN` را با توکن خودتان عوض کنید و credential تلگرام را در نودهای Telegram وصل کنید.
4. Workflow را Activate کنید.

⚠️ توکن واقعی را هرگز داخل ریپو commit نکنید.

## Author
Mahdi Jalambadani — [@Mehdi-777](https://github.com/Mehdi-777)
