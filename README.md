<h1 align="center">Syed Iqbal</h1>

<p align="center">
  <strong>Senior Full-Stack .NET Developer</strong><br>
  Angular · Azure Cloud · Microservices · CQRS · Clean Architecture
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/syed--iqbal/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:syediqbalsr.net@gmail.com"><img src="https://img.shields.io/badge/Email-333333?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## About Me

I design and deliver cloud-native enterprise platforms, including multi-tenant SaaS products, event-driven microservices, and systems built to remain maintainable long after the first release.

- 6+ years of professional experience
- Domains: FinTech, InventoryTech, CRM, EdTech
- Clients across the UAE, Romania, and Pakistan
- Based in Islamabad, Pakistan

---

## Featured Projects

### DAMAC Group (Dubai) — Multi-Tenant Inventory & Asset Tracking Platform
Architected end-to-end delivery of [Invoqat](https://invoqat.com), a multi-tenant SaaS platform processing 5,000+ daily asset transactions across 10+ locations via RFID, QR, Barcode, NFC, and OCR.

- Engineered a configurable procurement workflow (requests → approvals → transfers → consumption), cutting manual processing time by ~60%
- Built a multi-level RBAC and approval engine across 10+ user roles using Clean Architecture and CQRS/MediatR
- Automated document scanning with Tesseract and Azure Computer Vision for receipts, delivery notes, and asset labels
- Shipped a production MCP server integrated with Claude, Microsoft Copilot, Teams, and the Invoqat app for natural-language inventory queries and transfers
- Implemented event-driven workflows with Azure Service Bus, eliminating manual reconciliation across locations
- Mentored 5 developers through architecture walkthroughs and code reviews

### GPrime CRM (Dubai) — Vehicle Leasing & Trading Platform
Owned end-to-end delivery of a multi-tenant Modular Monolith CRM for Gargash Prime using Clean Architecture and CQRS/MediatR, built on .NET, MySQL, and Azure.

- Delivered the AutoTraderz online lease journey: OTP login, KYC checks, approval workflow, e-signed contracts, and webhook-based payments
- Designed a lease pricing engine with rate cards, residual values, mileage plans, and CI-validated reference quotes
- Built a daily Speed VLS integration syncing leases, vehicles, and customers without overwriting CRM-only data
- Built inventory and service modules: appointments with reminders, replacement vehicles, and mileage tracking
- Implemented tenant isolation, role-based permissions, and Microsoft Entra ID SSO
- Added lead capture from Meta Lead Ads and website forms with email notifications via Microsoft Graph
- Set up Azure delivery: Container Apps, Static Web Apps, GitHub Actions CI/CD with OIDC, and Bicep templates
- Built the buy journey: showrooms, vehicle configurator, saved vehicles, and test-drive booking

### Mahaana (Pakistan) — AI-Powered Investment Platform *(Y Combinator–backed)*
Built and owned core backend microservices for [Mahaana](https://mahaana.com), a regulated FinTech platform serving thousands of investors and employer accounts.

- Developed services for risk profiling, portfolio rebalancing, and automated transaction processing
- Implemented secure transaction pipelines with strong consistency guarantees, signed off by external compliance auditors
- Built employer and admin portals with Blazor Server for fund management and operational oversight
- Partnered with architects to define service boundaries and integration contracts for a loosely coupled distributed system
- Platform passed regulatory and investor due-diligence audits

### NBHX Rolem SRL (Romania) — Warehouse Management System
Designed a warehouse platform integrating Zebra RFID hardware for real-time inventory tracking.

- Delivered sub-second inventory visibility across all storage zones using 4–8 antenna RFID arrays
- Built backend services processing thousands of RFID events per hour for stock sync, adjustments, and transfers
- Created reporting dashboards that reduced stock discrepancy resolution time by ~40%

---

## Tech Stack

| Category | Technologies |
|---|---|
| Languages & Frameworks | C#, ASP.NET Core, Minimal APIs, Blazor, Angular, TypeScript, RxJS, NgRx |
| Architecture | Clean Architecture, CQRS/MediatR, Domain-Driven Design, Vertical Slice, Modular Monolith, Microservices, Event-Driven, Saga Pattern |
| Cloud (Azure) | App Services, Functions, Container Apps, Static Web Apps, Container Registry, Key Vault, Blob Storage, Service Bus, Computer Vision |
| DevOps | Docker, GitHub Actions, Bicep |
| Databases & ORM | SQL Server, PostgreSQL, MySQL, MongoDB, Cosmos DB, Redis, EF Core, Dapper |
| Messaging | Azure Service Bus, RabbitMQ, Kafka, MassTransit |
| Auth & Security | OAuth 2.0, OpenID Connect, JWT, Microsoft Entra ID, Azure AD B2C, Keycloak |
| Testing & Observability | xUnit, NUnit, Moq, FluentAssertions, TDD, Application Insights, OpenTelemetry |
| AI & Integrations | MCP Servers, RAG, Anthropic Claude, Microsoft Copilot, Microsoft Graph, Microsoft Teams, Tesseract OCR |

<p>
  <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square" alt="C#">
  <img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET">
  <img src="https://img.shields.io/badge/Blazor-512BD4?style=flat-square&logo=blazor&logoColor=white" alt="Blazor">
  <img src="https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white" alt="Angular">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square" alt="Azure">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square" alt="SQL Server">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" alt="RabbitMQ">
  <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Kafka">
  <img src="https://img.shields.io/badge/Claude_MCP-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude MCP">
</p>

---

## Certifications

| Certification | Code | Issued |
|---|---|---|
| Microsoft Certified: Azure Developer Associate | AZ-204 | Jul 2026 |
| Microsoft Certified: Azure Fundamentals | AZ-900 | Aug 2026 |

### Professional Development
- The .NET Senior Playbook — Anton Dev Tips (Sep 2026)
- System Design Questions — Anton Dev Tips (Sep 2026)
- Claude Code for .NET Developers — Anton Dev Tips (Sep 2026)

---

## Current Focus

Exploring AI-assisted development with Claude Code, including:
- Building MCP servers
- CLAUDE.md and Skills authoring, subagents, and quality-gated workflows
- Integrating AI tooling into existing enterprise codebases, not just greenfield demos

---

<p align="center">
  <em>Open to discussing enterprise architecture, .NET, and cloud-native systems. Feel free to reach out.</em>
</p>
