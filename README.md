<div align="center">

<img src="assets/hero.svg" width="100%" alt="Rami Khaldon Abu Lebdeh — Data Science & Artificial Intelligence · AI Engineering · Agentic AI · Multi-Agent Systems · Data Intelligence">

<h3>Building intelligent systems that combine AI agents, LLMs, machine learning, and data to solve real-world problems.</h3>

<code>Python</code>&nbsp; <code>SQL</code>&nbsp; <code>LangGraph</code>&nbsp; <code>FastAPI</code>&nbsp; <code>RAG</code>&nbsp; <code>PostgreSQL</code>&nbsp; <code>Machine Learning</code>

<sub>
<a href="#featured-projects"><b>Projects</b></a> &nbsp;·&nbsp;
<a href="#experience"><b>Experience</b></a> &nbsp;·&nbsp;
<a href="#tech-stack"><b>Stack</b></a> &nbsp;·&nbsp;
<a href="#contact"><b>Contact</b></a> &nbsp;·&nbsp;
Amman, Jordan
</sub>

</div>

<br>

## What I build

<table>
<tr>
<td width="50%" valign="top">

**`01` &nbsp;Agentic AI**

Agents with defined responsibilities, coordinated by an explicit orchestration layer instead of left to improvise.

<sub>AI agents · agentic workflows · multi-agent orchestration · LLM applications · tool-based workflows · RAG</sub>

</td>
<td width="50%" valign="top">

**`02` &nbsp;Data Intelligence**

Systems that go past *what* changed in the data and investigate *why* — with the evidence attached.

<sub>Business intelligence · analytical investigation · evidence-grounded answers · data validation · machine learning</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**`03` &nbsp;Decision Intelligence**

Decisions examined from several specialized angles, checked, and escalated to people when the stakes require it.

<sub>Multi-perspective reasoning · enterprise decision support · organizational memory · governance · verification</sub>

</td>
<td width="50%" valign="top">

**`04` &nbsp;AI Products**

End-to-end applications that put AI inside a real workflow — with the backend, data model, and controls around it.

<sub>Conversational AI · AI assistants · backend AI systems · end-to-end applications · real business workflows</sub>

</td>
</tr>
</table>

<br>

## Featured projects

<img src="assets/darb.svg" width="100%" alt="DARB — Autonomous Business Intelligence Platform. Flagship AI / data intelligence project, private case study. Workflow: business question → context / data → planning → SQL + analysis → hypotheses → validation → verification → business answer.">

<table>
<tr>
<td width="50%" valign="top">

**The problem**<br>
Dashboards show *what* changed. Finding out *why* still takes an analyst, a query editor, and hours of back-and-forth — and the answer rarely shows its evidence.

</td>
<td width="50%" valign="top">

**What I built**<br>
Designed and built DARB: an investigation workflow that plans, queries the data read-only, tests candidate causes, and answers with the queries and results behind every figure.

</td>
</tr>
</table>

<details>
<summary><b>Capabilities &amp; architecture</b></summary>
<br>

| Layer | What it does |
|---|---|
| **Investigation** | Business-question investigation · planning · multi-agent orchestration · hypothesis management |
| **Analysis** | SQL generation · data-quality analysis · statistical analysis · visualization · reporting |
| **Trust** | Evidence grounding · validation · verification — any figure no query result supports is flagged as unverified |
| **Operations** | Scheduled metric monitoring that can start an investigation on its own · organization-scoped access · audit trail |
| **Interface** | Arabic and English, Arabic-first RTL |

**Stack** &nbsp; Python · FastAPI · SQL · DuckDB · PostgreSQL · RAG · Claude / OpenAI · Next.js · TypeScript

</details>

<p align="right"><sub><b>PRIVATE PROJECT</b> — the case study above is the public layer.</sub></p>

<br>

<img src="assets/apex.svg" width="100%" alt="APEX — Autonomous Process & Enterprise X-Framework. Flagship multi-agent decision intelligence platform, completed. Decision request → CEO executive orchestrator → specialized executive agents (CFO, CMO, CRO, CLO, CHRO, CTO), organizational memory (CDO) and governance (BRD) → evidence / claims → QA verification → decision intelligence → human decision maker.">

**APEX is a completed enterprise-grade multi-agent decision intelligence platform I designed and built to orchestrate specialized AI executives, retrieve organizational knowledge, validate evidence, apply governance controls, and produce structured, auditable decisions.**

<sub>Agentic AI · Multi-Agent Systems · LLM Engineering · RAG · Decision Intelligence · AI Governance · Backend Architecture</sub>

<table>
<tr>
<td width="50%" valign="top">

**The problem**<br>
Cross-functional decisions crawl through departments one at a time, while a general-purpose assistant offers a single unchecked narrative — with no way to notice that its financial assumption contradicts its legal one.

</td>
<td width="50%" valign="top">

**What I built**<br>
I architected the system and implemented it end to end: a LangGraph state graph that runs ten specialized executive agents, retrieves precedent from organizational memory, verifies every claim, and escalates to a human whenever a governance threshold is crossed.

</td>
</tr>
</table>

<details>
<summary><b>The ten specialized units</b> — distinct responsibilities, not ten copies of one chatbot</summary>
<br>

| Unit | Responsibility |
|---|---|
| **CEO** | Executive orchestrator — decomposes the decision and coordinates the council |
| **CFO** | Financial implications |
| **CMO** | Market and marketing considerations |
| **CRO** | Revenue implications |
| **CLO** | Legal and compliance — a veto gate before a decision can pass |
| **CHRO** | Workforce and organizational implications |
| **CTO** | Technical feasibility |
| **CDO** | Organizational memory — retrieves relevant precedents *before* analysis begins |
| **QA** | Quality assurance — checks claims and output consistency |
| **BRD** | Board governance — escalation rules decide when a human must decide or approve |

</details>

<details>
<summary><b>What I engineered</b></summary>
<br>

| Layer | Implementation |
|---|---|
| **Orchestration** | Deterministic LangGraph state graph with parallel executive analysis and negotiation when positions conflict |
| **Agents** | The executive agent ecosystem — each unit role-constrained to one perspective on the decision |
| **Memory & RAG** | Organizational memory and precedent retrieval on PostgreSQL + pgvector |
| **Verification** | QA layer that checks claims, evidence, and consistency before a decision is assembled |
| **Decision intelligence** | Structured decision dossiers built from the council's verified output |
| **Governance** | Board escalation rules, human approval, and role-based authority over consequential decisions |
| **Auditability** | Decision traces — every step recorded, replayable, and auditable |
| **Platform** | FastAPI backend, Next.js frontend integration, persistence, and a provider-agnostic model-routing abstraction |

Taken through final hardening and verification as a completed system.

</details>

<p align="right"><sub><b>STATUS: COMPLETED</b> &nbsp;·&nbsp; PRIVATE — ARCHITECTURE CASE STUDY</sub></p>

<br>

<img src="assets/shifaa.svg" width="100%" alt="SHIFAA — AI Assistant for Clinics. Applied AI / conversational agent, private case study. A patient messages on WhatsApp; the AI agent routes the request to booking via a deterministic scheduler, grounded answers from clinic documents (RAG), or handoff to staff. Consequential actions are previewed, confirmed by a person, and re-verified against live data.">

<table>
<tr>
<td width="50%" valign="top">

**The problem**<br>
Clinic teams lose their day to routine WhatsApp messages, calendar changes, and reminders — while freed-up appointment slots sit empty.

</td>
<td width="50%" valign="top">

**What I built**<br>
Designed and built end-to-end: a WhatsApp agent that books against real availability, answers from the clinic's own documents, sends reminders, offers freed slots to a waitlist, and hands anything clinical or uncertain to staff — plus the staff dashboard and copilot.

</td>
</tr>
</table>

<p align="right"><sub><b>PRIVATE PROJECT</b> &nbsp;·&nbsp; Python · FastAPI · LangGraph · Claude · PostgreSQL · pgvector · WhatsApp Cloud API · Next.js · TypeScript</sub></p>

<br>

<a href="https://github.com/ramilebdeh2005-ux/Bellabelt"><img src="assets/bellabeat.svg" width="100%" alt="Bellabeat Fitness Data Analysis — data analytics / business intelligence, public repository. Raw data → cleaning → exploratory analysis → behavioral patterns → visualization → business insights."></a>

Analysis of Fitbit activity and sleep data to support Bellabeat's marketing strategy: cleaning and merging the datasets, engineering an *awake-in-bed* feature, user-level behavioural analysis, and recommendations such as personalized activity reminders and behavioural segmentation.

<p align="right"><a href="https://github.com/ramilebdeh2005-ux/Bellabelt"><b>View repository →</b></a></p>

<br>

## The thread

<img src="assets/journey.svg" width="100%" alt="From data to intelligence to autonomy: Bellabeat (data analysis) → DARB (data intelligence + AI agents) → APEX (decision intelligence + multi-agent) → SHIFAA (applied AI product).">

<p align="center"><sub>Different problems, one direction: turning data and AI agents into systems people can actually rely on.</sub></p>

<br>

## Experience

**AI Intern — Shamsieh Technology Services** &nbsp;·&nbsp; <sub>Amman, Jordan &nbsp;·&nbsp; July 2026 – August 2026 &nbsp;·&nbsp; 240 hours</sub>

- Built a grounded RAG knowledge-base assistant with source citations and explicit "not found" handling — [`AI-Agent`](https://github.com/ramilebdeh2005-ux/AI-Agent).

<br>

## Tech stack

| Area | Technologies |
|---|---|
| **AI & Agentic AI** | AI Agents · Agentic Workflows · Multi-Agent Systems · LLM Applications · RAG · LangGraph |
| **Programming** | Python · SQL · TypeScript |
| **ML & Data Science** | Machine Learning · Deep Learning · NLP · Scikit-learn · Pandas · NumPy · EDA · Data Cleaning · Feature Engineering · Predictive Modeling · Model Evaluation |
| **Backend & Data** | FastAPI · REST APIs · PostgreSQL · DuckDB |
| **Analytics & BI** | Power BI · Tableau · Data Analysis · Data Visualization · Dashboard Development |
| **Frontend** | Next.js · React · Tailwind CSS |
| **Tools** | Git · GitHub · Jira · Jupyter Notebook · VS Code |

<br>

## Engineering approach

| Principle | In practice |
|---|---|
| **Build systems, not demos** | Auth, audit trails, tests, and failure handling are part of the first design, not a later phase. |
| **Ground AI outputs in evidence** | DARB attaches the query and result behind every figure, and flags any number nothing supports. |
| **Probabilistic AI, deterministic checks** | In SHIFAA the model chooses what to ask for; deterministic code decides what is allowed to happen. |
| **Agents around clear responsibilities** | APEX units are role-constrained — each owns one perspective on the decision. |
| **Orchestration over improvisation** | Explicit state graphs define who runs, when, and with which inputs. |
| **Governance is system design** | Human approval and escalation thresholds are built in, not bolted on. |
| **Real problems first** | Start from a workflow someone actually runs, then decide where AI belongs in it. |

<br>

## Currently exploring

Agentic AI · Multi-Agent Systems · LLM Applications · RAG · AI Data Intelligence · Decision Intelligence · Machine Learning · Production-oriented AI systems · AI system architecture

<br>

## Education & certifications

**B.Sc. in Data Science and Artificial Intelligence** — Amman Arab University &nbsp;·&nbsp; <sub>Expected 2027</sub>

| Issuer | Certification |
|---|---|
| **IBM** | Building AI Agents and Agentic Workflows |
| **Microsoft** | Power BI Data Analyst Professional Certificate |
| **Google** | Data Analytics Professional Certificate |
| **Microsoft Certified** | Azure Data Fundamentals (DP-900) |
| **Shamsieh Technology Services** | Certificate of AI Practical Training (240 hours) |

<br>

## Contact

<p>
<a href="https://www.linkedin.com/in/rami-abu-lebdeh-2888a240"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-rami--abu--lebdeh-22D3EE?style=for-the-badge&labelColor=0B1020"></a>
<a href="mailto:rami.lebdeh2005@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-rami.lebdeh2005%40gmail.com-818CF8?style=for-the-badge&labelColor=0B1020"></a>
<a href="https://github.com/ramilebdeh2005-ux"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-ramilebdeh2005--ux-2DD4BF?style=for-the-badge&labelColor=0B1020"></a>
</p>

<sub>Open to conversations about AI engineering, agentic systems, and data intelligence.</sub>