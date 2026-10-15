# Ivan Shalganov

**Technical Lead · Platform & Systems Architect · SRE / Cloud Platforms · AI Agents**

Amsterdam, Netherlands · a.cobest@gmail.com · [Telegram](https://t.me/bezumen) · [GitHub](https://github.com/bzick) · Русская версия: [resume.md](resume.md)

## Summary

Engineer and technical lead with 20+ years of commercial experience designing and running production systems end to end: cloud platforms, high-load SaaS, distributed services, infrastructure, business-critical services and AI agents. I understand how IT systems work at every layer — from the OS, networking and runtimes to clouds, Kubernetes and the business requirements on top — and I design applications of any type around that understanding.

Go is my main language; other languages are tools I pick to fit the problem. Today most of my work is architecture, platform design, technical leadership and making AI agents do real work reliably.

I work with AI on a zero-trust basis and never vibe-code blindly. I set up and steer AI systems to reach a goal efficiently and, above all, safely; I read and dig into everything AI produces, and no AI-generated code reaches production until I understand how it works and it is proven correct and secure. I know where AI is strong and where it fails, and I can keep control in an environment flooded with vibe code from clients and users — governing the flow of AI-generated changes into production.

## Core competencies

- **System and application architecture:** distributed systems, microservices, high-load, horizontal scaling, SLAs, service interaction design
- **Platform engineering:** self-service internal cloud on Kubernetes, custom controllers, custom CRI/runtime, multi-cloud (AWS, GCP, on-prem)
- **SRE and operations:** observability, incident response and root-cause analysis, on-call process design, reliability of business-critical services
- **AI engineering and AI control:** configuring and orchestrating AI agents for real tasks; zero-trust approach to AI output — strict review and verification of everything agents write and do, human-in-the-loop, guardrails and least-privilege access for agents, evals to measure quality and catch regressions; agent harness, local LLM inference
- **AI-generated code governance:** no unverified vibe code in production — every AI-written change is read, understood and checked for correctness and security before release; controlling the flow of AI-generated code from clients and users into production; deep knowledge of AI strengths and failure modes
- **Design and long-term operation of services:** extensive experience designing and running business-critical production services with heavy operational load (toil) — keeping them stable under constant change and cutting toil through automation and AI agents
- **Technical leadership:** technical strategy, architecture decisions, stakeholder alignment, mentoring, hiring and growing engineers, building team processes

## Experience

### JetBrains — Amsterdam, Netherlands

SRE (Cloud Solutions) team, IT department.

**Technical Lead** · Feb 2026 – present (combined with Senior SDE)

- Own the team's technical strategy and architecture decisions; mentor engineers.
- Drove the design of the internal platform's Kubernetes controllers and aligned stakeholders across the company on how they should work.
- Built the on-call process for the company-wide SRE support channel (infrastructure issues, platform questions, how-tos): a small rotation of developers resolves almost all requests without escalation — incidents within minutes, questions the same day.
- Lead AI adoption in the team: AI agents that reduce on-call load, plus personal agents for colleagues (DevOps agent, legal agent), with a focus on agent reliability — getting agents to do real work well with minimal errors. Also explore self-hosted LLM inference for internal use.

**Senior Software Development Engineer** · Jun 2022 – present

- Design and build a self-service internal cloud platform on Kubernetes, used by every team in the company across a multi-cloud fleet (GKE, EKS, on-prem). Engineers without Kubernetes knowledge ship to production on their own.
- Designed and developed custom Kubernetes controllers for the platform; infrastructure as code and supporting services.
- Built a custom CRI and container runtime to run Kubernetes pods natively on macOS (Kubernetes has no macOS support) across a large Mac mini fleet.
- Develop and maintain the company-wide HSM-backed code signing service (Windows, macOS incl. notarization, Linux, JAR and more) — a mandatory step of every JetBrains software release. Turned a working but fragile setup into a stable, scaled service.
- Built AI agents that assist the on-call engineer and automate ticket handling, a harness for managing agents, and self-service LLM evals on Kubernetes.

### Megagroup — Saint Petersburg, Russia

Company behind a no-code website builder and CMS (SaaS).

**Technical Lead / Architect** · Jul 2017 – May 2022

- Owned the architecture and technology stack of the company's SaaS platform and supporting services; designed applications together with their infrastructure and SLAs.
- Designed and governed interactions between the company's microservices.
- Led development teams: shaped processes, interviewed, assessed and trained engineers.
- Led projects end to end — requirements, planning, delivery, maintenance and decommissioning.
- Drove systematic reduction of technical debt and legacy code.
- Owned reliability: monitoring of performance and availability, incident response and root-cause analysis.
- Designed and built the company's compute cluster.

**Full-stack Developer** · Feb 2009 – May 2022

- Built and evolved the main SaaS product: microservice architecture with horizontal scaling, ~3,000 RPS on average and ~6,000 RPS at peak, 200+ TiB of static content, many internal and external integrations.
- Built services for traffic and page-speed analytics, monitoring and alerting, streaming data generation, file processing, SSL/TLS certificate management, proxying, audit and backups.
- Built a caching CDN layer on Nginx/OpenResty and native extensions for performance-critical paths.

### Earlier experience · 2004 – 2009

Full-stack development of an internal CRM/ERP system (Internet LLC); freelance web development and my own commercial web services.

## Programming languages

- **Go — main language since 2018.** Kubernetes controllers, a custom CRI and container runtime, platform services, high-load microservices with many concurrent connections, high RPS and large input streams, libraries.
- **PHP** — 18 years, including writing PHP extensions in C; know its internals inside out.
- **C** (C99) — 10 years: libraries, PHP and Lua extensions, C via FFI.
- **Lua** (LuaJIT, 5.1) — 6 years: Nginx/OpenResty and Redis, caching CDN, auxiliary services.
- **JavaScript** (ES6) — 18 years.
- **Bash/shell** — fluent scripting.

## Technologies

- **Cloud and infrastructure:** Kubernetes, AWS, GCP, on-prem, Terraform, Pulumi, Docker, Linux, Nginx/OpenResty, HSM
- **Observability:** Prometheus, Thanos, VictoriaMetrics, Loki, Grafana, ELK
- **Data:** MySQL/MariaDB/Percona XtraDB Cluster, MongoDB, ClickHouse, Redis, Elasticsearch, Kafka
- **AI:** AI agents, agent harnesses, LLM evals, exo, vLLM
## Open source

Author of open source projects with own GitHub organizations ([fenom-template](https://github.com/fenom-template), [php-ion](https://github.com/php-ion), [unifire-app](https://github.com/unifire-app)):

- [Tokenizer](https://github.com/bzick/tokenizer) — Go tokenizer for unbounded data streams.
- [PHP-ION](https://github.com/php-ion/php-ion) — asynchronous, Node.js-style runtime extension for PHP, written in C.
- [Fenom](https://github.com/fenom-template/fenom) — template engine for PHP.
- [Aspect](https://unifire-app.github.io/aspect/) and [Nginx Red](https://github.com/bzick/nginx-red) — Lua/OpenResty projects.
- [Oh My Backend](https://github.com/bzick/oh-my-backend) — roadmap for backend developers.

## Education

Saint Petersburg State University — Master's level degree, Applied Mathematics and Control Processes (Mathematician, Systems Programmer), 2008.
