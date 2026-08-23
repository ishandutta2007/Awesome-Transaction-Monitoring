# Awesome-Transaction-Monitoring

# Top Transaction Monitoring Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on AML Transaction Monitoring, Fraud Detection, Sanctions Screening, Behavioral Analytics, Case Management & Regulatory Compliance*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Transaction Monitoring**. These tools analyze financial transactions in real time or batch to detect money laundering, fraud, sanctions violations, and other financial crime patterns while supporting investigation workflows and regulatory reporting.

**Examples** include Feedzai, Actimize, Featurespace, ComplyAdvantage, Lucinity, Flagright, SEON, Unit21, FICO TONBELLER, and SAS AML (the category leaders).

**Open-source emphasis**: Fully enterprise-grade open-source transaction monitoring platforms are still emerging. This section is expanded with the strongest available open-source decision engines, AML/fraud detection systems, rules engines, and research projects that fintechs and compliance teams can self-host or extend.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Feedzai](https://www.feedzai.com/)**  
  AI-powered risk management platform combining fraud and AML transaction monitoring with strong model explainability for banks and payment institutions.

- **[NICE Actimize](https://www.niceactimize.com/)**  
  Enterprise financial crime platform widely used by large banks for AML transaction monitoring, fraud detection, and case management with deep core-banking integrations.

- **[Featurespace](https://www.featurespace.com/)**  
  Adaptive behavioral analytics platform specializing in real-time fraud and financial crime detection using machine learning.

- **[ComplyAdvantage](https://complyadvantage.com/)**  
  AI-native AML platform offering real-time sanctions/PEP screening, transaction monitoring, and risk intelligence for fintechs and financial institutions.

- **[Lucinity](https://www.lucinity.com/)**  
  Modern AML and transaction monitoring platform focused on AI-assisted investigations and reduced false positives.

- **[Flagright](https://www.flagright.com/)**  
  Real-time AML and fraud prevention platform designed for fintechs and payment companies with API-first architecture.

- **[SEON](https://seon.io/)**  
  Fraud prevention and AML platform combining device intelligence, digital footprint analysis, and transaction monitoring.

- **[Unit21](https://www.unit21.ai/)**  
  No-code/low-code transaction monitoring and case management platform popular with fintech compliance teams.

- **[FICO TONBELLER](https://www.fico.com/)**  
  Established AML and compliance solutions from FICO covering transaction monitoring and financial crime risk management.

- **[SAS Anti-Money Laundering](https://www.sas.com/)**  
  Comprehensive AML suite from SAS offering transaction monitoring, customer due diligence, and regulatory reporting capabilities.

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
