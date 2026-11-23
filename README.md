# Hi, I'm Exryz

**AI/ML Engineer building grounded, verifiable LLM systems: RAG agents, document AI, and evaluation pipelines.**

B.S. Computer Science graduate from National University Laguna, former AI/ML Intern at CGI Philippines, and former AI Tech Lead for Microsoft Student Community – NU Laguna. I focus on turning LLM and computer vision workflows into reliable, measurable software with deterministic verification, structured schemas, and production observability.

[![GitHub](https://img.shields.io/badge/GitHub-Exryz-181717?style=flat&logo=github&logoColor=white)](https://github.com/Exryz)
[![helpdesk-agent](https://img.shields.io/badge/helpdesk--agent-RAG%20%2B%20MCP-0F766E?style=flat&logo=github&logoColor=white)](https://github.com/Exryz/helpdesk-agent)
[![docextract](https://img.shields.io/badge/docextract-Document%20AI-1D4ED8?style=flat&logo=github&logoColor=white)](https://github.com/Exryz/docextract)

---

## Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Exryz/helpdesk-agent">helpdesk-agent</a></h3>
      <p><em>Production-style IT support agent combining hybrid RAG citations, MCP ticketing tools, and telemetry.</em></p>
      <ul>
        <li><strong>Hybrid Retrieval + Reranking:</strong> Combines BM25 and dense Qdrant/fastembed search with Reciprocal Rank Fusion and cross-encoder reranking (<code>hybrid_rerank</code> Hit@4 <strong>100.0%</strong>, MRR <strong>0.966</strong>; dense MRR <strong>0.982</strong> across 37 labelled queries).</li>
        <li><strong>Agent &amp; MCP Tooling:</strong> LangGraph workflow executing ticket operations over <code>stdio</code> MCP, with Playwright portal scraping/autofill and confirmation before ticket mutations.</li>
        <li><strong>Integrations &amp; Ops:</strong> SSE token streaming, Chainlit UI, HMAC-verified Slack/Teams webhooks, SLA breach detection, KB hot-reload watcher, and SQLite telemetry with InfluxDB export.</li>
        <li><strong>Quality:</strong> Backed by <strong>89 passing offline tests</strong> and GitHub Actions CI.</li>
      </ul>
      <p><sub><strong>Stack:</strong> Python, LangGraph, LiteLLM, FastAPI, Qdrant, fastembed, MCP, Playwright, SQLite, InfluxDB, Chainlit</sub></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Exryz/docextract">docextract</a></h3>
      <p><em>Verified invoice and receipt Document AI pipeline pairing LLM extraction with deterministic financial checks.</em></p>
      <ul>
        <li><strong>Ingest &amp; Hybrid Layout:</strong> Magic-byte MIME validation, <code>pypdfium2</code> word bounding boxes, projection deskew, and CPU ONNX OCR fallback for scans.</li>
        <li><strong>Grounded Extraction &amp; Rules:</strong> LiteLLM Pydantic schema extraction with repair loop, bounding-box grounding, and deterministic <code>Decimal</code> math, tax, date, and ISO 13616 IBAN mod-97 validation.</li>
        <li><strong>Review Queue &amp; Delivery:</strong> Multi-signal field confidence, SQLModel state machine + audit log, FastAPI + Jinja2/HTMX review UI with clickable SVG bbox overlays, HMAC webhooks, and CSV/JSON export.</li>
        <li><strong>Verification &amp; Evals:</strong> Dockerized, <code>mypy --strict</code>, <strong>46 passing tests</strong>; <strong>100% fault-injection catch rate</strong> and <strong>99.1% bbox grounding coverage</strong> on the 24-document offline synthetic benchmark.</li>
      </ul>
      <p><sub><strong>Stack:</strong> Python, FastAPI, Pydantic, LiteLLM, pypdfium2, RapidOCR, SQLModel, Jinja2, HTMX, Docker, mypy</sub></p>
    </td>
  </tr>
</table>

---

## Experience

**AI/ML Intern — CGI Philippines** *(Dec 2025 – Jul 2026)*
- Built an internal IT support chatbot powered by Azure OpenAI (GPT-4o mini) and RAG to support ticketing and troubleshooting workflows.
- Implemented Playwright web-scraping automation scripts to streamline ticket data retrieval and status tracking.
- Authored technical documentation and structured knowledge base articles used by internal engineering teams and the chatbot retrieval pipeline.

**AI Tech Lead — Microsoft Student Community – NU Laguna** *(Jun 2025 – Jul 2026)*
- Led the planning and delivery of AI and machine learning workshops, bootcamps, and hands-on technical training sessions.
- Designed structured learning roadmaps and collaborated with guest speakers, mentors, and partner organizations.
- Mentored student members on applied AI/ML projects and guided continuous technical upskilling.

---

## Education

**B.S. Computer Science — National University Laguna** *(2023 – 2026)*
- **Thesis:** Real-time exercise form assessment (deadlift and power clean) using MediaPipe 33-landmark pose estimation with a hybrid CNN-LSTM architecture and MobileNetV2 transfer learning, delivering 0–100% form scoring and corrective feedback.

**Continuous Learning & Coursework**
- **Cloud & DevOps:** Enterprise ML on AWS/GCP/Azure, AWS Monitoring & Lambdas (2026)
- **AI & Machine Learning:** Deep Learning, Reinforcement Learning, NLP with Python, Enterprise ML Pipelines (2026)
- **Data Engineering & Agile:** Streaming Data Architectures (Spark), Python Data Visualization (2026); Agile Development Bootcamp (2025)

---

## Tech Stack

<p>
  <img src="https://skillicons.dev/icons?i=python,fastapi,docker,githubactions,aws,azure,sqlite,postgres,git,linux&perline=10" alt="Core Tech Icons" />
</p>

| Category | Technologies |
|---|---|
| **Languages & Core** | Python 3.11, Pydantic, SQLModel |
| **AI & LLM** | LangGraph, LiteLLM, RAG, MCP, Azure OpenAI, Gemini, MediaPipe, CNN-LSTM, MobileNetV2 |
| **Retrieval & Data** | Qdrant, BM25, Cross-Encoder Reranking, SQLite, PostgreSQL |
| **Backend & APIs** | FastAPI, REST APIs, SSE Streaming, Webhooks (HMAC), Playwright, Jinja2, HTMX |
| **Cloud & DevOps** | AWS (Lambda, Monitoring), Microsoft Azure, Docker, GitHub Actions, Linux |
| **Monitoring** | InfluxDB, Grafana |
| **Tools & Practices** | Git, Jira, `pytest`, `ruff`, `mypy`, Jupyter, Google Colab, Agile |

---

## GitHub Metrics

<p align="center">
  <img src="metrics.base.svg" alt="GitHub Base Metrics" />
  <img src="metrics.repositories.svg" alt="Featured Repositories Metrics" />
</p>
<p align="center">
  <img src="metrics.languages.svg" alt="Most Used Languages Metrics" />
  <img src="metrics.isocalendar.svg" alt="GitHub Contribution Isocalendar" />
</p>

---

*Open to AI/ML Engineer, Applied AI, and Backend AI opportunities.*
