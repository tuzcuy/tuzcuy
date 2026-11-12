# Yigit Tuzcu

Computer engineer and co-founder of [Corantsoft](https://corantsoft.com) — a small software studio shipping web, mobile and AI products. Currently a software engineer at International ATF Türkiye, where I build and run the technology stack behind a large international tourism fair. Based in Antalya, Turkey; previously worked as a software engineer in Madrid and Bilbao.

I work across the whole stack: Laravel/Livewire and Node/NestJS backends, React and Next.js frontends, Flutter mobile apps, and applied ML (PyTorch, computer vision). What I enjoy most is taking a real-world operation — a trade fair, a wholesaler, a boutique store — and turning it into software that actually runs in production.

## What I build

- **Event-tech at production scale** — a full CRM/ERP for an international tourism fair: company/contract/finance management, an interactive floor-plan (stand map) editor built in React and embedded in Laravel, and edge ingestion from Raspberry Pi turnstiles plus offline-first parking and canteen PWAs. The platform ran live during the fair, processing the flow of 14,000+ attendees in real time, side by side with a legacy database schema it was never allowed to alter (strangler-fig migration across 6 coexisting systems).
- **Cross-platform mobile** — the fair's official Flutter app (ATF World, Android/iOS/web from one codebase): B2B meeting scheduling, QR badge and lead capture, WhatsApp-OTP onboarding, FCM push — used by thousands of real attendees during the event.
- **Applied ML / computer vision** — VisionEvidence, an offline forensic image-analysis platform that decides whether an image is real, AI-generated or manipulated: two self-trained models (CLIP ViT-L/14 linear probe at 94.8% test accuracy, fine-tuned EfficientNet-B0), Grad-CAM explainability, Platt-calibrated confidence, a fusion engine that is allowed to say "uncertain", and fully offline Docker deployment. All metrics are read from real test runs — no invented numbers.
- **Multi-tenant ERP** — Cora, a quote-to-shipment management system for wholesalers: Prisma-extension-enforced tenant isolation, a tested Decimal pricing engine and sales state machine, ledger-only stock movements, and 55/55 Playwright e2e passing against the live deployment.
- **Client work via Corantsoft** — shipped-to-production sites and platforms: a custom e-commerce stack with an AI virtual try-on fitting room, a parametric three.js product viewer for a stainless-steel manufacturer, a canvas scroll-film site for a coffee brand, and multilingual (incl. RTL Arabic) business sites on constrained shared hosting.

## Stack

![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)
![Livewire](https://img.shields.io/badge/Livewire-4E56A6?logo=livewire&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?logo=firebase&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=white)

## Featured projects

| Project | What it is |
|---|---|
| [VisionEvidence](https://github.com/tuzcuy/visionevidence) | Offline forensic image analysis: self-trained CLIP/EfficientNet models, Grad-CAM, calibrated fusion verdicts, Turkish PDF reports, air-gapped Docker deploy |
| [Fair operations platform — case study](https://github.com/tuzcuy/atf-fair-platform-case-study) | Architecture write-up of the fair CRM/ERP + Flutter app + floor-plan editor + turnstile/PWA edge ingestion that ran a live international fair (write-up only, no employer code) |
| [Cora](https://github.com/tuzcuy/cora) | Multi-tenant wholesale ERP: enforced tenant isolation, Decimal pricing engine, ledger-based stock, 167 unit/integration tests + 55/55 e2e in production |
| [Selektör](https://github.com/tuzcuy/selektor) | Social discovery app concept built end to end: Flutter client, 37 Cloud Functions, custom face-verification microservice on Cloud Run, privacy-by-design (plates stored only as HMAC) |
| [shopify-orders-app](https://github.com/tuzcuy/shopify-orders-app) | Laravel 11 + Vue 3 dashboard syncing orders from the Shopify Admin API into MySQL |

## Contact

- Website: [yigittuzcu.com](https://www.yigittuzcu.com)
- LinkedIn: [linkedin.com/in/yigittuzcu](https://www.linkedin.com/in/yigittuzcu)
- Email: yigittuzcu@gmail.com
