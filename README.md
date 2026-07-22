# Arkadii Dolhonos

**Senior Full-Stack Engineer — Node.js, TypeScript, React**
Alicante, Spain (CET) · Remote / Hybrid in Spain
[arkad1ydolgonos@gmail.com](mailto:arkad1ydolgonos@gmail.com) · [LinkedIn](https://linkedin.com/in/arkadiy-dolgonos-6aa01438)

## Summary

Senior Full-Stack Engineer with 10+ years delivering B2B and enterprise product platforms end to end. A full-stack engineer throughout, combining strong React/TypeScript frontend work with consistent backend depth — Node.js/TypeScript services, AWS (Lambda, SQS), caching and async workflows, RabbitMQ pipelines, OOM/heap-dump debugging, and query optimization. Known for turning unstable legacy systems into reliable ones, raising engineering standards through testing and tooling, mentoring engineers, and working directly with product to shape features end to end.

## Core Skills

| | |
|---|---|
| **Backend** | Node.js, NestJS, Express, Fastify, TypeScript, REST APIs, RabbitMQ, query optimization *(earlier: Ruby on Rails, Java/Dropwizard, Spring/Hibernate)* |
| **Databases** | PostgreSQL, Oracle, Sybase, MongoDB, SQL & NoSQL; ORMs: Sequelize, Prisma |
| **Cloud & Infra** | AWS (Lambda, SQS), Docker, docker-compose, event-driven & async processing, caching (Redis, TTL) |
| **Frontend** | React, TypeScript, JavaScript, HTML5, CSS3, Redux Toolkit, RTK Query, React Query, MUI / Bootstrap, styled-components, React Hook Form, Yup/Zod |
| **Testing & Quality** | Playwright, Cypress (e2e), Jest, Jasmine, Enzyme, RSpec, JUnit; unit / integration / e2e testing |
| **Practices** | Clean architecture, code standards (ESLint / Husky), refactoring, production debugging, mentoring, epic estimation & breakdown; Agile/Scrum, Kanban, Waterfall |

## Experience

### NielsenIQ — Software Engineer
*Remote · Jul 2021 – Apr 2026*

- Owned backend development and maintenance of a B2B SaaS product built on Node.js (Express, Fastify, NestJS) and Sequelize — responsible end-to-end for its stability, performance, and feature delivery, including an SQS-based flow for asynchronous user updates.
- Eliminated a recurring out-of-memory crash that had occurred roughly every two weeks: traced the root cause from excessive frontend query calls down to inefficient backend data access, removed unnecessary React re-renders to stop the recurrence entirely, then added TTL-based caching that further cut backend load and sped up hot queries.
- Raised engineering standards across the team by adding unit and integration test coverage to critical paths of a previously under-tested legacy codebase and introducing linting and Husky pre-commit hooks — replacing inconsistent, review-heavy PRs with a consistent, automated baseline.
- Built a Lambda-based, client-facing email distribution service on AWS using SendGrid and MJML templates.
- Designed a batched async processing flow for regression testing that preserved data consistency — backend jobs collected data in batches, the frontend consumed partial results incrementally, and users could cancel processing without losing already-collected data.
- Shaped the architecture of Web Studio, a separate internal product, defining flexible module boundaries, dock-based tab workflows, and scalable patterns for independently managed product modules.
- Modernized the frontend of a legacy SaaS product — migrating an outdated React setup to a current React stack with Bootstrap and styled-components — and improved performance on data-heavy screens through debouncing, virtualization, and reduced re-renders.
- Worked directly with product managers to shape feature UX and backend design, estimated and broke epics down into tasks, and allocated and mentored junior engineers through delivery — including running internal sessions on testing practices.

### Oracle / Opower — Software Engineer
*Odesa · Jun 2017 – Jul 2021*

- Delivered full-stack features on Opower, an energy-industry product platform acquired by Oracle, across AngularJS frontend, Ruby on Rails backend, and Java/Dropwizard services for customer-facing email and letter communications.
- Led a gradual frontend migration from AngularJS to React, moving individual modules to React hooks, Redux, and Material UI.
- Removed a document-delivery bottleneck for large Japanese-market PDFs by moving heavy processing out of the Ruby on Rails request path and extending a Java service to convert PDFs into client-ready images.
- Built and optimized Java/Dropwizard services that generated final customer communications through RabbitMQ-based processing pipelines, tuning database queries and data access where needed.
- Improved reliability with automated tests across frontend and backend (Jasmine, Enzyme, RSpec, JUnit).

## Earlier Experience

### EPAM Systems — Software Engineer
*Dnipro · Oct 2015 – Jun 2017*

- Started on a team researching big-data technologies, then moved to backend development of POS terminal software using Java, Spring, Hibernate, Spring Data, Liquibase, and MariaDB.
- Delivered features, database changes, and maintenance for enterprise retail software in a Scrum team.

### Luxoft / Deutsche Bank — Software Engineer
*Dnipro · Jul 2014 – Oct 2015*

- Supported enterprise banking applications in a production-focused environment — issue investigation, maintenance, and improvements across Java, SQL/Oracle, and JavaScript.
- Built a Node.js/WebSocket prototype for continuous monitoring and faster operational troubleshooting.

### PrivatBank — Full-Stack Engineer
*Dnipro · Sep 2011 – Feb 2014*

- Maintained and extended a modular inbound-call handling system (Google Web Toolkit), used by all inbound-call operators and configurable per department, working full-stack across the GWT/JavaScript UI and REST/Jersey APIs with JDBC.
- Resolved OOM issues in a memory-sensitive product by analyzing heap dumps, tuning the JVM, and implementing a weak-reference-based cache with gradual cleanup.
- Built APIs for data collection and aggregation across internal systems, supporting operator and customer-service workflows.

## Education

**B.Sc., Oles Honchar Dnipro National University** · 2008 – 2012
Faculty of Physics, Electronics and Computer Systems

## Languages

English (B2) · Ukrainian (Native) · Russian (Native)
