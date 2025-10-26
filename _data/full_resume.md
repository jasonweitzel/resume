# Jason Weitzel — Superset Resume (Master)

> Master, non‑duplicative resume for cybersecurity/AppSec roles. Emphasizes scale, measurable impact, and reusable patterns. Tool/OS versions omitted unless material to the outcome.

---

## H‑E‑B — San Antonio, TX

### Principal Application Security Engineer  
**06/2023 – Present**
- Drove org‑wide adoption of **SAST/SCA/Secret** scanning from **<10% to 100%** in GitLab CI; cut false positives by **~85%** and overall noise by **~98%** with reachability analysis, automated validation, and **EPSS**‑weighted prioritization.
- Built incident‑ready data pipelines and dashboards unifying **GitLab**, scanners, and cloud telemetry; enabled **same‑day** triage and targeted guidance (e.g., traced malicious package installs across dev/CI/prod during the **Sep 8 NPM registry compromise**).
- Created **reusable security patterns** and **Terraform modules** (identity, secrets, network controls) to make secure‑by‑default the paved road; established OIDC‑based CI→cloud auth for direct GitLab deployments.
- Reduced **SAST/IaC** time‑to‑fix from **6+ months to ~1 week**; maintained and recommended **Renovate** for weekly CVE‑driven dependency updates on supported projects.
- Led org‑wide secret hygiene campaigns across **~14k repos**, shrinking static‑secret usage from **~750 to <100 repos**.
- Mentored ~2k developers via weekly **code jams**, office hours, and design consults (authn, secret mgmt, inter‑service comms).

### Lead Application Security Engineer  
**11/2021 – 06/2023**
- Standardized **SAST/DAST/SCA** pipelines across a portfolio growing from **~11k to ~15k repos** spanning hybrid/multi‑cloud (AWS, GCP, Azure, on‑prem/K8s).
- Engineered a security data lake (storage/ETL/query) integrating GitLab events, scanner output, and cloud artifacts; delivered **Grafana** dashboards that guided team planning and exec prioritization.
- Implemented automation in **Python** and **Backstage** to accelerate remediation and unlock new CI guardrails.

---

## Booz Allen Hamilton — Rome, NY • Colorado Springs, CO

### Solutions Architect (DevSecOps)  
**10/2019 – 11/2021**
- Took a legacy **monorepo (~100 components)** from near‑zero automation to **standardized CI/CD (Jenkins)** that installs/tests the full system; embedded **CIS/DISA** checks and functional tests to catch misconfigurations pre‑release.
- **100% of code** flowed through CI/CD and code review; automated test coverage rose from manual‑only to **~60%**. Authored **Robot Framework** libraries to speed integration/E2E test development.
- Dockerized legacy apps for portable, consistent deployments; produced **Windows (EXE)** and **Linux (RPM)** installers for multi‑component rollouts. Supported by **~50 engineers**.

### Cyber Threat Analyst / Software Engineer  
**06/2015 – 10/2019**
- Led on‑site threat analysis evaluations for Air Force systems; combined manual techniques and custom scripts to verify contractor‑reported posture against **RMF** controls.
- Built and scaled a multi‑user **NW.js/Vue.js/PouchDB** assessment app that generated RMF artifacts (reports, charts, diagrams) and trained new assessors via an embedded help system.
  - Reduced assessment duration from **4–6 weeks to 1–2 weeks** (data collection, review, reporting); enabled concurrent analyst workflows with full traceability to evidence.
  - Adopted across **hundreds of assessments** and multiple contracts; became a formal differentiator in proposals. Served as a key technical resource for capture/proposal content.
- Improved developer delivery by creating repeatable IaC‑based environments (**Vagrant**) and migrating a Java codebase from **Ant to Gradle** to stabilize and speed builds.

---

## Lockheed Martin (IS&GS / ISC2) — Colorado Springs, CO

### Senior Information Assurance Engineer (Tech Lead)  
**09/2011 – 01/2015**
- Tech lead for a matrixed department scaling to **~30** specialists across **~20 missions / 10+ contracts** and **~6 sites**; managed staffing and agile tasking.
- Delivered custom hardening across OS, network, vendor/custom apps, databases, and virtualized environments; introduced a **GPO** management process enabling concurrent developer workflows under strict lockdowns.
- Built an automated **STIG** evidence tool, achieving an **~80%** efficiency gain in validation and reporting.
- Presented risk posture and plans to management and government stakeholders; oversaw **TCNO** applicability and enterprise vulnerability reporting.
- Operated during **DIACAP to RMF** transition; trained operations/security staff; deployed/ran IDS/AV/SIEM.

### Information Assurance Engineer  
**05/2008 – 09/2011**
- Managed recurring enclave evaluations across **~4 sites**; produced reports/POA&Ms and briefed government and internal leadership.
- Re‑engineered hotfix workflows to cut patch time by **50%+** and meet accreditation deadlines; partnered with developers to balance mission availability with control rigor.
- Enhanced the hardening framework with **configuration suites** (layered dev vs. prod baselines) to raise **DISA STIG** compliance without blocking mission software.
- Authored **SOPs** and training (DokuWiki + slide decks) to speed onboarding, reduce rework, and standardize evidence capture. Team objective each cycle: **close all High/Medium findings**.
- Operated under **DIACAP**.

### Information Assurance Engineer Associate  
**05/2007 – 05/2008**
- Built a PHP web app with MySQL (later MSSQL) to auto‑generate **POA&Ms**, template recurring findings/mitigations, and replace spreadsheet workflows—cutting writing time by **~75%** and reducing assessment effort to **~25%** of baseline.
- Re‑architected OS hardening from many bespoke scripts to a **definition‑driven lockdown engine** (**VBScript/Perl/shell**), eliminating duplication and accelerating baseline creation.
- Supported **~5 missions / 3 contracts** across **~4 sites** with a core team of **4**; operated during **DITSCAP to DIACAP** transition.

---

## Selected Technical Themes
- **Application Security / Secure SDLC:** SAST/DAST/SCA, reachability‑based triage, secret management, authn/authorization design, paved‑road patterns, Terraform modules.
- **DevSecOps / Platform:** GitLab/Jenkins CI, OIDC workload identity, artifact security, policy‑as‑code guardrails, containerization, installers for multi‑component systems.
- **Automation & Data:** Python automation, data lakes/ETL for security telemetry, Grafana dashboards, incident‑driven analytics.
- **Compliance & Assessment:** DISA STIGs, POA&M, DIACAP/RMF, TCNO, assessment tooling, SOPs and enablement.

---
