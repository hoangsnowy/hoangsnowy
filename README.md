<h1 align="center">Nguyen Minh Hoang | hoangsnowy</h1>

<p align="center">
  <b>Software Architect | .NET Platform | Cloud-Native Systems</b>
</p>

<p align="center">
I design scalable architecture that helps teams ship faster, safer, and with less long-term technical debt.
</p>

<p align="center">
  <a href="https://github.com/hoangsnowy"><img src="https://img.shields.io/badge/GitHub-hoangsnowy-181717?style=flat-square&logo=github" /></a>
  <a href="https://www.linkedin.com/in/hoangsnowy"><img src="https://img.shields.io/badge/LinkedIn-hoangsnowy-0A66C2?style=flat-square&logo=linkedin" /></a>
  <a href="mailto:nguyenminhhoang.dit12@gmail.com"><img src="https://img.shields.io/badge/Email-contact-D14836?style=flat-square&logo=gmail" /></a>
</p>

---

## Architect Positioning

I am a `Software Architect` with 10+ years building production systems on `.NET` and `Azure`.

My focus is to turn complex business domains into clear technical architecture that teams can implement and evolve with confidence.

**What I lead**
- Architecture strategy for enterprise and platform products
- Domain modeling with DDD, Clean Architecture, CQRS, and event-driven design
- Platform engineering for reusable internal frameworks and developer tooling
- Reliability and operability across CI/CD, observability, and cloud runtime

---

## Architecture Strengths

| Capability | How I execute | Outcome |
|---|---|---|
| System Design | Define bounded contexts, service boundaries, and integration contracts | Reduced coupling and safer delivery |
| Platform Architecture | Build shared abstractions for infra concerns | Faster feature delivery across teams |
| Cloud-Native Engineering | Design for resilience, scaling, and observability on Azure | Stable systems under load |
| Engineering Governance | Set standards, ADRs, and technical guardrails | Consistent architecture decisions |

---

## Flagship Proof: Jaina .NET

`Jaina .NET` is my core framework project and a direct reflection of my architecture approach.

[![GitHub](https://img.shields.io/badge/GitHub-jaina--dotnet-181717?style=flat-square&logo=github)](https://github.com/hoangsnowy/jaina-dotnet)
[![Build](https://img.shields.io/github/actions/workflow/status/HoangSnowy/jaina-dotnet/build.yml?branch=main&style=flat-square)](https://github.com/HoangSnowy/jaina-dotnet/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](https://github.com/hoangsnowy/jaina-dotnet/blob/main/LICENSE)

**Why it matters**
- Abstraction-first design: app code depends on contracts, not vendor SDKs
- Provider swap with minimal change: Redis <-> Memory, RabbitMQ <-> Azure Service Bus, SFTP <-> Azure Blob
- Modular architecture for cache, data, messaging, storage, security, diagnostics
- Production mindset: testability, observability, and operational readiness built in

```text
Application Layer
    -> Jaina Abstractions (ICache, IQueue<T>, IFileStorage, ITelemetry)
        -> Infrastructure Providers (Redis, RabbitMQ, Azure Blob, App Insights, ...)
```

---

## Selected Projects

| Repository | Role |
|---|---|
| [jaina-dotnet](https://github.com/hoangsnowy/jaina-dotnet) | Architect and primary builder of a modular .NET framework |
| [FlowOrchestrator](https://github.com/hoangsnowy/FlowOrchestrator) | Creator of a reusable .NET workflow orchestration library |
| [pgp-sftp-lab-demo](https://github.com/hoangsnowy/pgp-sftp-lab-demo) | Secure integration blueprint with PGP and SFTP |

---

## Highlight Library: FlowOrchestrator

`FlowOrchestrator` is a focused orchestration library for modeling multi-step business flows with clean, testable execution paths.

[![GitHub](https://img.shields.io/badge/GitHub-FlowOrchestrator-181717?style=flat-square&logo=github)](https://github.com/hoangsnowy/FlowOrchestrator)

**Why it is useful**
- Encapsulates workflow steps and transitions into explicit flow definitions
- Keeps orchestration concerns separate from application and infrastructure code
- Makes complex business processes easier to reason about and test

---

## Core Stack

<p align="center">
  <img src="https://img.shields.io/badge/.NET_8-informational?style=flat-square&logo=dotnet" />
  <img src="https://img.shields.io/badge/C%23-blue?style=flat-square&logo=c-sharp" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker" />
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis" />
  <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm" />
  <img src="https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops" />
</p>

---

## GitHub Stats

<p align="center">
  <img src="https://streak-stats.demolab.com?user=hoangsnowy&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=hoangsnowy&theme=github_dark" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=hoangsnowy&theme=github_dark" />
</p>

---

<p align="center"><i>Architecture is about making hard-to-change decisions deliberately, with business outcomes in mind.</i></p>
