# Awesome-AML-Transaction-Monitoring

# Top AML Transaction Monitoring Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Anti-Money Laundering Transaction Monitoring, Fraud Detection, Case Management, Sanctions/PEP Screening & Financial Crime Compliance*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AML Transaction Monitoring**. These systems detect suspicious transactions in real time or batch, score risk, support investigations and SARs, and help banks, fintechs, and crypto platforms meet anti-money laundering and counter-terrorist financing obligations.

**Examples** include ComplyAdvantage, Feedzai, NICE Actimize, Oracle Financial Crime and Compliance / FCCM, FICO TONBELLER, ThetaRay, Napier AI, Flagright, Unit21, AMLYZE, SAS AML, Fenergo, and Quantexa (the category leaders).

**Open-source emphasis**: Enterprise AML transaction monitoring is dominated by commercial vendors. Meaningful open options exist—especially **Jube** (full open-source AML/fraud TM) and **Marble** (decision engine for fraud/AML)—plus research and crypto-focused tools. This section lists every significant relevant project found.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[NICE Actimize](https://www.niceactimize.com/)**  
  Enterprise financial crime platform covering AML transaction monitoring, fraud, and related compliance workflows used by large banks.

- **[Feedzai](https://www.feedzai.com/)**  
  AI-powered risk management platform for fraud and AML, with real-time transaction monitoring and case management for banks and payment companies.

- **[ComplyAdvantage](https://complyadvantage.com/)**  
  AML data and screening platform with transaction monitoring and ongoing monitoring capabilities, widely used by fintechs and financial institutions.

- **[Oracle Financial Crime and Compliance / FCCM, SAS AML, FICO TONBELLER](https://www.oracle.com/)**  
  Enterprise financial crime and compliance suites offering transaction monitoring, case management, and regulatory reporting.

- **[ThetaRay, Napier AI, Quantexa, Fenergo](https://www.thetaray.com/)**  
  AI and graph-based platforms for AML detection, network analysis, and client lifecycle / compliance workflows.

- **[Flagright, Unit21, AMLYZE](https://www.flagright.com/)**  
  Modern, often API-first transaction monitoring and case management platforms popular with fintechs and digital banks.

- **[Other commercial AML & financial crime platforms](https://www.niceactimize.com/)**  
  Additional solutions for sanctions screening, trade finance AML, and holistic financial crime risk management.

## Open-Source GitHub Projects

- **[Jube](https://github.com/jube-home/aml-fraud-transaction-monitoring)**  
  Full open-source (AGPLv3) AML and fraud detection platform for real-time transaction monitoring, hybrid rules + machine learning, risk scoring, and workflow-driven case management—designed for compliance teams and fintechs with data under their control.

- **[Marble](https://github.com/checkmarble/marble)**  
  Open-source real-time decision engine for fraud and AML—transaction monitoring, sanctions/PEP-style screening workflows, continuous monitoring, and AI-assisted investigation; self-hosted option with optional enterprise features.

- **[Enterprise-style AML TM research systems](https://github.com/dirumisra/aml-transaction-monitoring)**  
  Open projects demonstrating large-scale transaction pipelines, ML risk models (e.g. XGBoost), SHAP explainability, and GenAI-assisted SAR drafting for learning and prototyping.

- **[Crypto / on-chain AML tools](https://github.com/search?q=crypto+AML+OR+KYT+OR+on-chain+AML+open+source)**  
  Open platforms for address (KYA) and transaction (KYT) screening, wallet risk scoring, and continuous monitoring of blockchain transfers (e.g. AMLClaw-style and FINOS OpenAML research).

- **[Rules engines & decision platforms](https://github.com/search?q=transaction+monitoring+OR+fraud+rules+engine+open+source)**  
  Open rule and decision engines that teams adapt for simple threshold and scenario-based monitoring.

- **[Case management open components](https://github.com/search?q=case+management+OR+investigation+workflow+open+source)**  
  Workflow and case tools that can support AML investigation processes when integrated with detection engines.

- **[Graph analytics for financial crime](https://github.com/search?q=graph+AML+OR+network+analysis+money+laundering)**  
  Open graph libraries and demos used to surface networks of accounts and counterparties in investigations.

- **[Explainable ML for compliance](https://github.com/search?q=SHAP+OR+explainable+AI+transaction+monitoring)**  
  Tooling for model explainability often required in regulated AML model risk management.

### Additional Strong Open-Source Options

- **Full open TM platforms**: Jube as the most complete open-source AML/fraud transaction monitoring system; Marble as a flexible decision engine alternative.
- **Crypto compliance**: On-chain KYA/KYT open tools for digital asset businesses.
- **Research & prototypes**: Large-scale ML pipelines with explainability for education and PoCs.
- **Composable stacks**: Streaming ingest + rules/ML scoring + case workflow + audit log for custom monitoring.
- Enterprise multi-jurisdiction scenarios, managed typology libraries, and regulator-facing reporting remain commercial strengths.

**Frameworks for building custom systems**:  
**Jube** and **Marble** are the strongest open foundations for real-time AML/fraud monitoring and case handling.  
Crypto-focused open tools cover on-chain screening.  
Commercial platforms (Actimize, Feedzai, ComplyAdvantage, Oracle, SAS, ThetaRay, Flagright, Unit21, etc.) deliver typology coverage, scale, regulatory experience, and managed data.  
Regulated banks typically use commercial AML systems; fintechs and crypto firms sometimes combine open engines with commercial screening data or use open platforms where governance allows. Fully open stacks require strong model risk management, audit trails, and legal review before production use.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- AML transaction monitoring is a regulated activity. Incorrect or incomplete monitoring can lead to regulatory penalties, criminal exposure, and reputational harm. Open-source software does not replace qualified compliance programs, policies, or legal advice.
- Before using any system (open or commercial) for production monitoring, ensure model validation, explainability, data quality, case-handling procedures, and alignment with applicable AML/CFT laws in your jurisdictions. Self-hosted open tools require you to own security, availability, and auditability.

---

**Made for compliance officers, financial crime teams, fintech builders, and AML technologists.**  
Let's expand transparent, auditable options for transaction monitoring while recognizing the typology depth, scale, and regulatory maturity that leading commercial AML platforms deliver.
