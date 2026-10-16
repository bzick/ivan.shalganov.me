# Ivan Shalganov

**Technical Lead & Senior Software Engineer · Cloud Platform & SRE · Go, Kubernetes**

Amsterdam, Netherlands · <a.cobest@gmail.com> · [Telegram](https://t.me/bezumen) · [GitHub](https://github.com/bzick) · [LinkedIn](www.linkedin.com/in/ivan-shalganov-283397213)

## Summary

Backend and platform engineer with 20+ years of experience building and operating production systems — cloud platforms, high-load SaaS and distributed services. Go is my main language. At JetBrains I build a multi-cloud Kubernetes platform used by every team in the company and designed the SRE on-call process, so I rely on observability daily to troubleshoot production. Earlier, at Megagroup, I built monitoring, alerting and analytics services for a high-load SaaS. Recently focused on AI agents that help the on-call engineer — built with strict human-in-the-loop control and verification.

## Core competencies

- **SRE and operations:** incident response and root-cause analysis, on-call process design, reliability of business-critical services; monitoring and alerting
- **Distributed backend systems:** high-load services, horizontal scaling, streaming and large-volume data, service interaction design
- **Platform engineering:** self-service internal cloud on Kubernetes, custom controllers, custom CRI/runtime, multi-cloud (AWS, GCP, on-prem)
- **AI for operations:** agents for on-call triage and troubleshooting, agent harness, LLM evals; zero-trust review of everything AI produces before it reaches production
- **Technical leadership:** architecture decisions, design reviews, mentoring

## Experience

### JetBrains — Amsterdam, Netherlands

SRE (Cloud Solutions) team, IT department.

**Senior Software Development Engineer** · Jun 2022 – present (Technical Lead since Feb 2026)

- Design and build a self-service internal cloud platform on Kubernetes, used by every team in the company across a multi-cloud fleet (GKE, EKS, on-prem). Engineers without Kubernetes knowledge ship to production on their own.
- Built AI agents that assist the on-call engineer and automate ticket handling, plus the harness that manages the agents and self-service LLM evals on Kubernetes.
- Designed the on-call process for the company-wide SRE support channel: a small rotation of developers resolves almost all requests without escalation — incidents within minutes, questions the same day.
- Designed and developed custom Kubernetes controllers for the platform; infrastructure as code and supporting services.
- Built a custom CRI and container runtime to run Kubernetes pods natively on macOS across a large Mac mini fleet.
- Develop and maintain the company-wide HSM-backed code signing service (Windows, macOS incl. notarization, Linux, JAR and more) — a mandatory step of every JetBrains release. Turned a fragile setup into a stable, scaled service.
- As Technical Lead: own architecture decisions, run design reviews, mentor engineers.

### Megagroup — Saint Petersburg, Russia

Company behind a no-code website builder and CMS (SaaS).

**Technical Lead / Architect** · Jul 2017 – May 2022

- Owned the architecture and stack of the SaaS platform; designed applications together with their infrastructure and SLAs.
- Owned reliability: performance and availability monitoring, incident response and root-cause analysis.
- Designed and governed interactions between the company's microservices; designed and built the company's compute cluster.
- Led development teams: processes, hiring, mentoring; drove systematic reduction of technical debt.

**Software Engineer (Full-stack)** · Feb 2009 – Jul 2017

- Built and evolved the main SaaS product: microservice architecture with horizontal scaling, ~3,000 RPS average and ~6,000 RPS peak, 200+ TiB of static content.
- Built in-house monitoring, alerting and traffic / page-speed analytics services for the platform.
- Built services for streaming data generation, file processing, SSL/TLS certificate management, proxying, audit and backups.
- Built a caching CDN layer on Nginx/OpenResty with native extensions for performance-critical paths.

## Programming languages

- **Go — main language since 2018:** Kubernetes controllers, CRI and container runtime, platform services, high-load services with many concurrent connections and large input streams.
- **C** (C99), **Lua** (LuaJIT / OpenResty), **PHP** (incl. C extensions), **JavaScript**, **Bash**.

## Technologies

- **Observability:** Prometheus, Thanos, VictoriaMetrics, Loki, Grafana, ELK
- **Cloud and infrastructure:** Kubernetes, AWS, GCP, on-prem, Terraform, Pulumi, Docker, Linux, Nginx/OpenResty
- **Data:** ClickHouse, MySQL/Percona XtraDB Cluster, MongoDB, Redis, Elasticsearch, Kafka, SphinxSearch
- **AI:** AI agents, agent harnesses, LLM evals, vLLM, exo

## Open source

- [Tokenizer](https://github.com/bzick/tokenizer) — Go tokenizer for parsing unbounded data streams.
- [PHP-ION](https://github.com/php-ion/php-ion) — asynchronous runtime extension for PHP, written in C.
- [Fenom](https://github.com/fenom-template/fenom) — template engine for PHP.
- [Aspect](https://unifire-app.github.io/aspect/) — Lua/OpenResty projects.

## Education

Saint Petersburg State University — Master's level degree, Applied Mathematics and Control Processes, 2008.

