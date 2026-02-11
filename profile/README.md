<p align="center">
  <img src="https://escalated.dev/brand/logo-icon-gradient.svg" alt="Escalated Logo" width="128" height="128" />
</p>

<h1 align="center">Escalated</h1>
<p align="center">Support tickets, built *into your application* — not beside it.</p>

---

## 🌐 Vision

Escalated is a **framework-native embeddable help desk platform** designed to eliminate external ticketing silos by putting support systems directly into your existing application ecosystem. Rather than relying on standalone SaaS tools with separate data stores and authentication, Escalated integrates natively with your models, DB, and deployment pipeline so your support experience inherits your architecture and security model.

---

## 💡 What Escalated Is

Escalated is an **open-source, MIT-licensed support desk system** that lives inside your codebase and app workflows — offering:

- End-to-end ticketing with threaded conversations
- Statuses, priorities, SLAs, and escalation rules
- Assignment, ownership, and queue management
- Flexible tagging, filters, and organization
- Email notification and webhook integrations via native framework tooling
- A shared UI powered by Inertia.js that feels consistent across stacks :contentReference[oaicite:1]{index=1}

Your data stays yours — **no separate databases, no external auth, no “shadow system.”**

---

## 🛠️ Framework Support & Integrations

Escalated delivers **idiomatic integrations** for multiple ecosystems:

- **Laravel** — Eloquent models, migrations, artisan commands
- **Ruby on Rails** — Rails engine + ActiveRecord
- **Django** — Native Django app integration
- **AdonisJS** — TypeScript-first package with Lucid models
- **Filament** — Admin panel resources and widgets

---

## 🚀 Getting Started

Installation is simple — add the Escalated adapter for your stack and run migrations:

```bash
composer require escalated-dev/escalated-laravel
bundle add escalated-rails
pip install escalated-django
