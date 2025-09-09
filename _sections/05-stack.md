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

### Operational tooling & content
* PowerPoint executive storytelling; KPI narrative design
* Documentation in Markdown; reproducible environments and runbooks
* Training decks, including generation of corporate training videos with TTS-based narration

### Core languages
* Python 3.7–3.13
* SQL (T-SQL, PostgreSQL, Oracle)
* C#
* JavaScript
* Bash / Shell
* Java (foundational)

### Cloud platforms (primary → secondary)
* **Azure:** Power BI Service and Power Platform for M365; EntraID, App Service, Azure SQL, Azure OpenAI, Functions; Microsoft Fabric (Lakehouse, Dataflows, etc.)
* **GCP:** BigQuery, Google Cloud Storage, Compute Engine and Cloud Run, Vertex AI, Pub/Sub, Healthcare API (FHIR)
* **IBM Cloud**: OpenShift
* **AWS:** Limited exposure

### Data engineering & storage
* Lakehouse/warehouse design; partitioning, clustering, cost/perf tuning
* Files/streams/APIs ingestion; contract-driven schemas; schema checks
* Parquet/CSV on object storage; BigQuery datasets & streaming inserts
* SQL Server; Azure SQL; PostgreSQL; MySQL; SQLite; DuckDB

### Analytics, Visualization & BI
* Power BI (modeling, DAX, Power Query, RLS, printable exports, federation and auditable sharing)
* KQL in Azure Event Hub and Fabric Real-Time Analytics
* Jupyter (local, Codespaces, other computes)
* Excel (as a power analytics tool for teams and integrated in Microsoft Power Platform)

### Real-time & streaming
* Pub/Sub → Cloud Run → BigQuery streaming
* Power BI real-time pipelines and reports (push/streaming datasets)
* Backpressure, sampling, idempotency; SLA-aware telemetry,
* KQL / notebooks for diagnostics and analytics workloads

### ML / AI
* TensorFlow; Keras
* Batch & real-time ML pipelines; feature extraction
* OpenAI API function calling; embeddings; RAG
* Whisper STT; diarization/turn-taking; basic audio features
* Vector search: ChromaDB, Cassandra / DataStax Astra DB
* Deterministic pattern extraction: fuzzy matching; regex-based extraction
* Local LLM / micro and tiny OSS LLM runs (Llama-class on M2 Ultra / GCP VM, etc.)

### Agentic AI & orchestration
* LangGraph (stateful graphs; multi-agent, multi-tool orchestration including controls and recursion)
* LangChain (RAG, tool use, as basis for more complex agentic systems)
* Langflow (DataStax) for visual pipelines as a local tool for understanding flows and presentations
* Fundamentals of MCP servers (Model Context Protocol)

### Healthcare interoperability (kept minimal, no terminology lists)
* Meditech and Intrahealth Profile workflows
* FHIR R4 standards and events handling
* Google Cloud Healthcare API ("FHIR Store")
* Tuning up and synthecizing EMR data with Synthea (localization & module editing; FHIR streaming and bundle export/ingest)

### Backend & APIs
* FastAPI; Flask; others
* ASP.NET Core Minimal APIs; EF Core
* JWT + ASP.NET Identity; role-based auth
* REST / WebSocket endpoints; Postman collections
* Node.js on Azure App Service
* Redis for request and result caching, sessions, and rate limiting

### Frontend & visualization
* Power BI models, reports, apps, and dashboards with advanced analytical features (ML, flows, effect analysis)
* React 
* Blazor WebAssembly 
* Notebook visuals; ipyleaflet maps; Kepler-style outputs 

### DevOps / CI/CD & platform engineering
* GitHub Actions (build, test, secure, deploy)
* GitHub Codespaces; DevContainers on Azure and GCP
* Docker; Kubernetes (minikube/k3d); Helm; OpenShift (with Tekton)
* Bash automation; gcloud CLI; jq; curl
* Terraform
* Observability: structured logs, metrics (Prometheus + Grafana), traces
* Release hardening; rollback playbooks; runbooks
* Rollback and canary policies validated under high-memory and hot-key scenarios

### Testing & QA
* Unit/integration tests for APIs & clients (pytest, xUnit, others) with high coverage
* Smoke tests / bash route tests for event pipelines
* Data quality checks: schema, domain constraints; timestamped debug logs

### Privacy, security & governance
* Azure Entra ID; JWT; RBAC; secrets management; implementing least-privilege
* Dynamic Data Masking or compelte hashing for sensitive data; Row-Level Security
* k-anonymity / l-diversity / t-closeness checks; differential-privacy concepts
* Audit trails; data residency constraints for PII including PHI

### Cybersecurity & red-teaming
* Threat modeling; secure defaults; logging & monitoring
* Ethical hacking fundamentals; Kali Linux; Metasploit (fundamentals); deep packet analysis with Wireshark; monitoring with OpenVAS
* SAST/DAST basics; OWASP awareness, audits and testing; container image hardening

### Geospatial & routing
* Azure and GCP routing APIs; OSRM routing; distance/isochrone pipelines
* Deploying Open Street Map instances; ipyleaflet map visualizations; heatmaps in Power BI and other tools

### Media / audio ("waveform" data)
* Fully synthecized video creation from prompts (such as producing world-class, LMNotebook-style videos for corporate training)
* Whisper STT pipelines; Audacity workflows; basic audio feature extraction
