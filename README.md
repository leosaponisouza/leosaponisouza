# Leonardo Saponi de Souza

**Backend Software Engineer** · Java 21 · Spring Boot · Distributed Systems · Oracle & PostgreSQL · Spec-Driven Development & AI Agents

[![LinkedIn](https://img.shields.io/badge/LinkedIn-leonardosaponi-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leonardosaponi)
![Location](https://img.shields.io/badge/Location-Piracicaba%2C%20SP%20%E2%80%A2%20Brazil-24292F?style=flat-square)

---

### About Me

Backend Software Engineer with **~5 years of experience** designing, optimizing, and scaling mission-critical financial, credit, and billing systems serving **1.2M+ customers**.

- Currently **Backend Software Engineer at NGBilling**, building multi-module **Java 21 / Spring Boot 3.5** microservices, event-driven financial integrations (**Oracle Advanced Queuing / Outbox**, Pix/Boleto banking gateways, Serasa, SAP/TaxOne), and high-throughput Oracle workloads (**>90% latency reduction** on critical billing routines: 10 min → <1 min).
- Previously **Software Engineer at Algar Telecom** (4 years), developing high-volume credit orchestration, anti-fraud real-time integrations, BFF layers, and Oracle PL/SQL auditing pipelines.
- Advocate for **Spec-Driven Development (SDD)** and AI-assisted engineering (**Claude Code, MCP servers, automated guardrails**) to elevate architecture quality, predictability, and delivery velocity.
- B.Sc. in Information Systems — **Federal University of Uberlândia (UFU)**.

> *Most of my day-to-day engineering work lives in private corporate repositories; this profile highlights selected public architecture and personal projects.*

---

### Flagship Project

#### [**RepHelper**](https://github.com/leosaponisouza/rep-helper) — Full-Stack Shared Housing Management Monorepo

> Self-hosted platform for managing shared student residences ("repúblicas"), engineered as a unified monorepo with **zero external BaaS lock-in**.

[![CI](https://github.com/leosaponisouza/rep-helper/actions/workflows/ci.yml/badge.svg)](https://github.com/leosaponisouza/rep-helper/actions/workflows/ci.yml)
![Java 21](https://img.shields.io/badge/Java-21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot 3.4](https://img.shields.io/badge/Spring%20Boot-3.4-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL 16](https://img.shields.io/badge/PostgreSQL-16-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-Migrations-CC0200?style=flat-square)
![React Native / Expo](https://img.shields.io/badge/Expo-React%20Native-000020?style=flat-square&logo=expo&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker-Compose-2496ED?style=flat-square&logo=docker&logoColor=white)

- **Backend (`backend/`)**: Java 21 + Spring Boot 3.4 REST API, Spring Security 6 stateless JWT with refresh-token rotation, 2-step OTP password reset, server-side multi-tenant RBAC (`OWNER` / `ADMIN` / `MEMBER`), per-route rate limiting, Flyway-managed PostgreSQL 16 schema, OpenAPI/Swagger, authenticated local VPS media storage, and **27 MockMvc integration tests** running in GitHub Actions CI.
- **Frontend (`frontend/`)**: React Native / Expo (iOS, Android & Web) with custom Editorial Design System (light/dark/system themes, WCAG contrast guardrails), recurring chore engine, shared financial ledger (approval → reimbursement → balance audit), events/RSVP calendar, and **125 automated Jest tests**.
- **Architecture, Specs & QA (`docs/`)**: REST API spec, data model, Mermaid state/sequence diagrams, SDD plans (`docs/specs/`), and 22 verified end-to-end browser QA captures (`docs/qa/`).

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

---

### Core Technical Stack

| Domain | Technologies & Practices |
|---|---|
| **Languages & Core** | Java (8 → 21), TypeScript, OOP, Data Structures, SOLID, Clean Code, DDD, 12-Factor App |
| **Frameworks & APIs** | Spring Boot 3.x, Spring Data JPA, Spring Security, JWT, Bean Validation, REST APIs, OpenAPI / Swagger, Microservices, SOA, BFF |
| **Databases & Messaging** | Oracle (PL/SQL, Query Tuning, Execution Plans, Materialized Views, Triggers), PostgreSQL, MySQL, Flyway, Oracle AQ (Outbox Pattern), Kafka, RabbitMQ |
| **Cloud, DevOps & Obs.** | Docker, Kubernetes, Jenkins, GitLab CI/CD, GitHub Actions, Git, Maven, Spring Actuator, Micrometer, Prometheus |
| **Quality & AI Engineering** | JUnit 5, Mockito, REST Assured, JaCoCo, Jest, TDD, Spec-Driven Development (SDD), Claude Code, AI Agents, MCP Servers |

---

### Experience Highlights

- **Backend Software Engineer — NGBilling** *(Aug 2025 – Present)*: Billing performance optimization (>90% reduction on Oracle batch queries), Java 21 / Spring Boot 3.5 microservices, Outbox messaging (Oracle AQ), financial/ERP integrations, and SDD workflows with AI agents.
- **Software Engineer (Full-Stack / Backend Java) — Algar Telecom** *(Aug 2022 – Aug 2025)*: Mission-critical credit analysis services (1.2M+ customers), real-time anti-fraud & bureau integrations, BFF layers, and Oracle PL/SQL audit routines.
- **Software Engineering Intern — Algar Telecom** *(Aug 2021 – Aug 2022)*: Enterprise Java CRM evolution, incident resolution, and CI/CD build/deploy automation.