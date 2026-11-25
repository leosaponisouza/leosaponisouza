# Leonardo Saponi de Souza

**Backend Software Engineer** · Java 21 · Spring Boot · Distributed Systems · Oracle & PostgreSQL · Spec-Driven Development & AI Agents  
Piracicaba, SP · Brazil

[![LinkedIn](https://img.shields.io/badge/LinkedIn-leonardosaponi-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leonardosaponi)
[![Java 21 Backend](https://img.shields.io/badge/Featured%20Code-Java%2021%20%2B%20Spring%20Boot%20Ecosystem-ED8B00?style=flat-square&logo=openjdk&logoColor=white)](https://github.com/leosaponisouza?tab=repositories)

---

### About Me

Backend Software Engineer with **~5 years of experience** designing, optimizing, and scaling mission-critical financial, credit, and billing systems serving **1.2M+ customers**.

- Currently **Backend Software Engineer at NGBilling**, building multi-module **Java 21 / Spring Boot 3.5** microservices, event-driven financial integrations (**Oracle Advanced Queuing / Outbox**, Pix/Boleto banking gateways, Serasa, SAP/TaxOne), and high-throughput Oracle workloads (**>90% latency reduction** on critical billing routines: 10 min → <1 min).
- Previously **Software Engineer at Algar Telecom** (4 years), developing high-volume credit orchestration, anti-fraud real-time integrations, BFF layers, and Oracle PL/SQL auditing pipelines.
- Advocate for **Spec-Driven Development (SDD)** and AI-assisted engineering (**Claude Code, MCP servers, automated guardrails**) to elevate architecture quality, predictability, and delivery velocity.
- B.Sc. in Information Systems — **Federal University of Uberlândia (UFU)** · [Published Thesis (2025)](https://repositorio.ufu.br/handle/123456789/47535).

> *Most of my day-to-day engineering work lives in private corporate repositories; the connected public ecosystem below showcases how I design, test, and govern production systems.*

---

### Featured Engineering Ecosystem

#### 1. [**RepHelper**](https://github.com/leosaponisouza/rep-helper) — Full-Stack Shared Housing Management Monorepo

[![CI](https://github.com/leosaponisouza/rep-helper/actions/workflows/ci.yml/badge.svg)](https://github.com/leosaponisouza/rep-helper/actions/workflows/ci.yml)
[![Release](https://img.shields.io/github/v/release/leosaponisouza/rep-helper?style=flat-square&color=2ea44f)](https://github.com/leosaponisouza/rep-helper/releases)
[![Java 21](https://img.shields.io/badge/Java-21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)](https://github.com/leosaponisouza/rep-helper/tree/master/backend)
[![Spring Boot 3.4](https://img.shields.io/badge/Spring%20Boot-3.4-6DB33F?style=flat-square&logo=springboot&logoColor=white)](https://github.com/leosaponisouza/rep-helper/tree/master/backend)
[![PostgreSQL 16](https://img.shields.io/badge/PostgreSQL-16-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://github.com/leosaponisouza/rep-helper/blob/master/docs/arquitetura-e-modelagem/schema-postgresql-flyway.md)
[![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/leosaponisouza/rep-helper/blob/master/docker-compose.yml)

- [**Backend (`backend/`)**](https://github.com/leosaponisouza/rep-helper/tree/master/backend): **Java 21 Virtual Threads** + **Spring Boot 3.4.3** modular monolith, Spring Security 6 stateless JWT with refresh-token rotation, 2-step OTP password reset, server-side multi-tenant RBAC (`RepublicSecurityService`), Flyway + PostgreSQL 16, magic-byte upload validation, OpenAPI 3.1, and **27 MockMvc integration tests**.
- [**Frontend (`frontend/`)**](https://github.com/leosaponisouza/rep-helper/tree/master/frontend): React Native / Expo (iOS, Android & Web) with custom Editorial Design System (light/dark/system themes, WCAG contrast guardrails), recurring chores, shared financial ledger, events/RSVP calendar, and **125 Jest tests**.

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/leosaponisouza/rep-helper">
        <img src="https://raw.githubusercontent.com/leosaponisouza/rep-helper/master/docs/qa/14-painel-home-populado.png" width="190" alt="RepHelper Home Dashboard" />
      </a><br />
      <sub><b>Home Dashboard</b></sub>
    </td>
    <td align="center">
      <a href="https://github.com/leosaponisouza/rep-helper">
        <img src="https://raw.githubusercontent.com/leosaponisouza/rep-helper/master/docs/qa/13-financas-saldo-ajustado.png" width="190" alt="RepHelper Financial Ledger" />
      </a><br />
      <sub><b>Financial Ledger</b></sub>
    </td>
    <td align="center">
      <a href="https://github.com/leosaponisouza/rep-helper">
        <img src="https://raw.githubusercontent.com/leosaponisouza/rep-helper/master/docs/qa/11-eventos-agenda.png" width="190" alt="RepHelper Events Calendar" />
      </a><br />
      <sub><b>Events &amp; Calendar</b></sub>
    </td>
  </tr>
</table>

#### 2. Focused Java 21 Services & Libraries

| Repository | Focus & Architectural Proof |
|---|---|
| [**rep-helper-settlement-engine**](https://github.com/leosaponisouza/rep-helper-settlement-engine)<br/>[![CI](https://github.com/leosaponisouza/rep-helper-settlement-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/leosaponisouza/rep-helper-settlement-engine/actions/workflows/ci.yml) | **Fintech & Concurrency:** Exact-cent *Min-Cash-Flow* debt simplification ($\le N-1$ Pix transfers), concurrent Pix webhook idempotency (`UNIQUE` receipt ledger + JPA `@Version` optimistic locking verified under Virtual Thread storms), **Transactional Outbox**, and Prometheus metrics. |
| [**exomadb-engine**](https://github.com/leosaponisouza/exomadb-engine)<br/>[![CI](https://github.com/leosaponisouza/exomadb-engine/actions/workflows/ci.yml/badge.svg)](https://github.com/leosaponisouza/exomadb-engine/actions/workflows/ci.yml) | **High-Volume SQL & Streaming:** Clean-room Java 21 evolution of my UFU genomics thesis — bounded-memory VCF v4.2 batch ingestion (`1,000` rows/batch) and **$O(\log N)$ Keyset Pagination** vs. `OFFSET` benchmarked with composite B-Tree indexes and `EXPLAIN` plans. |
| [**sdd-spring-guardrails**](https://github.com/leosaponisouza/sdd-spring-guardrails)<br/>[![CI](https://github.com/leosaponisouza/sdd-spring-guardrails/actions/workflows/ci.yml/badge.svg)](https://github.com/leosaponisouza/sdd-spring-guardrails/actions/workflows/ci.yml) | **SDD & AI Governance:** Reusable **ArchUnit 1.3 + `@SpecContract`** library enforcing layered boundaries, zero `@Entity` leaks, explicit `OffsetDateTime` contracts, `@Valid` mutations, and Markdown spec traceability — consumed via JitPack by the engines above. |

---

### Core Technical Stack

| Domain | Technologies & Practices |
|---|---|
| **Languages & Core** | Java (8 → 21, Virtual Threads), TypeScript, OOP, Data Structures, SOLID, Clean Code, DDD, 12-Factor App |
| **Frameworks & APIs** | Spring Boot 3.x, Spring Data JPA, Spring Security, JWT, Bean Validation, REST APIs, OpenAPI / Swagger, Microservices, SOA, BFF |
| **Databases & Messaging** | Oracle (PL/SQL, Query Tuning, Execution Plans, Materialized Views, Triggers), PostgreSQL, MySQL, Flyway, Oracle AQ (Outbox Pattern), Kafka, RabbitMQ |
| **Cloud, DevOps & Obs.** | Docker, Kubernetes, Jenkins, GitLab CI/CD, GitHub Actions, Git, Maven, Spring Actuator, Micrometer, Prometheus |
| **Quality & AI Engineering** | JUnit 5, ArchUnit, Mockito, REST Assured, JaCoCo, Jest, TDD, Spec-Driven Development (SDD), Claude Code, AI Agents, MCP Servers |

---

### Experience Highlights

- **Backend Software Engineer — NGBilling** *(Aug 2025 – Present)*: Billing performance optimization (>90% reduction on Oracle batch queries), Java 21 / Spring Boot 3.5 microservices, Outbox messaging (Oracle AQ), financial/ERP integrations, and SDD workflows with AI agents.
- **Software Engineer (Full-Stack / Backend Java) — Algar Telecom** *(Aug 2022 – Aug 2025)*: Mission-critical credit analysis services (1.2M+ customers), real-time anti-fraud & bureau integrations, BFF layers, and Oracle PL/SQL audit routines.
- **Software Engineering Intern — Algar Telecom** *(Aug 2021 – Aug 2022)*: Enterprise Java CRM evolution, incident resolution, and CI/CD build/deploy automation.

---

### Research & Architectural Retrospective

- [**Incremental Modernization of exomaDB — Undergraduate Thesis (UFU, 2025)**](https://repositorio.ufu.br/handle/123456789/47535): Evolved a pilot module of a live rare-disease genomics platform (**LABGEN/UFU & CAMH** collaboration, **3.88M+ NGS variant annotations**), decoupling a 2,600-LOC legacy *God Class* into a Maven-managed SOLID layered architecture with PostgreSQL server-side pagination and JUnit 5/Mockito unit tests.
  - *Critical retrospective → [**exomadb-engine (v2)**](https://github.com/leosaponisouza/exomadb-engine):* while pragmatic as a low-risk *Strangler* pilot, the v1 design remained coupled to stateful SSR (`JSF @ViewScoped`) and naive `OFFSET` pagination that degrades on deep pages. `exomadb-engine` re-implements those problems from scratch with stateless **Java 21 Virtual Threads**, streaming JDBC batch ingestion, and composite-indexed **Keyset Pagination** verified via automated query plans.