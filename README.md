# 🎯 Azure AI-200 Journey — Azure AI Cloud Developer Associate

My preparation repo for the **AI-200: Developing AI Cloud Solutions on Azure** exam.

- **Started:** July 2026
- **Target exam date:** _(set after ~6 weeks of study)_
- **Passing score:** 700/1000 · 120 minutes · Proctored (Pearson Vue)
- **Official cert page:** https://learn.microsoft.com/credentials/certifications/azure-ai-cloud-developer-associate/
- **Official study guide:** https://aka.ms/AI200-StudyGuide
- **Exam sandbox (try the UI):** https://aka.ms/examdemo

---

## 📁 Repo structure

```
01-containers/        Domain 1: Containerized solutions (ACR, App Service, Container Apps, AKS)
02-data-services/     Domain 2: Cosmos DB, PostgreSQL + pgvector, Managed Redis
03-integration/       Domain 3: Service Bus, Event Grid, Azure Functions
04-secure-monitor/    Domain 4: Key Vault, App Configuration, OpenTelemetry, KQL
docker-basics/        Week 0: local Docker practice before touching Azure
notes/                Cheat sheets, decision matrices, gotchas
```

---

## ✅ Official Skills Checklist (from Microsoft's study guide, updated 2026-04-15)

### Domain 1 — Develop containerized solutions on Azure (20–25%)

**Container application hosting**
- [ ] Build, store, version, and manage container images using Azure Container Registry (ACR)
- [ ] Build and run images using ACR Tasks
- [ ] Deploy containers to Azure App Service (incl. environment variables and secrets)

**Container-orchestrated solutions**
- [ ] Deploy apps to Azure Container Apps (environment config, revision management)
- [ ] Implement event-driven scaling with KEDA in Container Apps
- [ ] Deploy and manage apps on AKS using manifest files
- [ ] Monitor and troubleshoot AKS / Container Apps (logs, events, end-to-end connectivity)

### Domain 2 — Develop AI solutions using Azure data management services (25–30%) ⭐ biggest domain

**Azure Cosmos DB for NoSQL**
- [ ] Connect via SDK and run queries
- [ ] Optimize query performance and RU consumption (indexing policies, consistency levels)
- [ ] Store/retrieve embeddings and run vector similarity search
- [ ] Implement a change feed processor

**Azure Database for PostgreSQL**
- [ ] Connect and query via SDKs
- [ ] Model schemas and design tables with appropriate data types
- [ ] Indexing strategies (query latency, pgvector compute overhead)
- [ ] Configure compute/memory/storage for vector workloads
- [ ] Vector similarity search + RAG patterns with metadata filters
- [ ] Connection optimization (throughput, latency)

**Azure Managed Redis**
- [ ] Data operations: caching, expiration, invalidation
- [ ] Vector indexing for similarity search

### Domain 3 — Connect to and consume Azure services (20–25%)

**Event- and message-based solutions**
- [ ] Azure Service Bus: queues, topics, subscriptions, dead-letter queue handling
- [ ] Azure Event Grid: filters, custom events, retries

**Azure Functions**
- [ ] Build serverless APIs with triggers and bindings
- [ ] Configure and deploy function apps

### Domain 4 — Secure, monitor, troubleshoot Azure solutions (20–25%)

**Secure solutions**
- [ ] Azure Key Vault: secret storage, rotation, retrieval
- [ ] Azure App Configuration: store/retrieve app config

**Monitor and troubleshoot**
- [ ] Distributed tracing with OpenTelemetry SDKs
- [ ] Write KQL queries to analyze logs and metrics

---

## 🗓️ Study plan (10 weeks)

| Week | Focus | Deliverable in repo |
|------|-------|---------------------|
| 0 | Local Docker basics (no Azure yet) | `docker-basics/` — containerized FastAPI app |
| 1–2 | Domain 1: ACR, App Service, Container Apps | Deploy my container to Container Apps |
| 3 | Domain 1: AKS + KEDA | AKS manifest files + scaling demo |
| 4–5 | Domain 2: Cosmos DB (SDK, RUs, vectors, change feed) | Vector search demo in Python |
| 6 | Domain 2: PostgreSQL + pgvector, RAG pattern | Mini RAG app with metadata filters |
| 7 | Domain 2: Redis + Domain 3: Service Bus, Event Grid | Event-driven pipeline demo |
| 8 | Domain 3: Functions + Domain 4: Key Vault, App Config | Serverless API with secrets |
| 9 | Domain 4: OpenTelemetry + KQL | Tracing + sample KQL queries in notes |
| 10 | Review weak areas, exam sandbox, practice questions | Revision cheat sheet |

---

## 💰 Cost-control rules

- Budget alert set at $5 in Azure Cost Management ✅
- Delete resource groups after every lab session (code lives here, redeploy anytime)
- Use Cosmos DB **free tier** (survives past the 30-day trial)
- Prefer Container Apps consumption plan / Functions consumption plan (scale to zero)

---

## 📝 Progress log

| Date | What I did | Commit |
|------|-----------|--------|
| | | |
