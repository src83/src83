# Roman Staroseltsev

**Senior Backend Developer (PHP, AI)** · commercial PHP since 2011 · Senior since 2017

Payments, integrations and the code around them that must not break: webhooks, queues, idempotency, retries.
Commercial PHP since 2011, Senior since 2017, former Tech Lead (rebuilt a marketplace, grew the team 0 → 3).
Remote from Turkey, UTC+3.

---

**What I build**

- **Payment flows** – PSP and bank acquiring integrations, webhooks, state machines, KYC/AML steps
- **Async backends** – RabbitMQ / Redis queues, Supervisor workers, safe retries and dedup
- **Laravel architecture** – modular monolith, clean API contracts, admin panels and internal services

**How I work with an AI agent**

1. Project rules in `CLAUDE.md` – every rule has its reason
2. Written plan first, approved before any code
3. Architectural plans get a critique in a fresh context
4. I trust the diff and the test output, not the agent's summary
5. No commit without green PHPUnit, PHPStan (level 8) and Pint

---

**Selected repositories**

- **[laravel-api-response](https://github.com/src83/laravel-api-response)** ([Packagist](https://packagist.org/packages/src83/laravel-api-response)) – one JSON contract for Laravel APIs: exceptions, localization, pagination, logging, an adaptive installer. Tested with PHPUnit, PHPStan level 8, GitHub Actions.
- **[laravel11-idempotent-webhook](https://github.com/src83/laravel11-idempotent-webhook)** – an idempotent payment webhook: unique payment_id, row lock, state machine, out-of-order events.
- **[l9stk](https://github.com/src83/l9stk)** – starter kit for a modular monolith on Laravel; each module has its own routes, models, migrations and views.
- **[l9stk-chat](https://github.com/src83/l9stk-chat)** – a production web chat with incremental polling, duplicate protection and a mobile UI, later extracted into a module.
- **[larbase](https://github.com/src83/larbase)** – a test bed for the package: a full module with API, CRUD, a console command and tests.

Also building a private HR-tech product (web + AI) on L9STK.

---

**Day-to-day stack:** PHP 8 · Laravel · Symfony · MySQL/MariaDB · Redis · RabbitMQ · ClickHouse · MongoDB · Elasticsearch · Docker · Nginx · Linux · GitLab CI · GitHub Actions · PHPUnit · PHPStan · Pint · Claude Code

[LinkedIn](https://www.linkedin.com/in/staroseltsev) · [Telegram @src83](https://t.me/src83) · src83work@gmail.com
