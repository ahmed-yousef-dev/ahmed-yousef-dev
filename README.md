<div align="center">

# Ahmed Yousef — Full-Stack Software Engineer

![Django](https://img.shields.io/badge/Django%20REST%20Framework-092E20?style=flat&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Celery](https://img.shields.io/badge/Celery%20%2B%20Redis-37814A?style=flat&logo=celery&logoColor=white)
![Linux](https://img.shields.io/badge/Linux%20%28Nginx%20%2F%20Gunicorn%29-FCC624?style=flat&logo=linux&logoColor=black)

📍 Egypt &nbsp;·&nbsp; Open to **Remote** & **International Relocation**

[![Email](https://img.shields.io/badge/ahmed.yousuf.dev@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:ahmed.yousuf.dev@gmail.com)
[![LinkedIn](https://img.shields.io/badge/linkedin.com%2Fin%2Fahmed18-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmed18/)

</div>

---

## Hiring Snapshot

I build **production-grade, performance-focused web systems** end-to-end: **schema → APIs → async jobs → deployment → tests**.

**Proof by outcomes:**

- **TakeWay** *(sole backend engineer):* architected a **multi-domain "Super App"** consolidating diverse services with **polymorphic data modeling** and **asynchronous push notifications** via Celery/Redis.
- **Shifaa** *(sole backend engineer):* shipped a production backend with **60+ REST APIs** and **730+ passing tests**, deployed on a **Linux VPS** — currently **in Google Play Store review**.
- **HERA** *(ITI capstone, team project):* delivered full-stack features and drove measurable backend improvements — **53% query latency reduction** and **90% fewer API calls** via caching, pagination, and debounced queries.

---

## What I'm Great At

**Backend architecture that stays clean as the product grows**
> SOLID design, provider-style extensibility, clear boundaries, maintainable APIs.

**Performance engineering with measurable wins**
> N+1 elimination, `select_related` / `prefetch_related`, indexing strategy, payload shaping, caching.

**Reliability under real-world concurrency**
> Transaction safety (`transaction.atomic`), DB-level atomic updates, race-condition resolution.

**Security-minded engineering**
> JWT auth, RBAC, OTP flows, throttling, CSP headers, SSRF-safe validation, audit logging, proactive CVE patching.

**Shipping, not just coding**
> Linux deployment (Gunicorn / Nginx), operational readiness, disciplined test coverage, delivery follow-through.

---

## Featured Work

### 🚀 TakeWay — Multi-Service Super App
**Sole Backend Engineer (Django REST Framework)** &nbsp;·&nbsp; Jul 2026 – Aug 2026

> Production-deployed · Android client integrated · **Currently in Google Play Store review**
> A scalable multi-domain platform aggregating food delivery, technician services, and custom orders.

- Architected a **unified "Super App" backend** consolidating e-commerce and service-booking using **polymorphic data modeling** (`GenericForeignKey`).
- Engineered a **multi-vendor order architecture** resolving cart checkouts into parent-child orders via **ACID-compliant atomic transactions**.
- Designed an **asynchronous push notification service** leveraging **Celery and Redis** to guarantee non-blocking, high-throughput processing.

---

### 🏥 Shifaa — Healthcare Booking Platform
**Sole Backend Engineer (Django REST Framework)** &nbsp;·&nbsp; Jan 2026 – May 2026 &nbsp;·&nbsp; [GitHub Repository](https://github.com/ahmed-yousef-dev/Shifaa)

> Production-deployed · Android client integrated · **Currently in Google Play Store review**
> Built for Egypt's underserved towns and villages.

- Architected a scalable multi-provider platform unifying workflows with **zero code duplication** avoiding SQL JOIN overhead.
- Orchestrated a **containerized deployment pipeline** (Docker + GitHub Actions) to a **Linux VPS** (Gunicorn + Nginx).
- Engineered concurrency-safe workflows using **Celery, Redis, and Celery Beat** under high-concurrency workloads.
- Conducted load/stress testing using **Locust** and maintained quality with **730+ passing pytest tests**.
- Reduced data seeding time **from 3 minutes to ~5 seconds** (96% reduction) via bulk operations.

---

### 📊 HERA — HR Management System
**Full-Stack Web Application (React + Django REST Framework)** &nbsp;·&nbsp; May – Jul 2025 &nbsp;·&nbsp; [GitHub Repository](https://github.com/ITI-Grad-Team/HR-Management-System)

> ITI Capstone · Team Project

- Built for a **full employee-lifecycle HR platform** spanning recruitment, attendance, overtime, leave management, and payroll generation.
- Delivered end-to-end features across Attendance (geo check-in/out), Overtime, Leave, and Payroll modules.
- Engineered secure **RBAC** (Admin / HR / Employee) with strict DRF permissions on all state-changing actions.
- Built real-time SPA approval flows with **optimistic UI updates** + rollback/error handling — no full page reloads.
- Optimized heavy endpoints using `select_related()`, `only()`, indexing, and dedicated lightweight serializers.
- Achieved **53% query latency reduction** (0.19s → 0.09s) and **60% API payload reduction**.

---

## Metrics That Matter

| Area | Result | Method |
|:--|--:|:--|
| Query efficiency | **90% fewer API calls** | Server-side pagination · debounced queries · LRU+TTL caching |
| Query performance | **53% faster** (0.19s → 0.09s) | ORM profiling · indexing · N+1 elimination |
| Dev velocity | **96% faster seeding** (3m → 5s) | Bulk ops · optimized data workflows |
| Code reuse | **Zero code duplication** | Polymorphism (`GenericForeignKey`) · abstract models |
| Test coverage | **730+ passing tests** | pytest · automated CI/CD pipelines |

---

## Tech Stack

| Layer | Tools |
|:--|:--|
| **Backend** | Python · Django · Django REST Framework · FastAPI · Flask |
| **Async** | Celery · Celery Beat · Redis |
| **Databases** | PostgreSQL · MySQL · SQL Server · MongoDB · SQLite |
| **Frontend** | React (ES6+, Hooks) · HTML/CSS · Bootstrap 5 |
| **DevOps** | Linux · Nginx · Gunicorn · Docker · GitHub Actions (CI/CD) · Bash |
| **Engineering** | Architecture · Concurrency · Performance Testing (Locust) · Security (OWASP, JWT, RBAC) |
| **Languages** | Python · JavaScript · C++ · Bash |

---

## Background

**B.Sc. Mechatronics Engineering — Benha University** *(2019–2024)*
Graduation project: **6-Axis AI-Based Robotic Arm Platform** — *Graded: Excellent*

**Information Technology Institute (ITI)** — 5-month intensive full-stack program *(Mar–Jul 2025)*
Curriculum: Django/Flask · React · PostgreSQL · Docker · Linux Administration

**Certifications:**
- [Ubuntu Linux Professional Certificate (Canonical)](https://www.linkedin.com/learning/certificates/d1da920f52e3cb65bcb7c731af2525a3213b8638bcdddfccf787a800dd08de20)
- [Azure Essentials Professional Certificate (Microsoft)](https://www.linkedin.com/learning/certificates/82a020ab618ae9b18bcceddd577c587b3b3e39eacb5085f5a3dc68c42678b592)
- [Docker Foundations Professional Certificate (Docker)](https://www.linkedin.com/learning/certificates/044791bcc8e33803851d43ab1f99067d62398354c6749c58f3190d494cfa56ac)
- [Career Essentials in GitHub Professional Certificate (GitHub)](https://www.linkedin.com/learning/certificates/4aff31097956d7f440776b95cd187d03eae76fcac5ebcb5526a6a04eb9b9da07)

**English:** C1 — Native-like proficiency

---

## How to Evaluate Me Quickly

If you're a hiring team running a technical screen, here's where I'm strongest:

1. **Architecture decisions** — ask about tradeoffs, constraints, and how a system should evolve.
2. **Performance stories** — ask how I profiled, hypothesized, changed, and measured.
3. **Reliability under concurrency** — ask about transactions, idempotency, race conditions.
4. **Engineering habits** — look at test discipline, PR hygiene, and written communication.

---

<div align="center">

*If you need an engineer who takes real ownership and ships systems that are secure, fast, and maintainable — let's talk.*

[![Email](https://img.shields.io/badge/ahmed.yousuf.dev@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:ahmed.yousuf.dev@gmail.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmed18/)

</div>
