# Awesome-Transaction-Monitoring

## Top Transaction Monitoring Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on AML Transaction Monitoring, Fraud Detection, Sanctions Screening, Behavioral Analytics, Case Management & Regulatory Compliance*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Transaction Monitoring**. These tools analyze financial transactions in real time or batch to detect money laundering, fraud, sanctions violations, and other financial crime patterns while supporting investigation workflows and regulatory reporting.

**Examples** include Feedzai, Actimize, Featurespace, ComplyAdvantage, Lucinity, Flagright, SEON, Unit21, FICO TONBELLER, and SAS AML (the category leaders).

**Open-source emphasis**: Fully enterprise-grade open-source transaction monitoring platforms are still emerging. This section is expanded with the strongest available open-source decision engines, AML/fraud detection systems, rules engines, and research projects that fintechs and compliance teams can self-host or extend.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Capabilities | Starting Pricing | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[SEON](https://seon.io/)** | Fraud prevention and AML platform combining device intelligence, digital footprint analysis, and real-time transaction monitoring. | **$699 / month** (Starter/Pro tier with 10+ QPS) | **Forever Free plan**: Up to 2,000 API calls/month (2 QPS rate limit, email support) or 14-day full-feature free trial (no credit card required). |
| **[ComplyAdvantage](https://complyadvantage.com/)** | AI-native AML platform offering real-time sanctions/PEP screening, transaction monitoring, and risk intelligence. | **$99 / month** (billed annually at $1,188/yr) or $119/mo (billed monthly) for up to 100 monitored entities | **ComplyLaunch program**: 12 months free access for eligible early-stage startups; standard plans offer guided interactive sandbox demo. |
| **[Flagright](https://www.flagright.com/)** | Real-time AML and fraud prevention platform designed for fintechs and payment companies with API-first architecture. | **~$30,000 / year** (~$2,500/month) base volume tier | **Startup Program**: 1st year free (12 months full platform access) for eligible early-stage startups; or 14-day guided POC trial upon request. |
| **[Unit21](https://www.unit21.ai/)** | No-code/low-code transaction monitoring, alert triage, and case management platform popular with fintech compliance teams. | **~$33,000 / year** (~$2,750/month) base contract for entry transaction volume tiers | **30-day guided POC sandbox**: Access with synthetic financial crime datasets for qualified prospective teams upon sales request. |
| **[Lucinity](https://www.lucinity.com/)** | Modern AML and transaction monitoring platform focused on AI-assisted investigations, actor-centric profiles, and reduced false positives. | **~$54,000 / year** (~$4,500/month) base subscription or SLA-based completed work pricing | **14-day interactive demo sandbox**: Preloaded with realistic AML scenario data to test alert handling and Copilot investigation tools. |
| **[Feedzai](https://www.feedzai.com/)** | AI-powered risk management platform combining fraud and AML transaction monitoring with strong model explainability for banks and payment institutions. | **~$60,000 / year** base SaaS subscription (available via AWS Marketplace) | **60-day targeted POC trial**: Available for qualified financial institutions alongside a complimentary risk intelligence briefing. |
| **[NICE Actimize](https://www.niceactimize.com/)** | Enterprise financial crime platform widely used by Tier 1/2 banks for AML transaction monitoring, fraud detection, and case management with deep core-banking integrations. | **~$50,000 / year** entry tier for mid-market/essentials deployments (scaling to $200k–$500k+ for full enterprise suite) | **30-day guided enterprise POC**: Dedicated sandbox environment with integration testing for qualified institutions upon request. |
| **[Featurespace](https://www.featurespace.com/)** | Adaptive behavioral analytics platform (ARIC Risk Hub) specializing in real-time fraud and financial crime detection using machine learning. | **~$75,000 / year** base SaaS contract (available via AWS Marketplace private offer) | **30-day POC sandbox**: Tailored testing environment with simulated transaction streams for enterprise evaluation. |
| **[SAS Anti-Money Laundering](https://www.sas.com/)** | Comprehensive AML suite from SAS offering transaction monitoring, customer due diligence, and regulatory reporting on the SAS Viya analytics engine. | **~$100,000 / year** base enterprise subscription on SAS Cloud / Viya platform | **14-day SAS Viya free trial**: Includes up to 1GB data upload, preloaded analytical models, and up to 5 user collaboration seats. |
| **[FICO TONBELLER](https://www.fico.com/)** | Established AML and compliance suite (FICO Siron AML) covering transaction monitoring, KYC, and financial crime risk management. | **~$180,000 / year** base enterprise contract for the compliance & decision management suite | **30-day guided pilot / POC**: Evaluation sandbox with custom rule calibration and typology simulation for enterprise prospects. |

## Open-Source GitHub Projects
- **[Marble](https://github.com/checkmarble/marble)**  
  Open-source real-time decision engine for fraud and AML, supporting transaction monitoring, sanctions/PEP screening, and AI-assisted case investigation with self-hosted options.

- **[Osprey](https://github.com/opensource-finance/osprey)**  
  Lightweight open-source transaction monitoring service using CEL rules and FATF typologies, deployable as a single Go binary.

- **[Jube](https://github.com/jube-home/aml-fraud-transaction-monitoring)**  
  Fully open-source (AGPLv3) AML and fraud detection platform for real-time transaction monitoring, hybrid rules + ML, and case management.

- **[OpenAML / FINOS projects](https://github.com/finos-labs)**  
  Open-source initiatives under FINOS focused on on-chain and intelligent AML detection, risk scoring, and compliance frameworks.

- **[AML transaction monitoring research systems](https://github.com/)**  
  Enterprise-style open projects demonstrating ML pipelines (XGBoost, SHAP explainability), SAR generation, and dashboards on large transaction datasets.

- **[Rules engines for transaction monitoring](https://github.com/)**  
  Open-source rule engines and DSLs (e.g., CEL-based or custom) for defining and executing fraud/AML detection logic.

- **[Graph-based AML detection tools](https://github.com/)**  
  Projects using graph embeddings and network analysis to identify suspicious money-flow patterns and layering.

- **[Fraud and anomaly detection libraries](https://github.com/)**  
  Open ML libraries and streaming frameworks commonly used to build custom real-time transaction scoring systems.

- **[Case management and investigation open tools](https://github.com/)**  
  Lightweight open platforms for alert triage, investigation workflows, and documentation that can sit on top of detection engines.

- **[Sanctions and watchlist open data pipelines](https://github.com/)**  
  Community tools for ingesting and matching against public sanctions, PEP, and adverse media lists.

### Additional Strong Open-Source Options
- Apache Flink / Kafka Streams pipelines for real-time transaction scoring.
- Custom XGBoost / isolation-forest models trained on synthetic or anonymized data (e.g., IBM AMLSim).
- Open SAR/STR template and reporting helpers.
- Graph databases (Neo4j community, etc.) for entity-link analysis.
- Integration examples connecting open monitoring engines to core banking or payment APIs.

**Frameworks for building custom systems**: Deploy a rules + ML engine such as **Marble**, **Osprey**, or **Jube** for real-time scoring, enrich with open sanctions data, store alerts in a case-management layer, and use SHAP or similar for explainability. Orchestrate with Kafka or similar for high-volume streams and visualize in Grafana or a custom dashboard. This stack provides full data control and auditability, though production AML systems still require rigorous model validation, typology coverage, and regulatory examination readiness.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Transaction monitoring systems are subject to strict regulatory requirements (AML, sanctions, SAR filing, model risk management). Open-source solutions offer transparency and cost advantages but generally need significant customization, independent validation, and ongoing governance before they can serve as a regulated institution’s primary compliance system.
- Always consult legal, compliance, and risk teams and ensure any solution meets applicable jurisdictional requirements.

---
**Made for compliance officers, fraud analysts, and fintech teams building or evaluating transaction monitoring capabilities.**
Let's make financial crime detection more transparent, adaptable, and community-supported where appropriate.
