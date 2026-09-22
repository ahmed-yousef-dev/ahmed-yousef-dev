<div align="center">

# Ahmed Yousef — Full-Stack Software Engineer

![Django](https://img.shields.io/badge/Django%20REST%20Framework-092E20?style=flat&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Async Jobs](https://img.shields.io/badge/Async_Jobs-Celery_+_Redis-37814A?style=flat&logo=celery&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Deployment](https://img.shields.io/badge/Deployment-Linux,_Nginx,_Gunicorn-FCC624?style=flat&logo=linux&logoColor=white)
![Automated Testing](https://img.shields.io/badge/Automated_Testing-pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![Load Testing](https://img.shields.io/badge/Load_Testing-Locust-4CAF50?style=flat&logo=locust&logoColor=white)
![Security](https://img.shields.io/badge/Security-OWASP_Top_10-000000?style=flat&logo=owasp&logoColor=white)

📍 Egypt &nbsp;·&nbsp; Open to **Remote** & **International Relocation**

[![Email](https://img.shields.io/badge/ahmed.yousuf.dev@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:ahmed.yousuf.dev@gmail.com)
[![LinkedIn](https://img.shields.io/badge/linkedin.com%2Fin%2Fahmed18-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmed18/)

</div>

---

## Hiring Snapshot

I build **production-grade, performance-focused web systems** end-to-end: **schema → APIs → async jobs → CI/CD → deployment → tests**.

**Proof by outcomes:**

- **TakeWay** *(sole backend engineer):* own the backend architecture of a platform combining **multi-vendor commerce, ride booking, and home services**, including **concurrency-safe wallet operations**, **atomic multi-vendor checkout**, and **event-driven workflows**.
- **Shifaa** *(backend engineer):* architected and deployed an extensible **multi-provider healthcare platform for doctors, laboratories, and pharmacies**, delivering 60+ secure REST APIs, 730+ automated tests, and a **Docker-based GitHub Actions CI/CD pipeline**.
- **HERA** *(full-stack engineer on a six-person team):* delivered workflows across attendance, overtime, leave, and payroll while reducing **API latency by 53%**, payload size by **60%**, and request volume by up to **90%**.

---

## Core Engineering Strengths

**Backend architecture that stays clean as the product grows**
> SOLID design, provider-style extensibility, clear boundaries, maintainable APIs.

**Performance engineering with measurable wins**
> N+1 elimination, `select_related` / `prefetch_related`, indexing strategy, payload shaping, caching.

**Reliability under real-world concurrency**
> Transaction safety (`transaction.atomic`), DB-level atomic updates, race-condition resolution.

**Security-minded engineering**
> JWT auth, RBAC, OTP flows, throttling, CSP headers, SSRF-safe validation, audit logging, proactive CVE patching.

**Shipping, not just coding**
> Automated CI/CD pipelines (GitHub Actions), containerized deployment (Docker / Linux / Nginx / Gunicorn), operational readiness, delivery follow-through.

---

## Featured Work

### TakeWay — Multi-Vendor Commerce, Ride Booking & Home Services Platform
**Sole Backend Engineer (Django REST Framework)** &nbsp;·&nbsp; Jul 2026 – Present

> A multi-service platform combining multi-vendor commerce, ride booking, and home services for underserved communities in Egypt.

- Engineered wallet credits, debits, and refunds using **PostgreSQL row-level locking**, atomic transactions, and database constraints, with every balance change preserved in an **immutable audit ledger**.
- Architected **multi-vendor checkout** that partitions a single cart into vendor-specific suborders within one atomic transaction while preserving historical invoices through immutable product, price, and discount snapshots.
- Decoupled order and ride events from delivery through an **internal event bus and Celery/Redis workers**, offloading FCM notifications, OTP delivery, and image processing while persisting in-app notifications.

---

### Shifaa — Multi-Provider Healthcare Booking Platform
**Backend Engineer (Django REST Framework)** &nbsp;·&nbsp; Jan 2026 – May 2026

> Shifaa is a scalable multi-provider healthcare booking platform designed to digitize offline medical services for smaller cities and underserved regions in Egypt.

- Architected a scalable and extensible multi-provider platform using abstract models and `GenericForeignKey`, unifying booking workflows (doctors, labs, pharmacies) with zero code duplication (DRY) while avoiding the SQL JOIN overhead of multi-table inheritance to seamlessly support future provider types.
- Orchestrated a containerized deployment pipeline using **Docker and GitHub Actions CI/CD**, ensuring reproducible builds across a Linux VPS (Nginx, Gunicorn), while delivering **60+ secure REST APIs** (JWT, RBAC, OTP).
- Engineered asynchronous, concurrency-safe workflows using **Celery, Redis, and Celery Beat**, enforcing transactional integrity and eliminating race conditions in booking and scheduling under high-concurrency workloads.
- Conducted load, stress, and spike testing using **Locust**, identifying API bottlenecks, payload inefficiencies, and scalability limitations through performance monitoring and endpoint-level analysis.
- Guaranteed platform reliability and security by implementing **730+ automated tests** (pytest) and OWASP-aligned hardening, while optimizing bulk database operations to reduce data seeding time by **96%** (from 3 mins to 5s).

---

### HERA — HR Management System
**Full-Stack Software Engineer (React + Django REST Framework)** &nbsp;·&nbsp; May – Jul 2025 &nbsp;·&nbsp; [GitHub Repository](https://github.com/ITI-Grad-Team/HR-Management-System)

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

| Domain | Technologies |
|:--|:--|
| **Backend** | Python · Django · Django REST Framework · FastAPI · Flask |
| **Databases & Caching** | PostgreSQL · Redis · MySQL · SQL Server · MongoDB · SQLite |
| **Async & Messaging** | Celery · Celery Beat · Redis |
| **Testing & Security** | pytest (Unit & Integration) · Locust (Load & Stress) · OWASP Top 10 · JWT · RBAC |
| **Frontend** | React (Hooks, ES6+) · HTML5 · CSS3 · Bootstrap 5 |
| **DevOps & Infrastructure** | Docker · GitHub Actions (CI/CD) · Linux (Ubuntu) · Nginx · Gunicorn · Bash |

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

## Technical Discussion Areas

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
