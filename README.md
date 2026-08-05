# Awesome-Payment-Reconciliation-Platform

## Top Payment Reconciliation Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Automated Transaction Matching, Bank & Payment Reconciliation, Financial Close & Operational Intelligence*  
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Payment Reconciliation**. These tools automate matching of transactions across banks, payment processors, ERPs, ledgers, and internal systems; manage exceptions; support audit trails; and accelerate financial close processes for finance teams, banks, fintechs, and enterprises.

**Examples** include Numeric, BlackLine, ReconArt, Trintech Adra, Fiserv Frontier Reconciliation, AutoRek, SmartStream TLM, Duco, SolveXia, and OneStream (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom matching engines, bank statement processing, multi-source reconciliation, and open financial data pipelines — ideal for finance teams, developers, fintechs, and researchers building transparent, auditable reconciliation solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Description | Pricing | Free Tier Limit |
|----------|-------------|---------|-----------------|
| **[Numeric](https://www.numeric.io/)** | AI-powered financial close and real-time account/cash reconciliation platform with deep ERP integrations and high auto-match rates. | Custom / Starts at ~$30/user/mo | N/A |
| **[BlackLine](https://www.blackline.com/)** | Enterprise-grade cloud platform for account reconciliation, transaction matching, journal entry automation, and financial close management. | Custom / Contact Sales | N/A |
| **[ReconArt](https://www.reconart.com/)** | Configurable web-based reconciliation and financial close platform supporting high-volume multi-way matching, exception management, and balance sheet certification. | Custom / Contact Sales | N/A |
| **[Trintech Adra](https://www.trintech.com/adra/)** | Mid-market financial close suite with multi-way transaction matching, balance sheet reconciliations, task management, and journal entry automation. | Custom / Contact Sales | N/A |
| **[Fiserv Frontier Reconciliation](https://www.fiserv.com/)** | Enterprise end-to-end reconciliation and certification solution for high-volume bank, payment, and inter-system matching with strong audit controls (now under Trintech). | Custom / Contact Sales | N/A |
| **[AutoRek](https://www.autorek.com/)** | No-code, AI-enhanced reconciliation and financial control platform for banks, payments, insurance, and asset management with regulatory rulebooks. | Custom / Contact Sales | N/A |
| **[SmartStream TLM](https://www.smartstream-stp.com/)** | Transaction Lifecycle Management reconciliation platform specializing in high-volume trade, cash, and collateral matching for capital markets and banks. | Custom / Contact Sales | N/A |
| **[Duco](https://www.du.co/)** | Cloud-native data reconciliation and automation platform focused on complex, high-volume matching and exception handling in financial services. | Custom / Contact Sales | N/A |
| **[SolveXia](https://www.solvexia.com/)** | No-code automation platform for multi-source data reconciliation, variance analysis, and workflow-driven financial processes. | Custom / Contact Sales | N/A |
| **[OneStream](https://www.onestream.com/)** | Unified corporate performance management platform with embedded account reconciliation, consolidation, and close automation capabilities. | Custom / Contact Sales | N/A |

## Open-Source GitHub Projects

- **[OpenRec](https://github.com/GrandmasterTash/OpenRec)**  
  Blazingly fast reconciliation matching engine written in Rust; processes CSV data with YAML/Lua rules, low memory footprint, and high throughput for enterprise-scale matching.

- **[Lerian Matcher](https://github.com/LerianStudio/matcher)**  
  Open-source multi-tenant transaction reconciliation engine in Go with configurable rules, confidence scoring, fee verification, exception workflows, and SOX-ready immutable audit trails.

- **[Reunion](https://github.com/imazen/reunion)**  
  Library and webapp for repeatable, evidence-based expense/income accounting with automatic reconciliation against balances, multi-currency support, and Git-friendly diffs.

- **[ALYF Banking](https://github.com/alyf-de/banking)**  
  ERPNext/Frappe app for loading bank transactions (via EBICS and other feeds) and reconciling them with vouchers; includes improved free bank reconciliation tools.

- **[Mint](https://github.com/The-Commit-Company/mint)**  
  Open-source bank reconciliation tool for ERPNext with React UI, fuzzy search, visual matching cues, payment entry creation, and multi-account support.

- **[Matcha](https://github.com/Negentropy-Solutions/matcha)**  
  Faster payment-to-invoice reconciliation app for ERPNext with two-panel workspace, multi-currency allocation, and cross-company (intercompany) support.

- **[OCA Account Reconcile](https://github.com/OCA/account-reconcile)**  
  Comprehensive Odoo Community Association modules for bank statement reconciliation, mass reconcile, models, wizards, and advanced matching features.

- **[OpenReconFI](https://github.com/developedbygeo/OpenReconFI)**  
  Self-hosted agency finance ops platform with LLM-powered bank reconciliation, invoice extraction, vendor management, and RAG expense chat.

- **[ReconBanker](https://github.com/ignaciogarcia-dev/reconbanker)**  
  Self-hosted bank-to-order reconciliation engine using browser automation for statements, heuristic matching, and webhook notifications.

- **[payments-ledger-engine](https://github.com/jzwerg/payments-ledger-engine)**  
  Correct, idempotent double-entry ledger with ISO 20022 payment processing and built-in reconciliation engine proving exactly-once semantics.

- **[opnreco](https://github.com/OpenPaymentNetwork/opnreco)**  
  Open Payment Network reconciliation tool for matching OPN activity against bank accounts, aimed at issuers.

- **[jPOS](https://jpos.org/)**  
  Mature open-source Java platform for ISO-8583/ISO-20022 payment messaging, switches, and transaction processing infrastructure used in production gateways worldwide.

- **[Firefly III](https://github.com/firefly-iii/firefly-iii)**  
  Popular self-hosted personal/business finance manager with double-entry bookkeeping, rule-based import cleaning, and bank statement reconciliation features.

- **[LedgerSMB](https://ledgersmb.org/)**  
  Open-source ERP/accounting system with robust multi-currency GL, receivables/payables, and bank reconciliation capabilities.

- **[open-accounting](https://github.com/HMB-research/open-accounting)**  
  Self-hosted multi-tenant accounting platform with bank import, auto-matching, and full reconciliation workflows.

### Additional Strong Open-Source Options

- **Bank statement parsers & CSV matching libraries** (Python/Go/Rust) for custom reconciliation pipelines.
- **ERPNext / Odoo / Frappe banking & reconcile modules** and community extensions.
- **ISO 20022 / camt.053 / MT940 parsers** and payment message processing tools.
- **Heuristic & subset-sum matching algorithms** for bundled payments and multi-invoice reconciliation.
- **InfluxDB + Grafana + Node-RED** or similar stacks for real-time transaction monitoring dashboards.
- **LangGraph / LLM agents** for intelligent exception classification and suggested matches.
- Many community **AIS-style** (but for payments) data interchange, sensor-style bank feed, and multi-source fusion projects.

**Frameworks for building custom systems**: Combine **OpenRec** or **Lerian Matcher**, **Odoo/ERPNext reconcile modules**, **Firefly III** or **LedgerSMB**, **jPOS**, and **PostgreSQL + audit logging** with optional LLMs for intelligent, self-hosted payment reconciliation platforms.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Payment reconciliation tools must comply with financial regulations (SOX, PCI-DSS, local banking rules, etc.).
- Self-hosted open-source solutions require proper financial-grade security, auditability, and reliability.

---

**Made for finance teams, controllers, fintech engineers, banks, and payment operations specialists.**  
Let's make payment reconciliation more open, automated, and transparent.
