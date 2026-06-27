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

This project is designed like a real Data Engineering platform: source data enters through API, file, or database-style inputs, passes through validation and quality gates, moves across lakehouse layers, generates downstream MDM-style outputs, and is protected with audit, observability, retry, CI/CD, and deployment controls.

```mermaid
flowchart LR
    A[Source Systems<br/>API / File / Database] --> B[Raw Landing<br/>JSON / CSV / Tables]
    B --> C[Schema Contracts<br/>Required Fields + Types]
    C --> D[Bronze Layer<br/>Standardization]
    D --> E[Data Quality<br/>Rules + Severity]
    E --> F{Valid?}
    F -- Yes --> G[Silver Layer<br/>Clean Data]
    F -- No --> H[Quarantine Layer<br/>Rejected Records]
    G --> I[Gold Layer<br/>Canonical Model]
    I --> J[SCD Type 2<br/>History Tracking]
    J --> K[Reltio-style<br/>JSON Payloads]
    K --> L[Audit + Run Metadata]
    L --> M[Observability Metrics]
    M --> N[Alerts + SLA Monitoring]
    N --> O[Retry / Recovery / Replay]
    O --> P[CI/CD + Release Gates]
    P --> Q[Docker + Databricks / ADF-style Deployment]
    Q --> R[Power BI-ready Outputs]
```

### What this end-to-end system proves

- I can design pipelines beyond simple ETL scripts.
- I understand source ingestion, validation, transformation, quarantine, canonical modeling, and downstream integration.
- I can implement production-style controls like audit, observability, alerting, retry, release verification, and CI/CD gates.
- I can explain the complete flow from source → raw → bronze → silver → gold → MDM-style output.

---

## Versioned Project Evolution

This portfolio has been built version by version to show how a real pipeline matures from a basic data flow into a production-ready engineering system.

```mermaid
flowchart LR
    A[v1-v5<br/>Foundation<br/>Python DQ, PySpark, Config, Audit] --> B[v6-v12<br/>Quality + Lakehouse<br/>DQ Severity, Schema, Watermark, Merge, SCD2]
    B --> C[v13-v17<br/>Operations<br/>Observability, Orchestration, Scheduling, Alerts, Retry]
    C --> D[v18-v22<br/>Production + Ingestion<br/>CI/CD, Docker, API, Database, Advanced DQ]
    D --> E[v23-v26<br/>Deployment + Analytics<br/>Databricks, ADF, Power BI, Live API Testing]
```

<table>
  <tr>
    <td><b>Version Range</b></td>
    <td><b>Engineering Maturity Added</b></td>
    <td><b>What it proves</b></td>
  </tr>
  <tr>
    <td><b>v1 - v5</b></td>
    <td>Config-driven Python pipeline, PySpark medallion flow, Databricks-style structure, centralized config, audit tracking</td>
    <td>Strong foundation and clean project structure</td>
  </tr>
  <tr>
    <td><b>v6 - v12</b></td>
    <td>Severity-based DQ, custom exceptions, schema validation, incremental load, watermarking, merge/upsert, SCD Type 2</td>
    <td>Data quality, reliability, and lakehouse processing depth</td>
  </tr>
  <tr>
    <td><b>v13 - v17</b></td>
    <td>Observability mart, orchestration, job control, scheduling, dependency checks, alerting, SLA monitoring, retry and replay</td>
    <td>Operational thinking beyond basic transformation code</td>
  </tr>
  <tr>
    <td><b>v18 - v22</b></td>
    <td>CI/CD hardening, Docker runtime, API ingestion, database ingestion, advanced DQ rule catalog</td>
    <td>Production-readiness, testability, and ingestion framework design</td>
  </tr>
  <tr>
    <td><b>v23 - v26</b></td>
    <td>Databricks Asset Bundle-style structure, Azure Data Factory simulation, Power BI observability, planned live public API integration</td>
    <td>Cloud deployment style, analytics visibility, and real-world integration practice</td>
  </tr>
</table>

### Why the versioning matters

This is not a one-time demo project. It is a versioned Data Engineering system that has been evolved step by step to reflect how real production pipelines mature:

- First, the core pipeline and medallion flow
- Then, data quality, schema validation, incremental logic, and history tracking
- Then, observability, orchestration, alerting, retry, and recovery
- Then, CI/CD, Docker, ingestion frameworks, deployment patterns, and dashboards
- Next, live public API integration testing for stronger real-world integration practice

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

## GitHub activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Rohith-S-98&show_icons=true&theme=tokyonight&hide_border=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rohith-S-98&layout=compact&theme=tokyonight&hide_border=true" height="165" />
</p>

---

<h3 align="center">Building my Data Engineering career in public — one production habit, one version, and one verified release at a time.</h3>
