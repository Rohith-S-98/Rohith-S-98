<div align="center">
  <img src="assets/profile-banner.svg" alt="Rohith S - Data Engineering Portfolio Banner" width="100%" />
</div>

<br />

<h1 align="center">Rohith S</h1>

<h3 align="center">Data Engineer II | Azure • Databricks • PySpark • Delta Lake • Reltio MDM</h3>

<p align="center">
  <b>I build production-style data pipelines that are validated, monitored, retried, documented, and explainable.</b>
</p>

<p align="center">
  <a href="https://github.com/Rohith-S-98/data-engineering-project"><img src="https://img.shields.io/badge/View_Main_Project-End_to_End_Data_Engineering-38BDF8?style=for-the-badge&logo=github&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Focus-Production_Ready_Data_Engineering-6EE7B7?style=for-the-badge" />
  <img src="https://komarev.com/ghpvc/?username=Rohith-S-98&label=Profile%20Views&color=0e75b6&style=for-the-badge" />
</p>

---

## 5-second profile summary

<table>
  <tr>
    <td align="center" width="25%"><b>Current Role</b><br />Data Engineer II<br />Apexon</td>
    <td align="center" width="25%"><b>Client Context</b><br />IQVIA<br />NextGen MDM</td>
    <td align="center" width="25%"><b>Core Stack</b><br />Azure, Databricks<br />PySpark, Delta Lake</td>
    <td align="center" width="25%"><b>Portfolio Proof</b><br />Versioned end-to-end<br />DE pipeline system</td>
  </tr>
</table>

---

## What makes this profile different

<table>
  <tr>
    <td width="33%" align="center">
      <b>Not just scripts</b><br />
      I focus on production habits: validation, audit logs, retry, recovery, SLA signals, CI/CD, and release gates.
    </td>
    <td width="33%" align="center">
      <b>Real-world data flow thinking</b><br />
      I connect source ingestion, data quality, quarantine, canonical modeling, and MDM-style JSON outputs.
    </td>
    <td width="33%" align="center">
      <b>Interview-ready explanation</b><br />
      I can explain source to bronze to silver to gold to MDM with failures, observability, and deployment readiness.
    </td>
  </tr>
</table>

---

## Featured portfolio system

<div align="center">

### [End-to-End Data Engineering Pipeline Simulator](https://github.com/Rohith-S-98/data-engineering-project)

<b>A production-style Data Engineering portfolio project built as a versioned system, not a one-time demo.</b>

<img src="assets/data-engineering-system.svg" alt="End-to-End Data Engineering System" width="100%" />

</div>

---

## End-to-End Portfolio Flow

```mermaid
flowchart LR
    A[Source Systems<br/>API / File / Database] --> B[Raw Landing Layer<br/>JSON / CSV / Input Tables]
    B --> C[Schema Validation<br/>Contracts + Required Fields]
    C --> D[Bronze Layer<br/>Initial Standardization]
    D --> E[Data Quality Framework<br/>Rules + Severity + Validation]
    E --> F{Valid?}
    F -- Yes --> G[Silver Layer<br/>Cleaned & Transformed Data]
    F -- No --> H[Quarantine Layer<br/>Rejected / Failed Records]

    G --> I[Gold Layer<br/>Canonical Business Model]
    I --> J[SCD Type 2 / History Tracking]
    J --> K[Reltio-style JSON Payloads / Downstream Output]

    K --> L[Audit & Run Metadata]
    L --> M[Observability Metrics]
    M --> N[Alerting + SLA Monitoring]
    N --> O[Retry / Recovery / Replay]
    O --> P[CI/CD + Release Verification]
    P --> Q[Docker + Databricks / ADF-style Deployment]
    Q --> R[Power BI-ready Dashboard Outputs]

---

### What this project demonstrates

<table>
  <tr>
    <td><b>Ingestion</b></td>
    <td>API ingestion, database ingestion, file ingestion patterns, raw landing, live public API integration planning</td>
  </tr>
  <tr>
    <td><b>Data Quality</b></td>
    <td>Schema contracts, metadata-driven DQ rules, severity handling, clean/quarantine split</td>
  </tr>
  <tr>
    <td><b>Lakehouse Processing</b></td>
    <td>Bronze, Silver, Gold, Quarantine, Delta-style merge/upsert, SCD Type 2 history tracking</td>
  </tr>
  <tr>
    <td><b>Reliability</b></td>
    <td>Pipeline audit, orchestration, runtime parameters, alerting, SLA monitoring, retry/recovery, failure replay</td>
  </tr>
  <tr>
    <td><b>Deployment Readiness</b></td>
    <td>Docker runtime, GitHub CI/CD quality gates, release verification, Databricks and ADF-style structure</td>
  </tr>
  <tr>
    <td><b>Observability</b></td>
    <td>Pipeline metrics mart, Power BI-ready dashboard outputs, alerting and SLA signals</td>
  </tr>
</table>

---

## Real work alignment

<table>
  <tr>
    <td><b>Apexon / IQVIA-style work</b></td>
    <td><b>How I connect it in my portfolio</b></td>
  </tr>
  <tr>
    <td>API, file, connector, and system source ingestion</td>
    <td>Config-driven API/database ingestion and raw landing</td>
  </tr>
  <tr>
    <td>Landing to staging and business-rule transformations</td>
    <td>Bronze/Silver transformations with schema and DQ checks</td>
  </tr>
  <tr>
    <td>DQ failures, quarantine, and clean data separation</td>
    <td>Severity-based DQ framework and quarantine output path</td>
  </tr>
  <tr>
    <td>Canonical modeling and downstream MDM integration</td>
    <td>Gold canonical layer and Reltio-style JSON payload generation</td>
  </tr>
  <tr>
    <td>Incremental processing, audit tracking, and error triage</td>
    <td>Watermarks, audit logs, retry/recovery, failure replay, SLA monitoring</td>
  </tr>
</table>

---

## Tech stack I am actively building with

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Delta_Lake-0A66C2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Reltio_MDM-5B5FC7?style=for-the-badge" />
  <img src="https://img.shields.io/badge/GitHub_CI_CD-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
</p>

<table>
  <tr>
    <td><b>Data Engineering</b></td>
    <td>ETL/ELT, incremental loads, watermarks, SCD Type 2, DQ frameworks, quarantine, observability</td>
  </tr>
  <tr>
    <td><b>Lakehouse</b></td>
    <td>PySpark, Databricks, Delta Lake, Medallion Architecture, canonical modeling</td>
  </tr>
  <tr>
    <td><b>Production Practices</b></td>
    <td>Git/GitHub discipline, CI/CD gates, Docker, release verification, structured documentation</td>
  </tr>
</table>

---

## Current engineering focus

```text
Build stronger production-ready Data Engineering skills
        ↓
Master PySpark, SQL, Databricks, Azure, and CI/CD through implementation
        ↓
Keep improving the portfolio with live API integration, observability, and deployment maturity
        ↓
Explain every project like a real client pipeline: source, rules, failures, recovery, and business output
```
---

## Versioned Project Evolution

```mermaid
flowchart TB

    subgraph Foundation
        V1[v1.0.0<br/>Python Config-Driven DQ Pipeline]
        V2[v2.0.0<br/>PySpark Bronze/Silver/Gold]
        V3[v3.0.0<br/>Databricks-style Structure]
        V4[v4.0.0<br/>Centralized Configuration]
        V5[v5.0.0<br/>Pipeline Audit Tracking]
    end

    subgraph Quality_and_Reliability
        V6[v6.0.0<br/>Severity-based DQ Control]
        V7[v7.0.0<br/>Custom Exceptions]
        V8[v8.0.0<br/>Schema Validation]
        V9[v9.0.0<br/>Incremental Load + Watermark]
        V10[v10.0.0<br/>Lakehouse Storage Upgrade]
        V11[v11.0.0<br/>Merge / Upsert Framework]
        V12[v12.0.0<br/>SCD Type 2 History]
        V13[v13.0.0<br/>Observability Metrics Mart]
        V14[v14.0.0<br/>Orchestration + Job Control]
        V15[v15.0.0<br/>Scheduling + Dependencies]
        V16[v16.0.0<br/>Alerting + SLA Monitoring]
        V17[v17.0.0<br/>Retry + Recovery + Replay]
    end

    subgraph Production_Readiness
        V18[v18.0.0<br/>CI/CD Hardening]
        V19[v19.0.0<br/>Docker Runtime]
        V20[v20.0.0<br/>API Ingestion Framework]
        V21[v21.0.0<br/>Database Ingestion Framework]
        V22[v22.0.0<br/>Advanced DQ Rule Catalog]
        V23[v23.0.0<br/>Databricks Asset Bundle-style Structure]
        V24[v24.0.0<br/>ADF Orchestration Simulation]
        V25[v25.0.0<br/>Power BI-ready Observability Dashboard]
        V26[v26.0.0 Planned<br/>Live Public API Integration Testing]
    end

    V1 --> V2 --> V3 --> V4 --> V5 --> V6 --> V7 --> V8 --> V9 --> V10 --> V11 --> V12 --> V13 --> V14 --> V15 --> V16 --> V17 --> V18 --> V19 --> V20 --> V21 --> V22 --> V23 --> V24 --> V25 --> V26

---


---

## Why the versioning matters

```markdown
## Why the versioning matters

This portfolio is not a one-time demo project.  
It is a **versioned Data Engineering system** that has been evolved step by step to reflect how real production pipelines mature over time:

- First, the **core pipeline and medallion flow**
- Then, **data quality, schema validation, incremental logic, and history tracking**
- Then, **observability, orchestration, alerting, retry, and recovery**
- Then, **CI/CD, Docker, ingestion frameworks, deployment patterns, and dashboards**
- Next, **live public API integration testing** for stronger real-world integration practice

---

## GitHub activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Rohith-S-98&show_icons=true&theme=tokyonight&hide_border=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rohith-S-98&layout=compact&theme=tokyonight&hide_border=true" height="165" />
</p>

---

<h3 align="center">Building my Data Engineering career in public — one production habit, one version, and one verified release at a time.</h3>
