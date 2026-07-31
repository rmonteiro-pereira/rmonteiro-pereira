# Rodrigo Monteiro Pereira

[![Email](https://img.shields.io/badge/-rmonteiropereira1@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:rmonteiropereira1@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rodrigo-monteiro-pereira/)
![Rio de Janeiro](https://img.shields.io/badge/-Rio_de_Janeiro,_BR-4A4A4A?style=flat&logo=googlemaps&logoColor=white)

**Data Platform & AI Lead Engineer** — data and AI platforms end to end, from architecture
and data engineering through analytics, ML and AI agents.

I lead a Data & AI function across on-prem and cloud, with a strong focus on governance,
data quality and regulatory compliance. Financial markets and telecoms. I care about the
parts most portfolios skip — idempotence, lineage, leakage tests, and being explicit about
which numbers are real.

---

## Now — Data Platform & AI Lead Engineer at Telecall

*Feb 2026 – present · reporting to the IT Director*

Own the Data & AI function end to end, from architecture through execution.

- Lead an analytics estate of **70+ pipelines, 60 datasets and 90 dashboards over terabytes**,
  and its migration to a **Databricks** cloud architecture compliant with **three regulatory
  jurisdictions (ANATEL, FCC, ANACOM)** — **100% GitOps** provisioning, regulatory controls
  as **policy-as-code**.
- Restructured data governance and sensitive-data handling: classification, protection,
  regulatory and **LGPD** compliance.
- Built **AI agents** for technical specification, **AIOps** in the customer-service SOC, and
  automated report generation.
- Built **near-real-time monitoring pipelines** for operations; optimised the product
  catalogue with **UMAP** dimensionality reduction and **HDBSCAN** clustering.
- Modernised the Power BI estate and shipped web dashboards.

| Company | Role | Period |
|---|---|---|
| **Telecall** | Data Platform & AI Lead Engineer | Feb 2026 – present |
| Consultoria Individual | Data & AI Consultant | Aug 2023 – Feb 2026 |
| Faros Investimentos | Data Team Leader · Data Engineer | Aug 2021 – Aug 2023 |

---

## Selected work

| Project | What it demonstrates | Stack |
|---|---|---|
| **[Open-Finance-LakeHouse](https://github.com/rmonteiro-pereira/Open-Finance-LakeHouse)** | Brazilian open-finance lakehouse on real public BACEN/IBGE/IPEA/B3 data: **51 active series across 10 source handlers**, medallion bronze → silver → gold, asset-driven Airflow 3 DAGs where each series is independently attributable, 8 gold marts, plus shipped Spark Structured Streaming and dbt lanes. | Spark · Delta Lake · DuckDB · Airflow 3 · Polars · Kubernetes |
| **[rag-eval](https://github.com/rmonteiro-pereira/rag-eval)** | RAG over real Banco Central Copom minutes, built as an **evaluation** problem rather than a demo: a diagnosed retrieval defect, a controlled ablation whose arms differ by one component at a time, and prompt-injection and PII guardrails measured against an ungoverned control arm. Gold-set status is enforced in code — `--min-status validated` returns nothing until a human validates. | Python · Qdrant · sentence-transformers · Presidio · FastAPI |
| **[energy-forecast-drift](https://github.com/rmonteiro-pereira/energy-forecast-drift)** | The MLOps axis: temporal-leakage control, walk-forward backtesting, four drift detectors (PSI/KS, target, prediction, performance) with a retrain-trigger verdict, and gated promotion through an MLflow registry. Demand data is a synthetic fixture pending an API key, and every artifact carries `"is_real": false` to say so. | Python · LightGBM · MLflow · FastAPI · React |
| **[Scraper-Lib](https://github.com/rmonteiro-pereira/Scraper-Lib)** | A properly packaged Python library, not a script dump: `src/` layout, tests, semantic versioning with an automated release pipeline, and a published documentation site. Ray-parallel downloads with retry/backoff, incremental mode and atomic state tracking. | Python · Ray · pytest · MkDocs |
| **[neuro_tech](https://github.com/rmonteiro-pereira/neuro_tech)** | IPTU (property-tax) pipeline built as a technical challenge: medallion architecture on Delta Lake with a PySpark path, automated data-quality validation via PyDeequ, and a containerised Spark runtime. | PySpark · Delta Lake · PyDeequ · Docker |
| **[ai-cli-bridge](https://github.com/rmonteiro-pereira/ai-cli-bridge)** | A small, focused tool that syncs MCP servers, skills, memory and session handoff between two agent CLIs — solving a real daily friction rather than a toy problem. | PowerShell · MCP |

---

## Technologies

**Data & orchestration** —
![Apache Spark](https://img.shields.io/badge/-Apache_Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/-Delta_Lake-20BDFF?style=flat&logo=delta&logoColor=white)
![DuckDB](https://img.shields.io/badge/-DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![Airflow](https://img.shields.io/badge/-Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/-dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Databricks](https://img.shields.io/badge/-Databricks-FF3621?style=flat&logo=databricks&logoColor=white)

**ML & evaluation** —
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/-LightGBM-9ACD32?style=flat)
![MLflow](https://img.shields.io/badge/-MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas&logoColor=white)

**Platform** —
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-623CE4?style=flat&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/-Azure-0089D6?style=flat&logo=microsoftazure&logoColor=white)

---

## Education

| Institution | Degree | Period |
|---|---|---|
| **PUC-Rio** | Mestrado em Ciências de Dados e Inteligência Artificial *(MSc, Data Science & AI — in progress)* | Aug 2025 – present |
| **PUC-Rio** | Bacharelado em Ciência da Computação *(BSc, Computer Science)* | Jan 2016 – Aug 2021 |

---

## Contact

- **Email** — [rmonteiropereira1@gmail.com](mailto:rmonteiropereira1@gmail.com)
- **LinkedIn** — [rodrigo-monteiro-pereira](https://www.linkedin.com/in/rodrigo-monteiro-pereira/)
- **Location** — Rio de Janeiro – RJ, Brazil
