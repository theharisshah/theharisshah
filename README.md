<h1 align="center">Hi, I'm Haris Shah 👋</h1>
<h3 align="center">Senior Software Engineer · Payments &amp; Billing Infrastructure</h3>

<p align="center">
  <a href="https://linkedin.com/in/theharisshah"><img src="https://img.shields.io/badge/LinkedIn-theharisshah-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:shahharis383@gmail.com"><img src="https://img.shields.io/badge/Email-shahharis383%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Bengaluru-India-16a34a?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Bengaluru, India" />
</p>

## 👋 About me

I build the backend systems that move money. Over 8+ years I've gone from shipping Laravel APIs for delivery marketplaces to owning payments end-to-end — today I lead the **Payments pod at Kenko AI**, responsible for the design, delivery and reliability of everything that charges a card.

- 💳 **Payments & subscriptions** — architected a gateway-agnostic subscription engine from scratch: recurring billing across Stripe, Adyen and Razorpay with no vendor lock-in
- 🔌 **Platform payments** — led the **Adyen for Platforms** integration end-to-end, working directly with Adyen's implementation engineers, and lead Kenko's **Stripe Connect** (Custom accounts) build: onboarding, payments and payouts for merchants on the platform
- 🚨 **Production ownership** — technical escalation point for payment failures; the person Support calls when money doesn't move
- 📈 **Scale** — took a warehouse management system to **7–8 million requests/day** with async queues, database partitioning and deadlock resolution
- 🧰 **Developer tools** — I build and open-source the desktop tools I wish existed (see below)

## 🚀 Featured projects

<p align="center">
  <a href="https://github.com/theharisshah/tinkerbox"><img src="https://github-readme-stats.vercel.app/api/pin/?username=theharisshah&repo=tinkerbox&theme=tokyonight&hide_border=true" alt="Tinkerbox" /></a>
  <a href="https://github.com/theharisshah/gitcolumn"><img src="https://github-readme-stats.vercel.app/api/pin/?username=theharisshah&repo=gitcolumn&theme=tokyonight&hide_border=true" alt="gitcolumn" /></a>
</p>
<p align="center">
  <a href="https://github.com/theharisshah/ClipboardManager"><img src="https://github-readme-stats.vercel.app/api/pin/?username=theharisshah&repo=ClipboardManager&theme=tokyonight&hide_border=true" alt="ClipboardManager" /></a>
</p>

| Project | What it is | Built with |
|---|---|---|
| **[Tinkerbox](https://github.com/theharisshah/tinkerbox)** | Open-source desktop scratchpad for PHP & Laravel — run code inside your project's booted context, with magic comments, SQL inspection, rich dumps and framework-aware autocomplete. Drivers for 20+ frameworks. | Electron · Vue 3 · Monaco · TypeScript · PHP |
| **[gitcolumn](https://github.com/theharisshah/gitcolumn)** | A Tower-style desktop Git client for macOS, Windows and Linux, sitting on top of the real git CLI. | Electron · React · TypeScript |
| **[ClipboardManager](https://github.com/theharisshah/ClipboardManager)** | Lightweight, keyboard-first macOS menu-bar clipboard history — ⇧⌘V to search everything you've copied. | Swift · SwiftUI |

## 💡 Things I've learned building payments

- **Webhooks are primary, reconciliation is mandatory.** Webhooks tell you what happened fast; a scheduled reconciliation sweep against the gateway catches the ones that never arrived.
- **Only retry from a definite failure.** An *unknown* outcome is not a failure — retrying it is how you double-charge a customer.
- **Switching gateways means new consent.** Moving a merchant's stored payment method isn't a config flip; it's an on-session re-authorisation, with chargeback and regulatory exposure if you skip it.

## 🛠️ Tech stack

| | |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white) |
| **Backend** | ![Django REST Framework](https://img.shields.io/badge/Django%20REST%20Framework-092E20?style=for-the-badge&logo=django&logoColor=white) ![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) |
| **Data** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white) |
| **Infrastructure** | ![AWS](https://img.shields.io/badge/AWS%20%C2%B7%20EC2%20%C2%B7%20ECS%20%C2%B7%20SQS%20%C2%B7%20S3-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) |
| **Payments** | ![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white) ![Stripe Connect](https://img.shields.io/badge/Stripe%20Connect-635BFF?style=for-the-badge&logo=stripe&logoColor=white) ![Adyen](https://img.shields.io/badge/Adyen-0ABF53?style=for-the-badge&logo=adyen&logoColor=white) ![Razorpay](https://img.shields.io/badge/Razorpay-0C2451?style=for-the-badge&logo=razorpay&logoColor=white) |
| **Desktop & frontend** | ![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white) ![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![SwiftUI](https://img.shields.io/badge/SwiftUI-0D84FF?style=for-the-badge&logo=swift&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white) |

## 📊 GitHub stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=theharisshah&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&rank_icon=github" height="165" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=theharisshah&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&hide=html,css,blade,scss" height="165" alt="Top languages" />
</p>

---

<p align="center">
  Always happy to talk payments, billing systems and developer tooling · 📫 <a href="mailto:shahharis383@gmail.com">shahharis383@gmail.com</a>
</p>
