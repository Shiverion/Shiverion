<picture>
  <source media="(max-width: 700px)" srcset="https://raw.githubusercontent.com/Shiverion/portfolio-project-index/main/assets/shiverion-signal-mobile.svg">
  <img src="https://raw.githubusercontent.com/Shiverion/portfolio-project-index/main/assets/shiverion-signal-desktop.svg" width="100%" alt="Muhammad Iqbal Hilmy Izzulhaq — building evidence-first agentic AI, retrieval systems, and applied machine learning products">
</picture>

<h1 align="center">AI systems that can show their work.</h1>

<p align="center">
  I build agent tools, retrieval systems, and production AI products —<br>
  with the evidence, constraints, and failure boundaries documented beside the result.
</p>

<p align="center"><samp>AI ENGINEER · DATA SCIENTIST · JAKARTA, INDONESIA</samp></p>

<p align="center">
  <a href="https://shiverion.com/"><img alt="Portfolio" src="https://img.shields.io/badge/PORTFOLIO-SHIVERION.COM-0B1220?style=for-the-badge&amp;logo=safari&amp;logoColor=67E8F9"></a>
  <a href="https://github.com/Shiverion/portfolio-project-index"><img alt="Project index" src="https://img.shields.io/badge/PROJECT%20INDEX-EXPLORE-0B1220?style=for-the-badge&amp;logo=github&amp;logoColor=F8FAFC"></a>
  <a href="https://www.linkedin.com/in/izzulhaq-iqbal/"><img alt="LinkedIn" src="https://img.shields.io/badge/LINKEDIN-CONNECT-0B1220?style=for-the-badge&amp;logo=linkedin&amp;logoColor=60A5FA"></a>
  <a href="https://medium.com/@miqbal.izzulhaq"><img alt="Medium" src="https://img.shields.io/badge/MEDIUM-READ-0B1220?style=for-the-badge&amp;logo=medium&amp;logoColor=F8FAFC"></a>
  <a href="mailto:miqbal.izzulhaq@gmail.com"><img alt="Email" src="https://img.shields.io/badge/EMAIL-SAY%20HELLO-0B1220?style=for-the-badge&amp;logo=gmail&amp;logoColor=FCA5A5"></a>
</p>

<p align="center">
  <samp>
    <a href="#about">ABOUT</a> ·
    <a href="#how-i-work">HOW I WORK</a> ·
    <a href="#practice">PRACTICE</a> ·
    <a href="#evidence-of-practice">EVIDENCE</a> ·
    <a href="#system-design">SYSTEM DESIGN</a> ·
    <a href="#connect">CONNECT</a>
  </samp>
</p>

<p align="center"><sub>Profile context first · detailed project records live in the <a href="https://github.com/Shiverion/portfolio-project-index">project index</a></sub></p>

---

## About

I'm **Muhammad Iqbal Hilmy Izzulhaq** (`@Shiverion`), an AI engineer and data scientist based in Jakarta, Indonesia. I work at the intersection of **agentic AI, retrieval, evaluation, and product engineering**.

My work moves between research and delivery: benchmarking RAG on Indonesian legal documents, designing MCP tool servers, building bioinformatics evidence workbenches, developing real-time voice interfaces, fine-tuning small language models, and turning applied ML into usable workflows. I care about the seam between a model's answer and the decision a person has to make with it.

### The work around the work

| Context | What that means in practice |
| --- | --- |
| **Business and delivery** | Director of Business Development at PT Internasional Teknik Nusantara, connecting technical systems to real organizational needs. |
| **Teaching and enablement** | AI Tech & Data mentor and team lead for corporate training programs, including work with Bayan Resources, PT Jalin, AXA Mandiri, and Indosat Hutchinson. |
| **Technical throughline** | Make the system useful, make its boundaries visible, and measure whether it actually works. |

> **Working principle:** AI should know its limits, show its evidence, and earn its place in a real workflow.

## How I work

| Habit | Question behind it |
| --- | --- |
| **Start with the decision** | What is the person or team actually trying to decide, and what would make the output useful? |
| **Treat boundaries as product features** | What data can the system see, what can it change, and where must a human take over? |
| **Test the claim, not just the demo** | Does the system hold up under human review, time-safe splits, execution checks, cost analysis, or failure analysis? |
| **Ship the surface around the model** | Can someone authenticate, understand the result, recover from failure, and use it inside a real workflow? |

## Practice

| Area | The problems I like working on | Typical tools |
| --- | --- | --- |
| **Agentic systems** | Tool orchestration, MCP servers, multi-agent workflows, and explicit data boundaries | `MCP` · `OpenAI Agents SDK` · `LangGraph` · `CrewAI` · `n8n` |
| **Retrieval and evaluation** | RAG, long context, hybrid search, fine-tuning, and evidence-grounded comparison | `FAISS` · `BM25` · `IndoBERT` · `QLoRA` · `Gemini` · `OpenAI` |
| **Production AI** | Voice interfaces, document intelligence, auth, quotas, persistence, and operational delivery | `Next.js` · `React` · `FastAPI` · `Firebase` · `WebRTC` · `Cloud Run` |
| **Applied ML and data** | Forecasting, classification, bioinformatics evidence triage, model interpretation, and resource-aware analysis | `Python` · `PyTorch` · `scikit-learn` · `Pandas` · `Perturb-seq` · `Polars` · `DuckDB` · `SQL` |

## Evidence of practice

The numbers below are anchors, not a substitute for the reasoning behind them. Each one links to the artifact where the method and boundary are visible.

| Signal | What it demonstrates |
| ---: | --- |
| **300 human-reviewed QA pairs** across 50 verdicts | [VerdictBench](https://github.com/Shiverion/VerdictBench-LCvsRAG) — benchmark design, annotation, and comparative RAG evaluation |
| **16–25× lower cost** for Dense RAG in the evaluated setup | [VerdictBench paper](https://openreview.net/forum?id=46hzq45LPE) — quality, cost, and failure behavior considered together |
| **40% → 73.5% valid SQL** | [Text2SQL fine-tuning](https://github.com/Shiverion/text2sql-finetuning) — small-model fine-tuning paired with execution-based evaluation |
| **384 chronologically held-out matches** | [World Cup prediction engine](https://github.com/Shiverion/ml-world-cup-prediction) · [Live demo](https://ml-world-cup-prediction-2026.streamlit.app/) — time-aware features, rolling backtests, and proper scoring |
| **10 MCP tools with deterministic evals** | [EPC tender screening MCP](https://github.com/Shiverion/epc-tender-screening-mcp-showcase) — reviewable orchestration, evidence traces, and security boundaries |
| **33,983 perturbation-condition rows audited** | [T-cell Evidence Workbench](https://github.com/Shiverion/t-cell-evidence-workbench) · [Live workbench](https://tcell-evidence.shiverion.com/) — six registered source-QC gates, 1,652 eligible rows, and 224 genes passing all gates across three conditions |
| **98% less memory · up to 100× faster** under benchmarked workloads | [Dataframe benchmark](https://shiverion.com/projects/dataframe-benchmark) — resource-aware engineering on 13.1M rows |

## System Design

Every project README in this account carries its own **System Design** section: requirements, high-level architecture, data model, scale and reliability, trade-offs, and what to revisit as the system grows. The same few patterns recur across them.

### How I approach a design

1. **Requirements first**: functional scope, non-functional targets (latency, cost, privacy, safety), and the real constraints (team of one, free tier, existing tools).
2. **High-level design**: components, data flow, API contracts, and storage choice, drawn before code.
3. **Deep dive** where risk concentrates: data model, validation boundaries, retries and fallbacks.
4. **Scale and reliability**: estimated load, the binding limit, failover paths, and what is observed.
5. **Explicit trade-offs**: each decision recorded with its benefit, its cost, and the trigger to revisit it.

### Patterns that recur

| Pattern | Why | Where to see it |
| --- | --- | --- |
| **Hard boundaries below the model** (database grants, AST allow-lists, schema-validated outputs) | Safety cannot depend on prompt compliance | [techtest](https://github.com/Shiverion/techtest) · [EPC tender screening MCP](https://github.com/Shiverion/epc-tender-screening-mcp-showcase) |
| **Numbers come from code, words from the model** | No hallucinated figures in answers | [techtest](https://github.com/Shiverion/techtest) · [InterviewMate](https://github.com/Shiverion/interviewmate-ai) |
| **Local-first, cloud-optional** | Offline use, privacy, near-zero hosting cost | [Gymboard](https://github.com/Shiverion/gymboard) · [AeroRUL](https://github.com/Shiverion/AeroRUL) static dashboard |
| **Provider fallback and graceful degradation** | One vendor outage should not take the product down | [Portfolio Career-Twin](https://shiverion.com/) · [itn-ops-dashboard](https://github.com/Shiverion/itn-ops-dashboard) |
| **Frozen protocols and gated pipelines** | Results that can be reproduced and challenged | [Indonesia Wildfire Analysis](https://github.com/Shiverion/indonesia-wildfire-analysis) · [HealthReach Indonesia](https://github.com/Shiverion/HealthReach-Indonesia) · [VerdictBench](https://github.com/Shiverion/VerdictBench-LCvsRAG) |
| **Free-tier serverless by default** | Personal projects should cost nothing at idle | Most live demos (Vercel, Cloud Run, Firebase) |

## Current focus

- Building MCP-compatible tools that let agents act inside explicit, inspectable boundaries.
- Evaluating retrieval and long-context systems with human review, time-safe splits, execution checks, and cost analysis.
- Turning useful AI prototypes into products with auth, quotas, persistence, recovery paths, and CI/CD.
- Building bioinformatics workbenches that preserve source QC, provenance, and scientific inference boundaries.
- Helping teams adopt AI through practical training, implementation, and clearer technical decisions.

## Project trail

This README is intentionally about the person and the practice. The detailed portfolio index carries the project-level record: categories, depth levels, public timelines, evidence, access status, repositories, live products, and private-source context.

<table>
  <tr>
    <td><strong>Start with the person</strong><br>Read the practice, principles, and current focus here.</td>
    <td><strong>Follow the evidence</strong><br>Browse the <a href="https://github.com/Shiverion/portfolio-project-index">full project index</a> when you want the detailed work.</td>
    <td><strong>Try the products</strong><br>Visit the <a href="https://shiverion.com/projects">portfolio projects</a> for live demos and case studies.</td>
  </tr>
</table>

## Connect

- **Portfolio:** [shiverion.com](https://shiverion.com/)
- **Project index:** [github.com/Shiverion/portfolio-project-index](https://github.com/Shiverion/portfolio-project-index)
- **LinkedIn:** [linkedin.com/in/izzulhaq-iqbal](https://www.linkedin.com/in/izzulhaq-iqbal/)
- **Writing:** [medium.com/@miqbal.izzulhaq](https://medium.com/@miqbal.izzulhaq)
- **Email:** [miqbal.izzulhaq@gmail.com](mailto:miqbal.izzulhaq@gmail.com)

---

<p align="center">
  <sub>“Mystery gives life meaning. Agency gives life motion.”</sub><br>
  <samp>OBSERVE // RETRIEVE // REASON // EVALUATE</samp>
</p>
