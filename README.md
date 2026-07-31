# Rodrigo Monteiro Pereira

[![Email](https://img.shields.io/badge/-rmonteiropereira1@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:rmonteiropereira1@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rodrigo-monteiro-pereira)

**Data & ML Engineering — lakehouses, ML systems, and the evaluation that keeps them honest.**

I build data platforms end to end: ingestion and orchestration, medallion storage on
Delta/DuckDB, and the modelling, drift monitoring and evaluation harnesses that sit on
top. I care about the parts most portfolios skip — idempotence, lineage, leakage tests,
and being explicit about which numbers are real.

<!-- NEEDS: current role, employer and start date — not stated anywhere I could verify. -->
<!-- NEEDS: years of experience, degree/education, and a CV link, if you want them here. -->

---

## Selected work

| Project | What it demonstrates | Stack |
|---|---|---|
| **[Open-Finance-LakeHouse](https://github.com/rmonteiro-pereira/Open-Finance-LakeHouse)** | Brazilian open-finance lakehouse: **51 active series across 10 source handlers**, medallion bronze → silver → gold, asset-driven Airflow 3 DAGs where each series is independently attributable, and 8 gold marts. A Spark Structured Streaming lane (event-time windows, `Trigger.AvailableNow` idempotence, near-real-time DuckDB mart) is in review. | Spark · Delta Lake · DuckDB · Airflow 3 · Polars · Kubernetes |
| **[Scraper-Lib](https://github.com/rmonteiro-pereira/Scraper-Lib)** | A properly packaged Python library, not a script dump: `src/` layout, tests, versioned releases and a published documentation site. Ray-parallel downloads with retry/backoff, incremental mode and atomic state tracking. | Python · Ray · pytest · MkDocs |
| **[neuro_tech](https://github.com/rmonteiro-pereira/neuro_tech)** | IPTU (property-tax) pipeline built as a technical challenge: medallion architecture on Delta Lake with a PySpark path, automated data-quality validation via PyDeequ, and a containerised Spark runtime. | PySpark · Delta Lake · PyDeequ · Docker |
| **[ai-cli-bridge](https://github.com/rmonteiro-pereira/ai-cli-bridge)** | A small, focused tool that syncs MCP servers, skills, memory and session handoff between two agent CLIs — solving a real daily friction rather than a toy problem. | PowerShell · MCP |

<!-- NEEDS: two more projects are being prepared for publication and are deliberately not
     linked here yet, because linking a private repo shows a 404 to visitors:
       - rag-eval               (retrieval evaluation harness: recall@k, MRR, nDCG)
       - energy-forecast-drift  (forecasting + drift detection: PSI/KS, MLflow registry)
     Add rows for them once they are public. -->

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

## Contact

- **Email** — [rmonteiropereira1@gmail.com](mailto:rmonteiropereira1@gmail.com)
- **LinkedIn** — [rodrigo-monteiro-pereira](https://www.linkedin.com/in/rodrigo-monteiro-pereira)
