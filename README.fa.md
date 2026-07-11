<div dir="rtl" align="right">

<div align="center">

# استارتر سرویس اتوماسیون

**سرویس Production-capable پایتون برای Webhook، کار زمان‌بندی‌شده، Queue، اتصال سرویس‌ها و اتوماسیون پس‌زمینه.**

[![Use this template](https://img.shields.io/badge/Use%20this%20template-2ea44f?logo=github&logoColor=white)](https://github.com/easy-starter/easy-starter-automation-service/generate) [![CI](https://github.com/easy-starter/easy-starter-automation-service/actions/workflows/ci.yml/badge.svg)](https://github.com/easy-starter/easy-starter-automation-service/actions/workflows/ci.yml) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) ![Status: foundation](https://img.shields.io/badge/status-foundation-orange) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

[مستندات](https://github.com/easy-starter/easy-starter-docs) · [گزارش مشکل](https://github.com/easy-starter/easy-starter-automation-service/issues/new/choose)

</div>

> [!IMPORTANT]
> این ریپوزیتوری در مرحله‌ی **Foundation** است. تا انتشار اولین نسخه‌ی پایدار، آن را Production-ready در نظر نگیرید.

## چه مشکلی را حل می‌کند؟

اسکریپت‌های شکننده و پروژه‌های صرفاً Cron را با سرویسی ساختاریافته، قابل‌مشاهده و Retry-safe جایگزین می‌کند که همراه محصول رشد می‌کند.

## این تمپلیت برای چه پروژه‌هایی مناسب است؟

- دریافت Webhook و سرویس Integration
- گزارش زمان‌بندی‌شده و همگام‌سازی
- پردازش فایل یا داده در پس‌زمینه
- اتوماسیون اعلان و Workflow
- سرویس عملیاتی کوچک با پنل ادمین

**مناسب این موارد نیست:** مجموعه‌ای از اسکریپت‌های بدون مالک یا پلتفرم Microservice توزیع‌شده نیست.

## امکانات پایه

- مرز اپلیکیشن HTTP/Webhook
- پایه‌ی Scheduler و Background Worker
- قراردادهای Retry، Idempotency، Timeout و Dead-letter
- دیتابیس، Cache، Logging، Metrics و Health Check
- Docker، تست، CI و Runbook پروداکشن

توضیحات جزئی معماری، قراردادها، پروفایل‌های استقرار و روش توسعه در [`docs/`](docs/) قرار می‌گیرند. توسعه‌ی فیچر از [`specs/`](specs/) شروع می‌شود و قوانین ایجنت‌ها در [`AGENTS.md`](AGENTS.md) نگهداری می‌شوند.

## شروع سریع

۱. روی **Use this template** بزنید یا فرمان زیر را اجرا کنید:

```bash
gh repo create my-project --template easy-starter/easy-starter-automation-service --private --clone
cd my-project
```

۲. نام پروژه، متادیتای پکیج و متغیرهای محیطی را تنظیم کنید.
۳. پروژه را اجرا کنید:

```bash
cp .env.example .env
make setup
make dev
make check
```

۴. اولین مشخصات فیچر را در `specs/` بنویسید.
۵. فیچر را پیاده‌سازی کنید و `make check` را سبز نگه دارید.

## قرارداد همکاری

- قبل از تغییر کد، `AGENTS.md` و Spec مرتبط را بخوانید.
- پیش از افزودن Abstraction یا Dependency جدید، از الگوهای موجود استفاده کنید.
- Credential یا داده‌ی واقعی پروداکشن را Commit نکنید.
- پیش از Pull Request تمام Quality Checkهای ریپو را اجرا کنید.
- تصمیم‌های معماری را در `docs/decisions/` ثبت کنید.

## مستندات

از `docs/getting-started.md` شروع کنید. راهنمای کامل‌تر توسعه‌ی AI-first در [Easy Starter Docs](https://github.com/easy-starter/easy-starter-docs) نگهداری می‌شود.

## مشارکت و پشتیبانی

قوانین مشارکت در [`CONTRIBUTING.md`](CONTRIBUTING.md)، روش دریافت کمک در [`SUPPORT.md`](SUPPORT.md) و گزارش مسائل امنیتی در [`SECURITY.md`](SECURITY.md) قرار دارد.

## مجوز

این پروژه تحت [مجوز MIT](LICENSE) منتشر می‌شود.

</div>
