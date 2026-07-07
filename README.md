<div align="center">

<img width="1700" height="460" alt="github-header-banner" src="https://github.com/user-attachments/assets/6b652d3a-ce12-4c6b-8830-62c5d72a9b92" />

<br/>

```
Data Engineer · Applied AI · Open Source Contributor
```
[![Profile Views](https://komarev.com/ghpvc/?username=abhishek09827&label=Profile%20Views&color=4C8BF5&style=flat)](https://github.com/abhishek09827)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-abhishek--kaushik-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/abhishek-kaushik-0a6a16243/)
[![Blog](https://img.shields.io/badge/Blog-ab--blog.hashnode.dev-2962FF?style=flat&logo=hashnode)](https://ab-blog.hashnode.dev/)

</div>

---

## About

Data Engineer at **Hewlett Packard Enterprise** building large-scale streaming and batch ingestion systems with Apache Kafka, PySpark, and Airflow across cloud and on-prem environments.

I work at the intersection of **data platform engineering**, **applied AI**, and **developer tooling** - with a focus on systems that are measurable, observable, and honest about their limitations.

- 🔧 Published [`SageScan`](https://pypi.org/project/sagescan-data/) to PyPI - a CLI data-quality validator (Go + Python) with 17 validator types and chunked processing for multi-GB datasets
- 🤝 Merged PRs in **dbt-core** ([#12390](https://github.com/dbt-labs/dbt-core/pull/12390), [#12358](https://github.com/dbt-labs/dbt-core/pull/12358)) and **LlamaIndex** ([#20661](https://github.com/run-llama/llama_index/pull/20661), [#20787](https://github.com/run-llama/llama_index/pull/20787))
- 📐 Interested in: schema evolution, retrieval evaluation, NL-to-SQL systems, and AIOps

---

## Experience

**Cloud Developer I - Hewlett Packard Enterprise** *(Aug 2025 – Present)*
- Streaming and batch ETL at scale using Apache Kafka and Airflow across cloud and on-prem
- Schema evolution and serialization with Avro and Protobuf across distributed ingestion systems
- PySpark transformation jobs containerized with Docker, deployed on Kubernetes + MinIO
- PII masking and ingestion-boundary governance controls
- Automated deployments via ArgoCD, CronWorkflows, and GitHub Actions

**SDE Intern - Hewlett Packard Enterprise** *(Feb 2025 – Aug 2025)*
- Ingestion pipelines with AWS Glue and Lambda; data-quality validation frameworks in SQL and PySpark
- ML telemetry prototypes with SageMaker; structured logging and ETL observability improvements

---

## Open Source

| Project | Contribution | PR |
|---|---|---|
| **dbt-core** | Seed-column validation for mismatched type configs | [#12390](https://github.com/dbt-labs/dbt-core/pull/12390) |
| **dbt-core** | Parser test coverage for Python model verification | [#12358](https://github.com/dbt-labs/dbt-core/pull/12358) |
| **LlamaIndex** | Prompt-template maintainability improvements | [#20661](https://github.com/run-llama/llama_index/pull/20661) |
| **LlamaIndex** | Multilingual-aware semantic chunking for mixed-language retrieval | [#20787](https://github.com/run-llama/llama_index/pull/20787) |

---

## Projects

### [SageScan](https://github.com/abhishek09827/sagescan) - CLI Data Quality Validator
`Go` `Python` `Cobra` `Pandas` `Pydantic v2` `PyPI`

- 17 validator types: schema, statistical, and drift validation
- Chunked processing for multi-GB CSVs at 125K+ rows/sec (Intel i5 / 16GB RAM, 1M-row benchmark), 599MB peak memory
- KS-test + PSI drift detection for statistical distribution shifts
- Optional LLM-assisted YAML rule generation - raw data never leaves the machine

---

### [QueryMind-DW](https://github.com/abhishek09827/querymind-dw) - NL-to-SQL Data Warehouse
`Python` `LangChain` `FastAPI` `Kafka` `dbt` `DuckDB` `PostgreSQL` `Redis` `MinIO`

- End-to-end warehouse: Kafka ingestion → MinIO data lake → dbt transforms (SCD Type 2) → DuckDB/PostgreSQL → Streamlit dashboards
- DuckDB for analytical execution (vectorized engine, low operational overhead); PostgreSQL for transactional serving and metadata
- 67% NL-to-SQL accuracy on aggregations, joins, subqueries, and window functions via schema-aware prompt injection
- Redis caching layer: 14.9s → 1ms on cache hits; SQL safety validator blocking destructive statements pre-execution

---

### [OI-Engine](https://github.com/abhishek09827/oi-engine) - Agentic AIOps Platform
`Python` `FastAPI` `CrewAI` `Kafka` `Redis` `PostgreSQL` `pgvector` `Docker`

- Multi-agent orchestration (CrewAI) for anomaly detection, incident summarization, remediation planning, and root-cause retrieval
- Two-stage filtering: Z-score pre-filter (tuned on labeled log-event datasets) → LLM inference; 98% candidate reduction at 14.5K+ events/sec ingestion
- pgvector semantic retrieval for historical incident similarity; Redis-backed agent memory; Prometheus observability

---

## Tech Stack

**Data Engineering**
`Apache Kafka` `Apache Airflow` `PySpark` `dbt` `AWS Glue` `MinIO` `Avro` `Protobuf` `Schema Evolution` `Stream Processing`

**AI / LLM Systems**
`RAG Pipelines` `LangChain` `LlamaIndex` `pgvector` `CrewAI` `Multi-Agent Systems` `Evaluation Pipelines`

**Languages**
`Python` `Go` `SQL` `JavaScript` `Shell Scripting`

**Cloud & DevOps**
`AWS (Glue · SageMaker · Lambda · S3)` `Docker` `Kubernetes` `ArgoCD` `GitHub Actions`

**Backend & Databases**
`FastAPI` `GraphQL` `REST APIs` `PostgreSQL` `DuckDB` `Redis`

**Observability**
`Prometheus` `Grafana` `KPow` `Structured Logging`

---

## GitHub

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=abhishek09827&theme=github_dark" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=abhishek09827&theme=github_dark" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=abhishek09827&theme=github_dark" />

</div>

---

## DSA

<div align="center">
<img src="https://leetcard.jacoblin.cool/abhishekk09827?theme=dark&font=Karma&ext=heatmap" />
</div>

---

## Contact

📩 abhishekk09827@gmail.com  
💼 [linkedin.com/in/abhishek-kaushik-0a6a16243](https://www.linkedin.com/in/abhishek-kaushik-0a6a16243/)  
🌐 [github.com/abhishek09827](https://github.com/abhishek09827)  
✍️ [ab-blog.hashnode.dev](https://ab-blog.hashnode.dev/)

Open to remote opportunities in **Data Engineering** and **Applied AI**.
