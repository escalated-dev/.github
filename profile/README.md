<p align="center">
  <a href="https://escalated.dev">
    <img src="https://raw.githubusercontent.com/escalated-dev/escalated/main/.github/og.png" alt="Escalated — support tickets, built into your app" width="840" />
  </a>
</p>

<p align="center">
  Support tickets, built <strong>into your application</strong> — not beside it.
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/escalated-dev/escalated/main/.github/profile/demo.gif" alt="Escalated demo" width="800" />
</p>

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
- A shared UI powered by Inertia.js that feels consistent across stacks

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
npm install @escalated-dev/escalated-adonis
composer require escalated-dev/escalated-laravel escalated-dev/escalated-filament
