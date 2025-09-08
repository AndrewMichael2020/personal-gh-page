---
title: Stack
section_id: stack
order: 5
---

### Managerial / product stack
* Requirements capture → KPI definition → semantic modeling
* Road-mapping for data/ML projects; iteration plans
* Privacy/compliance scoping; cost-conscious cloud architecture & run-rate control
* Negotiation frameworks (Harvard PON)
* Community engagement and technical demos

### Core languages
* Python 3.7–3.11
* SQL (T-SQL)
* C#
* Java
* JavaScript
* Bash / Shell

### Cloud platforms (primary → secondary)
* **Azure:** Microsoft Fabric (Lakehouse, Dataflows), App Service, Azure SQL, Entra ID, Azure OpenAI (experience/planning), Functions (evaluating), Data Factory
* **GCP:** Cloud Run, Pub/Sub, BigQuery, Google Cloud Storage, Compute Engine (DL VM), Healthcare API (FHIR), Vertex AI (evaluating)
* **IBM Cloud / OpenShift** (coursework), **AWS** (limited exposure)
* **AWS:** Limited exposure

### Data engineering & storage
* Lakehouse/warehouse design; partitioning, clustering, cost/perf tuning
* Files/streams/APIs ingestion; contract-driven schemas; schema checks
* Parquet/CSV on object storage; BigQuery datasets & streaming inserts
* SQL Server; Azure SQL; PostgreSQL (planned); MySQL; SQLite; DuckDB

### Analytics, Visualization & BI
* Power BI (modeling, DAX, Power Query, RLS, printable exports)
* KQL / Azure Data Explorer (Fabric Real-Time Analytics)
* Jupyter (local, Codespaces); Excel (advanced)

### Real-time & streaming
* Pub/Sub → Cloud Run → BigQuery streaming
* Power BI real-time tiles (push/streaming datasets)
* Backpressure, sampling, idempotency; SLA-aware telemetry
* KQL / notebooks for diagnostics

### ML / AI
* TensorFlow; Keras
* Batch & real-time ML pipelines; feature extraction
* OpenAI API (function calling); embeddings; RAG
* Whisper STT; diarization/turn-taking; basic audio features
* Vector search: ChromaDB
* Pattern extraction: fuzzy matching; regex-based extraction
* Local LLM experiments (Llama-class on M2 Ultra / GCP VM)

### Agentic AI & orchestration
* LangGraph (stateful graphs, multi-tool orchestration)
* LangChain (RAG, tool use)
* Langflow (DataStax) for visual pipelines
* MCP servers (Model Context Protocol)

### Healthcare interoperability (kept minimal, no terminology lists)
* Meditech and Intrahealth Profile workflows
* FHIR R4
* Google Cloud Healthcare API (FHIR Store)
* Synthea synthetic EMR (localization & module editing; FHIR bundle export/ingest)

### Backend & APIs
* FastAPI; Flask
* ASP.NET Core (.NET 8) Minimal APIs; EF Core
* JWT + ASP.NET Identity; role-based auth
* REST / WebSocket endpoints; Postman collections
* Node.js on Azure App Service (with Entra ID)

### Frontend & visualization
* Power BI dashboards (executive/shift; drill-throughs)
* React (course/projects)
* Blazor WebAssembly (selected projects)
* Notebook visuals; ipyleaflet maps; Kepler-style outputs (non-pydeck)

### DevOps / CI/CD & platform engineering
* GitHub Actions (build, test, coverage/Cobertura, deploy)
* GitHub Codespaces; DevContainers
* Docker; Kubernetes (minikube/k3d); Helm; OpenShift (labs/Tekton)
* Bash automation; gcloud CLI; jq; curl
* Terraform (targeted, in progress)
* Observability: structured logs, metrics (Prometheus/Grafana), traces
* Release hardening; rollback playbooks; runbooks; SLAs/SLOs

### Privacy, security & governance
* Entra ID (Azure AD); JWT; RBAC; secrets management; least-privilege
* Dynamic Data Masking; Row-Level Security; tokenization/pseudonymization
* k-anonymity / l-diversity / t-closeness checks; differential-privacy concepts
* Audit trails; data residency constraints (PHI/PII)

### Cybersecurity & red-teaming (foundational)
* Threat modeling; secure defaults; logging & monitoring
* Ethical hacking fundamentals; Kali Linux; Metasploit (intro); Wireshark; OpenVAS
* SAST/DAST basics; OWASP awareness; container image hardening

### Geospatial & routing
* OSRM routing on GCP VM; distance/isochrone pipelines
* ipyleaflet maps; HTML heatmaps (pydeck-free)

### Media / audio ("waveform" data)
* Whisper STT pipelines; Audacity workflows; basic audio feature extraction

### Testing & QA
* Unit/integration tests for APIs & clients (pytest, xUnit)
* Smoke tests / bash route tests for event pipelines
* Data quality checks: schema, domain constraints; timestamped debug logs

### Operational tooling & content
* PowerPoint executive storytelling; KPI narrative design
* Short training decks; video education with Whisper-based narration
* Documentation in Markdown; reproducible environments and runbooks
